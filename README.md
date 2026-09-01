# Sistema-de-Estoque-e-Vendas-do-Mercado-Santana

## 1. Caracterização da Organização

- **Nome e natureza da organização:** O Mercado Santana é um estabelecimento comercial do setor varejista, voltado à comercialização de produtos alimentícios e domésticos. A organização foi escolhida por ser um estabelecimento real ao qual o grupo possui acesso para realizar a pesquisa de campo.
- **Contexto e porte:** O Mercado Santana está em funcionamento desde 2013 e possui uma operação de pequeno porte, contando geralmente com 2 pessoas envolvidas nas atividades do estabelecimento. Entre os produtos comercializados estão alimentos, bebidas, produtos de limpeza e itens domésticos.
- **Problemas e necessidades identificados:** Atualmente, o mercado não possui um sistema informatizado para controle de vendas e estoque. A quantidade dos produtos é acompanhada principalmente por observação física das prateleiras, sem registro das entradas e saídas de mercadorias.
 Essa forma de controle já ocasionou situações de falta de produtos e compras em quantidade maior do que a necessária. Além disso, não há um histórico detalhado das vendas, dificultando a identificação dos produtos mais vendidos.
- **Justificativa da escolha:** O Mercado Santana foi escolhido por ser uma organização real e acessível ao grupo, possibilitando a realização de uma pesquisa de campo. Além disso, os problemas identificados no controle de estoque e vendas apresentam uma oportunidade para desenvolver uma solução de banco de dados que possa melhorar a organização das informações e auxiliar no gerenciamento do estabelecimento.
- **Evidências da organização:** As fotos para as evidências da existência da organização e da realização da pesquisa de campo estão disponíveis na pasta [Evidências](./Evidências).

 **Endereço:** [Av. Naylor de Oliveira, 120 - Cidade Tiradentes, São Paulo - SP, 08470-800]
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
*(esta seção e a Seção 4 "Regras de Negócio" DIVIDEM 7,5% na dimensão conceitual — juntas valem 7,5%, não 7,5% cada — + 4% exclusivos desta seção na organização/documentação)*

### 3.1 Requisitos Funcionais
*O que o sistema precisa FAZER (ex.: "o sistema deve permitir registrar uma venda").*

### 3.2 Requisitos Não Funcionais
*Características de qualidade (ex.: desempenho, segurança, usabilidade, disponibilidade).*

---

## 4. Regras de Negócio
*(esta seção DIVIDE com a Seção 3 "Requisitos do Sistema" os mesmos 7,5% da dimensão conceitual — juntas valem 7,5%, não 7,5% cada — + 4% exclusivos desta seção na documentação. "Regras de negócio" é o termo técnico usado em modelagem de dados para as regras de funcionamento de qualquer organização, com ou sem fins lucrativos)*

- **Regras operacionais:** *condições que a organização impõe (ex.: "um pedido só pode ser fechado se houver estoque disponível", "uma doação só pode ser registrada com identificação do doador", "um ritual só pode ser agendado se o espaço estiver disponível").*
- **Restrições organizacionais:** *limitações que afetam o modelo (ex.: políticas internas, prazos, exigências legais, normas religiosas ou estatutárias) — e por que elas importam.*

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

---

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

