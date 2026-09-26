## Metadados
-
- Millena Dias Santana - 47555041
- 
# Sistema-de-Estoque-e-Vendas-do-Mercado-Santana

## 1. Caracterização da Organização

- **Nome e natureza da organização:** O Mercado Santana é um estabelecimento comercial do setor varejista, voltado à comercialização de produtos alimentícios e domésticos. A organização foi escolhida por ser um estabelecimento real ao qual o grupo possui acesso para realizar a pesquisa de campo.
- **Contexto e porte:** O Mercado Santana está em funcionamento desde 2013 e possui uma operação de pequeno porte, contando geralmente com 2 pessoas envolvidas nas atividades do estabelecimento. Entre os produtos comercializados estão alimentos, bebidas, produtos de limpeza e itens domésticos.
- **Problemas e necessidades identificados:** Atualmente, o mercado não possui um sistema informatizado para controle de vendas e estoque. A quantidade dos produtos é acompanhada principalmente por observação física das prateleiras, sem registro das entradas e saídas de mercadorias.
 Essa forma de controle já ocasionou situações de falta de produtos e compras em quantidade maior do que a necessária. Além disso, não há um histórico detalhado das vendas, dificultando a identificação dos produtos mais vendidos.
- **Justificativa da escolha:** O Mercado Santana foi escolhido por ser uma organização real e acessível ao grupo, possibilitando a realização de uma pesquisa de campo. Além disso, os problemas identificados no controle de estoque e vendas apresentam uma oportunidade para desenvolver uma solução de banco de dados que possa melhorar a organização das informações e auxiliar no gerenciamento do estabelecimento.
- **Evidências da organização:** As fotos para as evidências da existência da organização e da realização da pesquisa de campo estão disponíveis na pasta [Evidências](./Evidências).

 **Endereço:** [Av. Naylor de Oliveira, 116 - Cidade Tiradentes, São Paulo - SP, 08470-800]
 **Telefone:** [11 97157-9851]
 **Google Maps:** [Google Maps — Mercado Santana](https://www.google.com/maps/search/?api=1&query=Mercado+Santana)
 **Responsável:** [Fernando Ribeiro]

---

## 2. Processos de Negócio

**Processo de Vendas:** Inicia quando o cliente escolhe o produto e se dirige ao caixa. O valor é calculado e o cliente realiza o pagamento. No modelo atual, a venda não é registrada imediatamente no sistema; esse registro ocorre apenas no fechamento do caixa ao final do dia.  

**Controle de Estoque:** Depende da observação visual das prateleiras por parte do funcionário. Se o produto estiver acabando (Sim), identifica-se a necessidade de reposição para realizar uma nova compra; caso contrário (Não), a rotina segue normalmente.  

**Processo de Compras:** O funcionário observa as prateleiras e identifica a falta do produto. O responsável decide o que comprar e efetua o pedido. Quando a mercadoria chega, a quantidade é conferida, o produto é guardado e a nota fiscal é armazenada.  

**Processo Proposto:** Integra as operações por meio de software. O produto é previamente cadastrado. Assim que a venda é realizada, o produto vendido é registrado automaticamente e o estoque é atualizado em tempo real. O sistema exibe o saldo atual e, caso o item fique abaixo do estoque mínimo, gera um alerta de reposição para disparar uma nova compra. 

- **Fluxogramas** representados visualmente na pasta [Fluxograma](./Fluxograma).

---

## 3. Requisitos do Sistema
Os requisitos do sistema foram definidos a partir dos problemas identificados no Mercado Santana, principalmente relacionados à ausência de controle informatizado das vendas e do estoque. Atualmente, as vendas não são registradas em um sistema e o estoque é acompanhado visualmente, o que dificulta o controle das entradas e saídas, a identificação dos produtos mais vendidos e a reposição de mercadorias. 

### 3.1 Requisitos Funcionais
- **RF01 — Cadastro de produtos:** o sistema deve permitir cadastrar e consultar os produtos comercializados pelo mercado.
- **RF02 — Registro de vendas:** o sistema deve permitir registrar as vendas realizadas e os produtos vendidos em cada operação.
- **RF03 — Controle de estoque:** o sistema deve registrar as entradas e saídas de produtos e manter atualizada a quantidade disponível.
- **RF04 — Consulta de estoque:** o sistema deve permitir consultar a quantidade disponível de cada produto.
- **RF05 — Controle de estoque mínimo:** o sistema deve permitir definir uma quantidade mínima para cada produto e identificar quando ela for atingida.
- **RF06 — Reposição:** o sistema deve permitir identificar os produtos que necessitam de reposição.
- **RF07 — Histórico de vendas:** o sistema deve armazenar as vendas realizadas para possibilitar consultas posteriores e identificar os produtos mais vendidos.
- **RF08 — Controle de produtos não comercializáveis:** o sistema deve permitir registrar produtos vencidos ou danificados.
- **RF09 — Registro de entradas:** o sistema deve permitir registrar a entrada de mercadorias e as respectivas quantidades recebidas.

### 3.2 Requisitos Não Funcionais
- **RNF01 — Usabilidade:** o sistema deve possuir uma interface simples e intuitiva, facilitando seu uso pelos responsáveis pelo estabelecimento.
- **RNF02 — Segurança:** o acesso às informações e funcionalidades deve ser restrito a usuários autorizados.
- **RNF03 — Integridade:** o sistema deve manter os dados consistentes e evitar registros que comprometam o controle de vendas e estoque.
- **RNF04 — Confiabilidade:** os registros armazenados devem permanecer disponíveis para consultas posteriores.


---

## 4. Regras de Negócio
- **Regras operacionais:**
  - Cada produto deve possuir uma identificação única no sistema.
  - A quantidade disponível de um produto não pode ser inferior a zero.
  - Ao registrar uma venda, a quantidade vendida deve ser subtraída do estoque.
  - Ao registrar uma entrada, a quantidade recebida deve ser adicionada ao estoque.
  - Cada produto pode possuir uma quantidade mínima definida para orientar a reposição.
  - Quando o estoque estiver abaixo do mínimo estabelecido, o produto deve ser identificado para reposição.
  - Não deve ser permitida uma venda em quantidade superior ao estoque disponível.
  - Produtos registrados como vencidos ou danificados não devem ser considerados disponíveis para venda.
  - As movimentações de estoque e as vendas realizadas devem permanecer registradas para consultas posteriores.
- **Restrições organizacionais:**
  - A decisão sobre quais produtos devem ser comprados é realizada pelo responsável pelo estabelecimento.
  - As notas fiscais das compras devem ser armazenadas e relacionadas aos respectivos registros de entrada, quando aplicável.
---

## 5. Dicionário de Dados Conceitual 

O Dicionário de Dados foi desenvolvido em formato de site, apresentando as
entidades, atributos, relacionamentos e regras aplicadas ao modelo.

 [Acessar o Dicionário de Dados](http://127.0.0.1:5500/Dicionario_Mercado_Santana.html)

---

# 6. Modelagem Conceitual (Entidades, Atributos, Relacionamentos)

## 1. Modelo conceitual

Este modelo representa o controle de vendas e estoque do Mercado Santana, organizando as principais informações necessárias para o funcionamento do sistema.

### Entidades reconhecidas

- **Produto:** representa os produtos comercializados pelo mercado e suas informações de estoque.
- **Categoria:** organiza os produtos em grupos, como alimentos, bebidas, limpeza e itens domésticos.
- **Venda:** representa cada venda realizada pelo mercado.
- **Movimentacao_Estoque:** registra as entradas e saídas de produtos, mantendo o histórico das alterações no estoque.

### Atributos e classificações

Cada entidade possui atributos responsáveis por armazenar suas informações. As PKs (chaves primárias) identificam cada registro de forma única, enquanto as FKs (chaves estrangeiras) estabelecem os relacionamentos entre as entidades.

- **Produto:** id_produto, nome, preco_venda, quantidade_estoque, estoque_minimo, status e id_categoria.
- **Categoria:** id_categoria e nome.
- **Venda:** id_venda, data_hora e forma_pagamento.
- **Item_Venda:** id_venda, id_produto, quantidade, preco_unitario e subtotal.
- **Movimentacao_Estoque:** id_movimentacao, id_produto, tipo, quantidade, data_hora e motivo.

### Relacionamentos pertinentes

- **Categoria — Produto (1:N):** uma categoria pode possuir vários produtos, enquanto cada produto pertence a uma categoria.
- **Venda — Item_Venda (1:N):** uma venda pode possuir vários itens, enquanto cada item pertence a uma venda.
- **Produto — Item_Venda (1:N):** um produto pode aparecer em vários itens de venda.
- **Produto — Movimentacao_Estoque (1:N):** um produto pode possuir várias movimentações de estoque.

### Restrições e políticas organizacionais

- O estoque não pode possuir valores negativos.
- A quantidade vendida não pode ser maior que a quantidade disponível.
- Todo produto deve estar associado a uma categoria.
- O estoque mínimo serve como referência para reposição.
- Produtos vencidos ou danificados não podem ser comercializados.
- As movimentações de estoque devem registrar o tipo, quantidade, data e motivo da alteração.
- As vendas e movimentações permanecem registradas para manter o histórico das operações.

---

# 7. Diagrama Entidade-Relacionamento (DER)

O Diagrama Entidade-Relacionamento apresenta a modelagem conceitual do sistema, incluindo as entidades, atributos, relacionamentos e respectivas cardinalidades.

<p align="center">
  <img src="Diagrama Entidade-Relacionamento.png" alt="Diagrama Entidade-Relacionamento" width="900">
</p>
---

# 8. Justificativa Técnica

A modelagem foi definida a partir dos principais processos do Mercado Santana, considerando o controle de produtos, categorias, vendas e movimentações de estoque.

A entidade Produto concentra as informações necessárias para identificar os produtos, controlar seus preços, acompanhar a quantidade disponível, definir o estoque mínimo e registrar sua situação.

A entidade Categoria foi criada para organizar os produtos em grupos, facilitando sua classificação e gerenciamento.

A entidade Venda representa o registro geral de cada venda realizada, enquanto Item_Venda detalha os produtos presentes em cada venda, suas quantidades, preços unitários e subtotais.

A entidade Movimentacao_Estoque permite registrar as alterações realizadas no estoque, mantendo informações sobre tipo, quantidade, data, horário e motivo da movimentação.

Os relacionamentos foram definidos com cardinalidade 1:N para representar que uma categoria pode possuir vários produtos, uma venda pode possuir vários itens, um produto pode aparecer em vários itens de venda e um produto pode possuir várias movimentações de estoque.

Essa estrutura permite organizar os dados de forma separada e relacionada, evitando duplicidade de informações e possibilitando futuras ampliações do sistema.
## 9. Uso de Inteligência Artificial
### Uso 1 —  Caracterização da Organização

| Item | Registro |
|---|---|
| **Ferramenta e etapa** | **Gemini**| Utilizado para analisar as informações obtidas na pesquisa do Mercado Santana e auxiliar na pesquisa sobre modelagem conceitual, justificativa técnica e definição de entidades, atributos e cardinalidades do Diagrama Entidade-Relacionamento (DER).
| **Motivação**|Auxiliar na organização das informações da pesquisa de campo e na identificação dos principais problemas de controle de estoque e vendas do Mercado Santana. A utilização da IA teve como objetivo estruturar a modelagem conceitual, a definição das entidades e a identificação das cardinalidades, buscando uma estrutura organizada e alinhada às práticas profissionais de banco de dados.
| **Prompt(s) utilizados** | “Essas foram as respostas do proprietário, agora deixe o documento mais profissional e com base nas respostas responde o que nos iremos fazer, o que o programa vai precisar para funcionar.” |“Me dê uns exemplos sobre justificativa técnica?”, “Der + justificativa técnica”, “Explique a relação técnica e a separação das entidades produto, item_produto, item_venda e venda”, “Reescreva a justificativa de Entrada removendo a entidade Fornecedor” e “Ajude a estruturar os Requisitos Não Funcionais focando em baixo capacidade de processamento”
| **Resposta recebida** |A IA organizou as respostas de forma profissional, compreendeu a estrutura do diagrama (DER) enviado e auxiliou na identificação das relações entre as entidades Produto, Categoria e Movimentação de Estoque. Além disso, propôs uma estrutura de Documento de Justificativa Técnica (DJT) e sugeriu a divisão dos Requisitos Não Funcionais focando em computadores de baixo processamento.
| **Fontes consultadas e verificadas** |Não foram utilizadas citações de fontes externas diretamente nas respostas da IA. Todas as informações de funcionamento do estabelecimento foram verificadas com base nas respostas fornecidas pelo responsável durante a pesquisa de campo e analisadas pelo grupo com base na documentação do projeto, regras de negócio e conceitos de modelagem de dados.
| **Trechos rejeitados ou corrigidos** |Foram corrigidos, adaptados e rejeitados os trechos e sugestões genéricas que não correspondiam à realidade do estabelecimento. O grupo retirou manualmente todas as referências à entidade Fornecedor e ao relacionamento fornece para atender à solicitação de alteração do escopo do projeto feito pelo professora e focar no baixo processamento do sistema.
| **Justificativa da escolha final** |A modelagem conceitual e o texto final foram definidos considerando estritamente as regras de negócio do Mercado Santana e as orientações fornecidas pela professora. As sugestões da IA foram analisadas pelo grupo e adaptadas conforme os critérios estabelecidos para a atividade, incluindo os ajustes nas entidades, atributos e cardinalidades.
| **Reflexão crítica** | O Gemini foi utilizado como uma ferramenta de apoio para organizar e analisar as informações iniciais, mas o conteúdo final foi revisado, adaptado e definido inteiramente pelo grupo. Ficou evidente que a intervenção humana ativa é indispensável para filtrar respostas genéricas da IA e garantir que o projeto atenda perfeitamente às reais necessidades do Mercado Santana.
### Uso 2 — PROCESSOS DE NEGÓCIOS

| Item | O que registrar |
|------|------------------|
| **Ferramenta e etapa** | ChatGPT – Etapa de revisão e validação dos fluxogramas com base no levantamento de dados do Mercado Santana.. |
| **Motivação** | Verificar a coerência e o alinhamento dos fluxogramas propostos em relação às informações e requisitos coletados no levantamento de dados prévio. |
| **Prompt(s) utilizados** | "Baseado no arquivo enviado de levantamento de dados do Marcado Santana, e verifique se está correto os fluxogramas enviado abaixo". |
| **Resposta recebida** |"Sim. Comparei os dois fluxogramas com o Levantamento de Dados do Mercado Santana que você enviou. No geral, o fluxograma do processo proposto está bem alinhado ao levantamento". |
| **Fontes consultadas e verificadas** | Comparação direta do retorno da IA com o documento de Levantamento de Dados do Mercado Santana e com os diagramas de fluxograma elaborados pelo grupo. |
| **Trechos rejeitados ou corrigidos** |(Ajustar conforme o caso do grupo, por exemplo: "Nenhum trecho descartado; a validação confirmou a estrutura planejada" ou especificar eventuais ajustes feitos nos fluxogramas após o feedback). |
| **Justificativa da escolha final** | A resposta da IA confirmou que a proposta mantinha alinhamento com a documentação de campo, permitindo ao grupo dar sequência e manter o fluxograma validado. |
| **Reflexão crítica** | A IA realizou uma validação geral de alinhamento textual/estrutural, mas coube ao grupo revisar os detalhes operacionais específicos e as particularidades do fluxo do Mercado Santana que não estavam explicitamente mapeadas na análise genérica. |

### Uso 3 — Requisitos e regras de negócio

| Item                                 | Registro                                                                                                                                                                                                                                                                                  |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ferramenta e etapa**               | **ChatGPT** — utilizado na etapa de definição dos requisitos funcionais, não funcionais e das regras de negócio do sistema.                                                                                                                                                               |
| **Motivação**                        | Auxiliar na transformação dos problemas identificados no Mercado Santana em requisitos e regras que representassem o que o sistema deverá realizar.                                                                                                                                       |
| **Prompt(s) utilizados**             | “Com base no levantamento do Mercado Santana, quais seriam os requisitos funcionais, não funcionais e as regras de negócio para o sistema?”                                                                                                                                               |
| **Resposta recebida**                | A IA sugeriu requisitos relacionados ao cadastro de produtos, registro de vendas, controle de entradas e saídas, consulta de estoque, estoque mínimo, reposição e controle de produtos vencidos ou danificados. Também sugeriu regras relacionadas à movimentação do estoque e às vendas. |
| **Fontes consultadas e verificadas** | As sugestões foram verificadas com base no levantamento de dados realizado pelo grupo sobre o funcionamento do Mercado Santana.                                                                                                                                                           |
| **Trechos rejeitados ou corrigidos** | Foram ajustadas ou descartadas sugestões que não estavam diretamente relacionadas aos problemas identificados ou que não faziam parte do escopo definido para o sistema.                                                                                                                  |
| **Justificativa da escolha final**   | Foram mantidos os requisitos e regras que estavam relacionados aos problemas encontrados e que poderiam ser aplicados ao funcionamento proposto para o sistema.                                                                                                                           |
| **Reflexão crítica**                 | O ChatGPT foi utilizado como ferramenta de apoio. As sugestões não foram aceitas automaticamente, sendo analisadas e adaptadas pelo grupo de acordo com os dados da pesquisa e com o escopo do projeto.                                                                                   |


### Uso 4 — Uso de Inteligência Artificial

Durante o desenvolvimento do trabalho, foi utilizado o  **ChatGPT como ferramenta de apoio**, principalmente para tirar dúvidas e ajudar na organização das ideias relacionadas à modelagem do banco de dados.

| Item                                 | Registro                                                                                                                                                                                                                                            |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ferramenta e etapa**               | ChatGPT — utilizado como apoio durante a etapa de modelagem conceitual.                                                                                                                                                                             |
| **Motivação**                        | Utilizamos a ferramenta para esclarecer dúvidas e auxiliar na organização das informações que já haviam sido levantadas pelo grupo.                                                                                                                 |
| **Prompt utilizado**                 | “Pode nos ajudar a organizar as informações do Mercado Santana para identificar possíveis entidades, atributos e relacionamentos para o banco de dados?”                                                                                            |
| **Resposta recebida**                | A IA apresentou sugestões de possíveis entidades, atributos e relacionamentos que poderiam ser considerados na modelagem.                                                                                                                           |
| **Fontes consultadas e verificadas** | As informações sugeridas foram comparadas com os dados e informações levantados pelo próprio grupo sobre o Mercado Santana.                                                                                                                         |
| **Trechos rejeitados ou corrigidos** | Algumas sugestões apresentadas pela IA não correspondiam à realidade do mercado e foram descartadas ou modificadas pelo grupo.                                                                                                                      |
| **Justificativa da escolha final**   | A estrutura final foi definida pelo grupo com base nas informações coletadas e nas necessidades identificadas no Mercado Santana. A IA foi utilizada apenas como apoio.                                                                             |
| **Reflexão crítica**                 | O uso da IA facilitou a organização das ideias e ajudou a esclarecer algumas dúvidas, mas foi necessário analisar as sugestões antes de utilizá-las, pois a ferramenta pode apresentar informações que não correspondem à realidade da organização. |
