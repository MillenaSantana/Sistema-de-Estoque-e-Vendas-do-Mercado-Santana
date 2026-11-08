## Metadados

| Nome completo do aluno | RGM | Usuário do GitHub |
|---|---|---|
| Isabella Bonfim Reis | 48837423 | [@isab7fim](https://github.com/isab7fim) |
| Maria Eduarda Santos Guedes |  48216810 | [@mariaeduardamazuqueli](https://github.com/mariaeduardamazuqueli) |
| Millena Dias Santana | 47555041 | [@MillenaSantana](https://github.com/MillenaSantana) |
| Raquel Guimarães Pereira | 47813369 | [@ raquel-dev70](https://github.com/raquel-dev70) |
| Yasmin Helena Marinho Pinda | 47740981 | [@yasminpinda](https://github.com/yasminpinda) |


## 1. Caracterização da Organização

### 1.1 Nome e natureza da organização

O Mercado Santana é um estabelecimento comercial do setor varejista, voltado à comercialização de produtos alimentícios e domésticos. A organização foi escolhida por ser um estabelecimento real ao qual o grupo possui acesso para realizar a pesquisa de campo.

### 1.2 Contexto e porte

O Mercado Santana está em funcionamento desde 2013 e possui uma operação de pequeno porte, contando com aproximadamente 2 pessoas envolvidas nas atividades do estabelecimento.

Entre os produtos comercializados estão alimentos, bebidas, produtos de limpeza e itens domésticos. O estabelecimento realiza mais de 50 vendas por dia, apresentando uma movimentação frequente de mercadorias e operações comerciais.

### 1.3 Problemas e necessidades identificados

Atualmente, o mercado não possui um sistema informatizado para o controle de vendas e estoque. A quantidade dos produtos é acompanhada principalmente por observação física das prateleiras, sem um registro centralizado das entradas e saídas de mercadorias.

A partir do levantamento realizado, foram identificados os seguintes problemas:

- **P1 – Controle de estoque:** a quantidade dos produtos é acompanhada visualmente, dificultando a identificação precisa dos itens disponíveis e daqueles que precisam ser repostos.
- **P2 – Controle de entradas e saídas:** a ausência de registros organizados dificulta o acompanhamento das mercadorias recebidas e das saídas de produtos do estoque.
- **P3 – Histórico de vendas:** a falta de um histórico detalhado das vendas dificulta a consulta das operações realizadas e a identificação dos produtos mais vendidos.

Essas situações já ocasionaram falta de produtos e compras em quantidades maiores do que as necessárias, demonstrando a necessidade de melhorar a organização das informações do estabelecimento.

### 1.4 Escopo do sistema

O banco de dados proposto busca centralizar as informações relacionadas às operações de estoque e vendas do Mercado Santana.

O escopo contempla oito tabelas: Produtos, Categorias, Fornecedores, Entradas, Itens de Entrada, Vendas, Itens de Venda e Movimentações de Estoque.

Essa estrutura permitirá organizar os dados das mercadorias, registrar as entradas e vendas e acompanhar as movimentações do estoque, fornecendo informações para consultas e apoio à tomada de decisões.

### 1.5 Justificativa da escolha

O Mercado Santana foi escolhido por ser uma organização real e acessível ao grupo, possibilitando a realização de uma pesquisa de campo.

Além disso, um dos integrantes do grupo possui vínculo familiar com o responsável pelo estabelecimento, o que facilitou o acesso ao local e a coleta de informações.

Os problemas identificados no controle de estoque e vendas apresentam uma oportunidade para desenvolver uma solução baseada em banco de dados, capaz de melhorar a organização das informações e auxiliar no gerenciamento do estabelecimento.

### 1.6 Evidências da organização

As fotos utilizadas para comprovar a existência da organização e a realização da pesquisa de campo estão disponíveis na pasta [Evidências](https://github.com/MillenaSantana/Sistema-de-Estoque-e-Vendas-do-Mercado-Santana/tree/main/Evid%C3%AAncias).


 - **Endereço:** [Av. Naylor de Oliveira, 116 - Cidade Tiradentes, São Paulo - SP, 08470-800]
 - **Telefone:** [11 97157-9851]
 - **Google Maps:** [Google Maps — Mercado Santana](https://maps.app.goo.gl/Qb853Zpj6gXqc9pv8)
 - **Responsável:** [Fernando Ribeiro]

---

## 2. Relato da Entrevista

### 2.1 Identificação da entrevista

A entrevista foi realizada com o objetivo de conhecer o funcionamento do Mercado Santana, entender como são realizadas as atividades de compras, vendas e controle de estoque, além de identificar as principais dificuldades do estabelecimento.

- **Entrevistado:** Fernando Ribeiro.
- **Função:** Responsável pelo Mercado Santana.
- **Entrevistadores:** Millena Dias Santana.
- **Data da entrevista:** 27/10/2026.
- **Local:** Mercado Santana — Avenida Naylor de Oliveira, 116, Cidade Tiradentes, São Paulo - SP.

### 2.2 Informações obtidas

Durante a entrevista, foi possível conhecer melhor a rotina do mercado, que envolve o atendimento aos clientes, a venda de produtos, a organização das mercadorias e o fechamento do caixa ao final do dia.

Atualmente, o controle de estoque é realizado principalmente pela observação das prateleiras, sem um sistema informatizado para registrar as quantidades disponíveis e as movimentações dos produtos. Segundo o responsável, essa forma de controle pode ocasionar a falta de mercadorias, o esquecimento de produtos na hora das compras e a aquisição de quantidades maiores do que o necessário.

Também foi identificada a importância de registrar as vendas, acompanhar o histórico de movimentações e definir uma quantidade mínima para cada produto, facilitando a identificação dos itens que precisam ser repostos.

Em relação aos fornecedores, a escolha é feita principalmente pela comparação dos preços oferecidos. Quando as mercadorias chegam ao estabelecimento, são conferidos os produtos, as quantidades e os valores.

Por fim, o responsável destacou o interesse em consultar informações como a quantidade atual dos produtos em estoque, os itens que precisam ser repostos, os produtos mais vendidos, o histórico de vendas e os dados dos fornecedores.

### 2.3 Observações do grupo

Com base nas informações coletadas, o grupo identificou a necessidade de melhorar o controle de estoque e vendas do Mercado Santana. A ausência de registros informatizados dificulta o acompanhamento das mercadorias e pode gerar problemas na reposição dos produtos.

Diante disso, a proposta de desenvolvimento de um banco de dados busca organizar essas informações, registrar as entradas e saídas de produtos e facilitar o acompanhamento das vendas e do estoque.

### 2.4 Levantamento completo

O documento com as perguntas e respostas utilizadas durante a entrevista está disponível em: [Relato completo da entrevista](./levantamento_relato_entrevista.pdf).

# 3. Processos de Negócio

Esta seção descreve o funcionamento atual e a proposta de informatização dos principais processos do Mercado Santana. Em todos os fluxos, o responsável pelo estabelecimento deve conferir as informações e manter os registros das operações para preservar o histórico de vendas, estoque e movimentações financeiras.

**3.1 Processo de Vendas**

O processo inicia quando o cliente escolhe os produtos e se dirige ao caixa. O funcionário confere os itens, calcula o valor total, informa as formas de pagamento disponíveis e recebe o pagamento. No modelo atual, a venda não é registrada imediatamente no sistema; o controle ocorre principalmente no fechamento do caixa ao final do dia. No processo proposto, a venda é registrada no momento da conclusão, os itens são associados à venda, o estoque é atualizado e o comprovante pode ser consultado posteriormente. Se a quantidade solicitada for maior que o saldo disponível, a venda do item deve ser impedida ou ajustada antes da conclusão.

**3.2 Controle de Estoque e Reposição**

O funcionário acompanha a quantidade disponível dos produtos e verifica se algum item está acabando. Quando o saldo permanece acima do estoque mínimo, a rotina continua normalmente. Quando o saldo atinge ou fica abaixo do mínimo, o produto é identificado para reposição, o responsável avalia a necessidade da compra e o processo de compras é iniciado. Com o sistema proposto, as entradas, vendas, perdas e devoluções atualizam o saldo de estoque, permitindo que o alerta de reposição seja gerado automaticamente.

**3.3 Processo de Compras**

O processo começa com a identificação da necessidade de reposição. O responsável define os produtos e as quantidades, escolhe o fornecedor e realiza o pedido. No recebimento, o funcionário confere a quantidade, os produtos, a nota fiscal e as condições da mercadoria. Se houver divergência, o recebimento deve ser ajustado ou questionado ao fornecedor. Se estiver correto, a entrada é registrada, a mercadoria é armazenada e a nota fiscal é guardada junto ao registro da compra.

**3.4 Trocas, Cancelamentos e Devoluções**

O cliente solicita a troca, o cancelamento ou a devolução, e o funcionário localiza a venda por meio da nota ou do comprovante. Em seguida, verifica se a solicitação atende à política do mercado e registra o motivo da operação. Em caso de recusa, o cliente é informado e a justificativa fica registrada. Se a solicitação for aprovada, o fluxo depende do tipo: na troca, separa-se o produto substituto; no cancelamento, a venda é anulada antes da conclusão; na devolução, o produto recebido é conferido. Produto devolvido em condições de venda pode retornar ao estoque; produto vencido, aberto ou danificado deve ser encaminhado ao processo de perdas. Por fim, o pagamento é estornado ou ajustado e o estoque é atualizado.

**3.5 Cadastro e Escolha de Fornecedores**

Quando surge uma necessidade de compra, o responsável consulta os fornecedores disponíveis. Se o fornecedor ainda não existir no sistema, são cadastrados a razão social, o CNPJ, os contatos e as condições comerciais. Em seguida, são comparados preço, prazo de entrega, qualidade dos produtos e condições de pagamento. O fornecedor aprovado é registrado como escolhido e vinculado ao pedido de compra. Caso nenhum fornecedor seja aprovado, o responsável busca outra opção e repete a cotação antes de emitir o pedido.

**3.6 Pagamento a Fornecedores**

Após o recebimento da mercadoria, o funcionário confere o pedido, a quantidade, a nota fiscal e os valores. Se houver inconsistência, o pagamento é bloqueado e a correção é solicitada ao fornecedor. Se os dados estiverem corretos, é registrada a conta a pagar com o valor e o vencimento. Na data prevista, o responsável verifica a autorização e a disponibilidade financeira, realiza o pagamento, armazena o comprovante e baixa a conta. Quando o pagamento não puder ser realizado, a justificativa e a nova programação devem ser registradas.

**3.7 Cadastro de Produtos e Precificação**

Antes de vender um item, o responsável verifica se o produto já está cadastrado. Para um novo produto, registra nome, categoria, unidade de medida e estoque mínimo. Para um produto existente, confere e atualiza os dados necessários. Depois, informa o custo de compra, define a margem e calcula o preço sugerido. O preço deve ser revisado e aprovado pelo responsável; somente após essa aprovação o produto é ativado e disponibilizado para vendas e controle de estoque.

**3.8 Tratamento de Perdas por Vencimento ou Danos**

Quando um produto vencido ou danificado é identificado, o funcionário o separa e o retira da área de venda para impedir sua comercialização. O motivo da perda é classificado como vencimento ou dano, e são registrados o produto, a quantidade, a data e a justificativa. Se houver possibilidade de devolução, o responsável solicita a devolução ao fornecedor e guarda o comprovante; caso contrário, o item é descartado de forma adequada. Ao final, o sistema registra a saída por perda, atualiza o estoque e mantém o histórico para acompanhamento do responsável.

**3.9 Fechamento de Caixa**

Ao encerrar o expediente, o funcionário interrompe novas vendas e consulta as vendas registradas e as respectivas formas de pagamento. Em seguida, conta o dinheiro e confere os comprovantes de cartões e pagamentos via Pix. Os valores são comparados com o total apresentado pelo sistema. Se houver diferença, as vendas, os comprovantes e a contagem são revisados; persistindo a divergência, o valor e a justificativa são registrados. Se os valores estiverem corretos, o fechamento é confirmado. Em ambos os casos, o relatório e o registro do caixa são armazenados para consulta posterior.

**3.10 Processo Proposto Integrado**

O processo proposto integra cadastro de produtos, vendas, estoque, compras, fornecedores, pagamentos, perdas e fechamento de caixa por meio de software. O produto é cadastrado e precificado antes de ser disponibilizado para venda. A cada venda, troca, devolução, entrada ou perda, o sistema registra a movimentação correspondente e atualiza o saldo em tempo real. Quando o estoque atinge o mínimo, o sistema sinaliza a reposição; o responsável consulta e escolhe um fornecedor, emite o pedido, registra o recebimento e controla o pagamento. Ao final do dia, o fechamento de caixa consolida as vendas e registra eventuais divergências.

- **Fluxogramas** representados visualmente na pasta [Fluxograma](./Fluxograma).

---
# 4. Requisitos do Sistema

Os requisitos do sistema foram definidos com base nos problemas identificados durante a pesquisa de campo no Mercado Santana, considerando as necessidades apresentadas pelo responsável pelo estabelecimento.

A proposta busca organizar as informações dos produtos, controlar as entradas e saídas de mercadorias, registrar as vendas e facilitar o acompanhamento do estoque.

## 4.1 Requisitos Funcionais

- **RF01 — Cadastro de produtos:** o sistema deve permitir cadastrar, consultar e atualizar os produtos comercializados pelo mercado, armazenando suas informações de identificação, categoria, preço de venda e estoque mínimo.

- **RF02 — Cadastro de categorias:** o sistema deve permitir cadastrar e consultar categorias para organizar e classificar os produtos comercializados.

- **RF03 — Cadastro de fornecedores:** o sistema deve permitir cadastrar, consultar e atualizar os dados dos fornecedores responsáveis pelo fornecimento das mercadorias.

- **RF04 — Registro de entradas:** o sistema deve permitir registrar o recebimento de mercadorias, armazenando a data da entrada, o número da nota fiscal, o fornecedor e os produtos recebidos com suas respectivas quantidades.

- **RF05 — Atualização do estoque por entradas:** o sistema deve atualizar a quantidade disponível dos produtos após o registro de uma entrada de mercadorias.

- **RF06 — Registro de vendas:** o sistema deve permitir registrar as vendas realizadas, armazenando a data, o horário, o valor total e a forma de pagamento utilizada.

- **RF07 — Detalhamento das vendas:** o sistema deve permitir registrar os produtos presentes em cada venda, incluindo suas respectivas quantidades, preços unitários e subtotais.

- **RF08 — Atualização do estoque por vendas:** o sistema deve subtrair automaticamente do estoque as quantidades dos produtos comercializados após a confirmação de uma venda.

- **RF09 — Consulta de estoque:** o sistema deve permitir consultar a quantidade disponível de cada produto cadastrado.

- **RF10 — Controle de estoque mínimo:** o sistema deve permitir definir uma quantidade mínima para cada produto e identificar aqueles cujo estoque esteja igual ou abaixo desse limite.

- **RF11 — Identificação de produtos para reposição:** o sistema deve permitir consultar os produtos que atingiram o estoque mínimo, facilitando a identificação das necessidades de compra.

- **RF12 — Registro de movimentações de estoque:** o sistema deve registrar as movimentações realizadas nos produtos, incluindo entradas, saídas e perdas, armazenando o tipo, a quantidade, a data e o motivo da movimentação.

- **RF13 — Controle de produtos não comercializáveis:** o sistema deve permitir registrar produtos vencidos ou danificados, identificando-os como indisponíveis para venda e registrando suas respectivas saídas por perda.

- **RF14 — Histórico de vendas:** o sistema deve armazenar os registros das vendas realizadas, permitindo consultar operações anteriores e identificar os produtos mais vendidos.

## 4.2 Requisitos Não Funcionais

- **RNF01 — Usabilidade:** o sistema deve apresentar uma interface simples, intuitiva e organizada, permitindo que os responsáveis pelo estabelecimento realizem as operações sem conhecimentos técnicos avançados.

- **RNF02 — Segurança:** o sistema deve restringir o acesso às funcionalidades e informações a usuários autorizados, evitando alterações ou consultas indevidas.

- **RNF03 — Integridade dos dados:** o sistema deve garantir a consistência das informações armazenadas, impedindo registros inválidos, duplicidade de identificações e quantidades negativas no estoque.

- **RNF04 — Confiabilidade:** o sistema deve preservar os registros de vendas, entradas e movimentações de estoque, permitindo consultas posteriores sem perda do histórico das operações.

- **RNF05 — Desempenho:** o sistema deve permitir a realização de consultas e registros de operações cotidianas sem exigir equipamentos de alto desempenho, considerando a estrutura de pequeno porte do estabelecimento.

- **RNF06 — Manutenibilidade:** o sistema deve possuir uma estrutura organizada, permitindo futuras correções, atualizações e inclusão de funcionalidades sem comprometer os dados já armazenados.

---

# 5. Regras de Negócio

As regras de negócio estabelecem as condições que devem ser respeitadas durante a utilização do sistema, garantindo que as operações de vendas, compras e controle de estoque estejam de acordo com o funcionamento do Mercado Santana.

## 5.1 Regras Operacionais

- **RN01 — Identificação de produtos:** cada produto deve possuir uma identificação única no sistema.

- **RN02 — Associação de categorias:** cada produto deve estar associado a uma única categoria cadastrada.

- **RN03 — Controle de estoque:** a quantidade disponível de um produto não pode ser inferior a zero.

- **RN04 — Saída por venda:** toda venda confirmada deve gerar a baixa das quantidades correspondentes no estoque.

- **RN05 — Entrada de mercadorias:** toda entrada de mercadorias registrada deve acrescentar as quantidades recebidas ao estoque dos respectivos produtos.

- **RN06 — Disponibilidade para venda:** não deve ser permitida a venda de produtos em quantidade superior à disponível em estoque.

- **RN07 — Estoque mínimo:** cada produto pode possuir uma quantidade mínima definida pelo responsável pelo estabelecimento.

- **RN08 — Reposição de mercadorias:** quando a quantidade disponível de um produto atingir ou ficar abaixo do estoque mínimo, ele deve ser identificado para reposição.

- **RN09 — Registro de movimentações:** toda movimentação de estoque deve possuir identificação do produto, tipo de operação, quantidade, data e motivo.

- **RN10 — Controle de perdas:** produtos vencidos ou danificados devem ser retirados da disponibilidade de venda e registrados como perdas quando não puderem retornar ao estoque comercializável.

- **RN11 — Histórico de operações:** as vendas, entradas e movimentações de estoque devem permanecer registradas para possibilitar consultas posteriores.

- **RN12 — Registro de entradas:** toda entrada de mercadorias deve possuir informações sobre a data de recebimento e, quando aplicável, o número da nota fiscal correspondente.

- **RN13 — Detalhamento das vendas:** cada venda deve possuir pelo menos um produto associado, com sua respectiva quantidade e valor.

## 5.2 Restrições Organizacionais

- A decisão sobre quais produtos devem ser comprados é de responsabilidade do responsável pelo estabelecimento.

- A escolha dos fornecedores deve considerar fatores como preço, qualidade dos produtos e condições de entrega.

- As mercadorias recebidas devem ser conferidas antes de serem registradas como entradas no estoque.

- As notas fiscais das compras devem ser armazenadas e relacionadas aos respectivos registros de entrada, quando aplicável.

- Produtos vencidos, danificados ou impróprios para comercialização não podem permanecer disponíveis para venda.

---

# 6. Relação entre Problemas, Requisitos e Regras de Negócio

Para garantir que o sistema proposto atenda às necessidades identificadas durante a pesquisa de campo, foi estabelecida uma relação entre os problemas encontrados no Mercado Santana, os requisitos definidos e as regras de negócio correspondentes.

| Problema identificado | Requisitos relacionados | Regras de negócio relacionadas |
|---|---|---|
| **P1 — Controle de estoque:** a quantidade dos produtos é acompanhada visualmente, dificultando a identificação dos itens disponíveis e daqueles que precisam ser repostos. | RF01, RF02, RF09, RF10 e RF11. | RN01, RN02, RN03, RN07 e RN08. |
| **P2 — Controle de entradas e saídas:** a ausência de registros organizados dificulta o acompanhamento das mercadorias recebidas e das saídas de produtos do estoque. | RF04, RF05, RF06, RF07, RF08, RF12 e RF13. | RN03, RN04, RN05, RN06, RN09, RN10 e RN12. |
| **P3 — Histórico de vendas:** a falta de um histórico detalhado dificulta a consulta das operações realizadas e a identificação dos produtos mais vendidos. | RF06, RF07 e RF14. | RN09, RN11 e RN13. |

## 6.1 Atendimento às Necessidades Identificadas

A partir da relação apresentada, é possível observar como os requisitos e as regras de negócio contribuem para solucionar os problemas encontrados:

- **P1 — Controle de estoque:** os requisitos de consulta, cadastro e controle de estoque mínimo permitem acompanhar as quantidades disponíveis e identificar produtos que precisam de reposição, reduzindo a dependência da observação física das prateleiras.

- **P2 — Controle de entradas e saídas:** os registros de entradas, vendas, perdas e movimentações permitem acompanhar as alterações realizadas no estoque, mantendo as quantidades atualizadas e o histórico das operações.

- **P3 — Histórico de vendas:** o registro das vendas e de seus respectivos produtos permite consultar operações anteriores, acompanhar a comercialização das mercadorias e identificar os produtos mais vendidos.

Dessa forma, os requisitos funcionais, não funcionais e as regras de negócio foram estruturados para atender às necessidades identificadas na pesquisa de campo, mantendo a proposta de informatização alinhada à realidade operacional do Mercado Santana.
---

## 5. Dicionário de Dados Conceitual  

O Dicionário de Dados foi desenvolvido em formato de site, apresentando as
entidades, atributos, relacionamentos e regras aplicadas ao modelo.

[Acessar o Dicionário de Dados](https://millenasantana.github.io/Sistema-de-Estoque-e-Vendas-do-Mercado-Santana/dicionario.html).

---

## 6. Modelagem Conceitual (Entidades, Atributos e Relacionamentos)
6.1 Modelo conceitual


O modelo conceitual representa o controle de vendas e estoque do Mercado Santana, organizando as principais informações necessárias para o cadastro de produtos, categorias, entradas de mercadorias, vendas e movimentações de estoque.

Entidades reconhecidas
Produto: representa os produtos comercializados pelo mercado, contendo informações relacionadas à identificação, nome e preço de venda.

Categoria: representa os grupos aos quais os produtos pertencem, permitindo organizar os produtos em categorias como alimentos, bebidas, produtos de limpeza e itens domésticos.

Entrada: representa o registro de entrada de mercadorias no estoque, contendo informações como data da entrada, número da nota fiscal e valor total.

Venda: representa cada venda realizada pelo mercado, registrando a data e hora, o valor total e a forma de pagamento utilizada.

Movimentacao_Estoque: registra as alterações realizadas no estoque, permitindo controlar entradas, saídas e outros tipos de movimentação, juntamente com suas respectivas quantidades, datas e motivos.

6.2 Atributos e classificações

Cada entidade possui atributos responsáveis por armazenar suas informações. As PKs (chaves primárias) identificam cada registro de forma única. Os relacionamentos entre as entidades representam as associações existentes entre os dados do sistema.

Produto
id_produto — chave primária;

nome — nome do produto;

preco_venda — preço de venda do produto.

Categoria
id_categoria — chave primária;

nome — nome da categoria.

Entrada
id_entrada — chave primária;

data_entrada — data em que a mercadoria foi recebida;

numero_nota_fiscal — número da nota fiscal relacionada à entrada;

valor_total — valor total da entrada.

Venda
id_venda — chave primária;

data_hora — data e horário em que a venda foi realizada;

valor_total — valor total da venda;

forma_pagamento — forma de pagamento utilizada.

Movimentacao_Estoque
id_movimentacao — chave primária;

tipo — identifica o tipo de movimentação realizada;

quantidade — quantidade movimentada;

data_hora — data e horário da movimentação;

motivo — motivo da movimentação.

6.3 Relacionamentos pertinentes

Categoria — Produto: 1:N
O relacionamento “possui” estabelece que uma Categoria pode possuir vários Produtos, enquanto cada Produto pertence a uma única Categoria.

Entrada — Produto: N:N
O relacionamento “contém” estabelece que uma Entrada pode conter vários Produtos, e um Produto pode estar presente em várias Entradas.

Esse relacionamento permite representar que diferentes compras ou recebimentos podem conter os mesmos produtos em momentos diferentes.

Venda — Produto: N:N
O relacionamento “contém” estabelece que uma Venda pode conter vários Produtos, enquanto um Produto pode participar de várias Vendas.

Esse relacionamento representa a comercialização dos produtos pelo mercado.

Produto — Movimentacao_Estoque: 1:N
O relacionamento “registra” estabelece que um Produto pode possuir várias Movimentações de Estoque, enquanto cada movimentação está relacionada a um único produto.

Dessa forma, é possível manter o histórico das alterações realizadas no estoque de cada produto.

6.4 Restrições e políticas organizacionais

Cada produto deve estar associado a uma única categoria.

Uma categoria pode possuir vários produtos.

Uma entrada pode conter vários produtos.

Um produto pode aparecer em várias entradas.

Uma venda pode conter vários produtos.

Um produto pode aparecer em várias vendas.

Cada movimentação de estoque deve estar associada a um produto.

Um produto pode possuir várias movimentações de estoque.

A quantidade movimentada deve ser maior que zero.

As movimentações de estoque devem registrar o tipo, a quantidade, a data e o motivo da alteração.

As entradas devem registrar a data, o número da nota fiscal e o valor total.

As vendas devem registrar a data e hora, o valor total e a forma de pagamento.

As vendas e movimentações de estoque devem permanecer registradas para manter o histórico das operações.
---

# 7. Diagrama Entidade-Relacionamento (DER)

O Diagrama Entidade-Relacionamento (DER) foi elaborado com base nas informações coletadas durante a pesquisa de campo no Mercado Santana. Seu objetivo é representar conceitualmente os dados necessários para o desenvolvimento do banco de dados, apresentando as entidades, seus atributos e os relacionamentos entre elas.

O modelo contempla oito entidades principais: Categoria, Produto, Fornecedor, Entrada, Item_Entrada, Venda, Item_Venda e Movimentacao_Estoque.

3.2 Arquivo do modelo conceitual

O diagrama completo está disponível em: [Visualizar Modelo Conceitual](Modelo_Conceitual.pdf).

3.3 Ferramenta utilizada

O modelo conceitual foi desenvolvido utilizando o software brModelo.

# 8. Justificativa Técnica

A modelagem foi definida a partir dos principais processos do Mercado Santana, considerando o controle de produtos, categorias, vendas e movimentações de estoque.

A entidade Produto concentra as informações necessárias para identificar os produtos, controlar seus preços, acompanhar a quantidade disponível, definir o estoque mínimo e registrar sua situação.

A entidade Categoria foi criada para organizar os produtos em grupos, facilitando sua classificação e gerenciamento.

A entidade Venda representa o registro geral de cada venda realizada, enquanto detalha os produtos presentes em cada venda, suas quantidades, preços unitários e subtotais.

A entidade Movimentacao_Estoque permite registrar as alterações realizadas no estoque, mantendo informações sobre tipo, quantidade, data, horário e motivo da movimentação.

Os relacionamentos foram definidos com cardinalidade 1:N para representar que uma categoria pode possuir vários produtos, uma venda pode possuir vários itens, um produto pode aparecer em vários itens de venda e um produto pode possuir várias movimentações de estoque.

Essa estrutura permite organizar os dados de forma separada e relacionada, evitando duplicidade de informações e possibilitando futuras ampliações do sistema.
## 9. Uso de Inteligência Artificial
### Uso 1 —  Caracterização da Organização

| Item | Registro |
|---|---|
| **Ferramenta e etapa** | **Gemini** — utilizado na etapa de organização e análise das informações obtidas na pesquisa de campo realizada com o responsável pelo Mercado Santana. |
|  **Motivação** | Auxiliar na organização das respostas da entrevista e na identificação dos principais problemas relacionados ao controle de estoque e às vendas. 
| **Prompt(s) utilizados** | “Essas foram as respostas do proprietário, agora deixe o documento mais profissional e com base nas respostas responde o que iremos fazer, o que o programa vai precisar para funcionar.” |
| **Resposta recebida** | A IA organizou as respostas de forma mais profissional e objetiva, identificou a falta de um sistema de controle de estoque e vendas como principal problema e sugeriu funcionalidades para o sistema. |
| **Fontes consultadas e verificadas** | As informações sobre o funcionamento do estabelecimento foram verificadas com base nas respostas fornecidas pelo responsável durante a pesquisa de campo. |
| **Trechos rejeitados ou corrigidos** | Sugestões que não correspondiam à realidade do estabelecimento foram ajustadas ou desconsideradas pelo grupo. |
| **Justificativa da escolha final** | Foram mantidas as informações que correspondiam aos dados obtidos diretamente na pesquisa de campo. |
| **Reflexão crítica** | O Gemini foi utilizado como ferramenta de apoio para organizar e interpretar as informações, mas as decisões foram baseadas nos dados reais fornecidos pelo responsável pelo estabelecimento. |

### Uso 2 — Processo de Negócio

| Item | O que registrar |
|------|------------------|
| **Ferramenta e etapa** | **ChatGPT** – Etapa de revisão e validação dos fluxogramas com base no levantamento de dados do Mercado Santana. |
| **Motivação** | Verificar a coerência e o alinhamento dos fluxogramas propostos em relação às informações e requisitos coletados no levantamento de dados prévio. |
| **Prompt(s) utilizados** | "Baseado no arquivo enviado de levantamento de dados do Marcado Santana, e verifique se está correto os fluxogramas enviado abaixo". |
| **Resposta recebida** |"Sim. Comparei os dois fluxogramas com o Levantamento de Dados do Mercado Santana que você enviou. No geral, o fluxograma do processo proposto está bem alinhado ao levantamento". |
| **Fontes consultadas e verificadas** | Comparação direta do retorno da IA com o documento de Levantamento de Dados do Mercado Santana e com os diagramas de fluxograma elaborados pelo grupo. |
| **Trechos rejeitados ou corrigidos** | Nenhum trecho descartado; a validação confirmou a estrutura planejada |
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


### Uso 4 — Modelagem Conceitual

Durante o desenvolvimento do trabalho, foi utilizado o  **ChatGPT como ferramenta de apoio**, principalmente para tirar dúvidas e ajudar na organização das ideias relacionadas à modelagem do banco de dados.

| Item                                 | Registro                                                                                                                                                                                                                                            |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ferramenta e etapa**               | **ChatGPT** — utilizado como apoio durante a etapa de modelagem conceitual.                                                                                                                                                                             |
| **Motivação**                        | Utilizamos a ferramenta para esclarecer dúvidas e auxiliar na organização das informações que já haviam sido levantadas pelo grupo.                                                                                                                 |
| **Prompt utilizado**                 | “Pode nos ajudar a organizar as informações do Mercado Santana para identificar possíveis entidades, atributos e relacionamentos para o banco de dados?”                                                                                            |
| **Resposta recebida**                | A IA apresentou sugestões de possíveis entidades, atributos e relacionamentos que poderiam ser considerados na modelagem.                                                                                                                           |
| **Fontes consultadas e verificadas** | As informações sugeridas foram comparadas com os dados e informações levantados pelo próprio grupo sobre o Mercado Santana.                                                                                                                         |
| **Trechos rejeitados ou corrigidos** | Algumas sugestões apresentadas pela IA não correspondiam à realidade do mercado e foram descartadas ou modificadas pelo grupo.                                                                                                                      |
| **Justificativa da escolha final**   | A estrutura final foi definida pelo grupo com base nas informações coletadas e nas necessidades identificadas no Mercado Santana. A IA foi utilizada apenas como apoio.                                                                             |
| **Reflexão crítica**                 | O uso da IA facilitou a organização das ideias e ajudou a esclarecer algumas dúvidas, mas foi necessário analisar as sugestões antes de utilizá-las, pois a ferramenta pode apresentar informações que não correspondem à realidade da organização. |

### Uso 05 — DER + Justificativa Técnica

| Item | O que registrar |
|------|------------------|
| **Ferramenta e etapa**|**Gemini** — Utilizado para auxiliar na compreensão do Diagrama Entidade-Relacionamento (DER), das entidades, dos atributos e das cardinalidades, contribuindo para a organização e estruturação do sistema do Mercado Santana.|
| **Motivação** |A IA foi utilizada para auxiliar na compreensão das cardinalidades e na organização das entidades do sistema, considerando os setores e processos identificados no Mercado Santana. O recurso também ajudou na interpretação do modelo do DER e na comparação com os conteúdos apresentados pelo professor.|
| **Prompt(s) utilizados** |“Me dê uns exemplos sobre justificativa técnica?”, “Der + justificativa técnica”, “Explique a relação técnica e a separação das entidades produto, item_produto, item_venda e venda”, “Reescreva a justificativa de Entrada removendo a entidade Fornecedor” e “Ajude a estruturar os Requisitos Não Funcionais focando em baixo capacidade de processamento” |
| **Resposta recebida** |A IA organizou as respostas de forma profissional, compreendeu a estrutura do diagrama (DER) enviado e auxiliou na identificação das relações entre as entidades Produto, Categoria e Movimentação de Estoque. Além disso, propôs uma estrutura de Documento de Justificativa Técnica (DJT) e sugeriu a divisão dos Requisitos Não Funcionais focando em computadores de baixo processamento.|
| **Fontes consultadas e verificadas** |As informações sugeridas pela IA foram comparadas com os materiais disponibilizados pelo professor e com as informações levantadas sobre o Mercado Santana. As sugestões da IA não foram utilizadas como fonte única para a definição do modelo.|
| **Trechos rejeitados ou corrigidos** |Algumas sugestões apresentadas pela IA foram rejeitadas ou corrigidas manualmente por não corresponderem à realidade do Mercado Santana ou aos critérios definidos pelo professor.|
| **Justificativa da escolha final** |A equipe priorizou as orientações apresentadas pelo professor e as informações obtidas sobre o Mercado Santana. Com isso, algumas sugestões da IA foram adaptadas ou removidas, incluindo elementos relacionados a Fornecedor, Item_Entrada e algumas estruturas de Item_Venda, para manter o modelo de acordo com a realidade da organização e com os requisitos definidos para o projeto.|
| **Reflexão crítica** |A IA foi útil como ferramenta de apoio, principalmente para compreender conceitos de modelagem e organizar ideias. Entretanto, suas respostas apresentaram generalizações que não correspondiam totalmente à realidade do Mercado Santana. Por isso, foi necessário analisar, corrigir e adaptar as sugestões com base nas informações da organização e nas orientações do professor.|
