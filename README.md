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
*(vale 10% — Dimensão Procedimental)*

- **Principais processos mapeados:** *ex.: cadastro de clientes/beneficiários/fiéis, controle de estoque ou doações, vendas ou arrecadação, emissão de pedidos ou solicitações, entregas ou distribuição, organização de eventos/rituais/mutirões.*
- **Fluxogramas:** *represente visualmente pelo menos os processos-chave (imagens anexadas). Deve ficar claro o fluxo de cada processo e como eles se integram entre si.*

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

## 5. Dicionário de Dados Conceitual (Preliminar)
*(vale 10% — Dimensão Procedimental)*

Para cada entidade identificada, liste:

| Atributo | Descrição | Regra de negócio associada |
|----------|-----------|------------------------------|
| *nome do atributo* | *o que ele representa* | *se houver alguma regra (obrigatoriedade, valores possíveis, etc.)* |

*Mantenha o dicionário organizado e padronizado (mesmo formato de tabela para todas as entidades).*

**Atenção à privacidade:** se forem usados exemplos de valores para ilustrar os atributos, esses exemplos devem ser **fictícios** — não utilize dados reais de clientes, fiéis, beneficiários, doadores ou funcionários da organização (nomes, CPFs, contatos etc.), mesmo que tenham sido observados durante a pesquisa de campo. Os exemplos devem apenas ser **coerentes com as operações reais** observadas.

---

## 6. Modelagem Conceitual (Entidades, Atributos, Relacionamentos)
*(vale 7,5% na dimensão conceitual)*

- **Entidades reconhecidas:** *liste e justifique brevemente cada uma.*
- **Atributos e classificações:** *quais atributos pertencem a cada entidade.*
- **Relacionamentos pertinentes:** *como as entidades se conectam.*
- **Restrições e políticas organizacionais aplicadas ao modelo.**

---

## 7. Diagrama Entidade-Relacionamento (DER)
*(vale 20% — é o item de maior peso da entrega)*

- Anexe o DER (em imagem).
- O diagrama deve representar corretamente:
  - Entidades
  - Atributos
  - Relacionamentos
  - **Cardinalidades**
- O modelo deve ser **consistente** e já demonstrar potencial de **escalabilidade e integração** (pensando nas próximas etapas do projeto).

---

## 8. Justificativa Técnica
*(vale 7,5% — sozinho, é o subcritério de maior peso dentro da Dimensão Conceitual)*

*Explique e defenda as decisões de abstração e modelagem tomadas: por que essas entidades, esses atributos, esses relacionamentos e essas cardinalidades — e não outras alternativas possíveis?*

---

## 9. Uso de Inteligência Artificial
### Uso 1 — Pesquisa e organização da organização

| Item | Registro |
|---|---|
| **Ferramenta e etapa** | **ChatGPT** — utilizamos na etapa de organização e análise das informações obtidas na pesquisa de campo realizada com o responsável pelo Mercado Santana. |
| **Motivação** | Auxiliar na organização das respostas da entrevista e na identificação dos principais problemas relacionados a falta de controle de estoque e de vendas. |
| **Prompt(s) utilizados** | “Essas foram as respostas do proprietário, agora deixe o documento mais profissional e com base nas respostas responde o que nos iremos fazer, o que o programa vai precisar para funcionar.” |
| **Resposta recebida** | A IA organizou as respostas de forma mais profissional e objetiva, identificou a falta de um sistema de controle de estoque e vendas como principal problema e sugeriu funcionalidades para o sistema. |
| **Fontes consultadas e verificadas** | As informações sobre o funcionamento do estabelecimento foram verificadas com base nas respostas fornecidas pelo responsável durante a pesquisa de campo. |
| **Trechos rejeitados ou corrigidos** | Sugestões que não correspondiam à realidade do estabelecimento foram ajustadas ou desconsideradas pelo grupo. |
| **Justificativa da escolha final** | Foram mantidas as informações que correspondiam aos dados obtidos diretamente na pesquisa de campo. |
| **Reflexão crítica** | O ChatGPT foi utilizado como ferramenta de apoio para organizar e interpretar as informações, mas as decisões foram baseadas nos dados reais fornecidos pelo responsável pelo estabelecimento. |

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


## Critérios Atitudinais (20%)
**Estes critérios NÃO constam explicitamente como item de entrega no README.** Eles são avaliados por meio de **Avaliação 360º entre os integrantes do grupo** (cada membro avalia os colegas de equipe) e, no caso da Colaboração, também pela **colaboração equilibrada no histórico de commits** do repositório GitHub — não pela leitura do restante do repositório nem pela apresentação:

- **Participação (5%):** envolvimento nas discussões técnicas e nas decisões do grupo.
- **Comprometimento (5%):** cumprimento de prazos e responsabilidades assumidas.
- **Colaboração (5%):** respeito às contribuições dos colegas, cooperação na construção do projeto e colaboração equilibrada no histórico de commits do repositório GitHub.
- **Autonomia (5%):** busca independente de soluções e proposta de melhorias.

---

## Resumo dos Pesos

| Dimensão | Peso total |
|----------|-----------|
| Conceitual (contexto, requisitos/regras, modelagem, justificativa técnica) | 30% |
| Procedimental (requisitos, fluxogramas, dicionário de dados, DER) | 50% |
| Atitudinal (participação, comprometimento, colaboração, autonomia) | 20% |

