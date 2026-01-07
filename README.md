
<img width="448" height="98" alt="imagem_cabecalho_readme" src="https://github.com/user-attachments/assets/5715fdf7-0faf-4862-b271-85c058f69e5c" />
<br/>
<br/>

# Projeto - Dashboard de Vendas – Barraca Brisa Solar
**<ins>Simulação</ins>** de vendas de uma barraca de praia **<ins>fictícia</ins>**, com dashboard em Excel, para fins de treinamento no curso Santander 2025 - Ciência de Dados com Python, ministrado pela [DIO](https://www.dio.me/).

<br/>

## Visão Geral
O objetivo do desafio foi criar um dashboard de vendas em Excel focado na organização e visualização de dados, transformando dados brutos em informações visuais claras. O projeto visa permitir uma análise eficaz do desempenho e a tomada de decisões baseada em dados.

<br/>

## Arquivos Principais do Repositório

- Barraca_Brisa_Praia.xlsx :: arquivo principal do projeto (assets, dados, cálculos e dashboard).

- README.md :: documentação do projeto.

<sub>Observação - as imagens, paleta de cores, base de dados e cálculos encontram-se também no arquivo .xlsx e serão detalhadas em "Estrutura do Workbook".</sub>

<br/>

## Descrição dos Dados Simulados
O Prompt para Perplexity IA **<ins>simular os dados</ins>** encontra-se disponível no [Apêndice](#apêndice---prompt-para-perplexity-ia-simular-os-dados) logo abaixo.

<br/>

## Estrutura do Workbook
- Planilha Assets: logo, paleta de cores, ícones, avatar.
- Planilha Base: tabela de vendas do ano de 2025 (fonte para criação das Tabelas Dinâmicas).
- Planilha Cálculos: Perguntas de negócio, tabelas dinâmicas + medidas (total vendas, quantidade, ticket médio etc.) e prévia dos gráficos.
- Planilha Dashboard: página final em tela cheia com slicers e gráficos.

<br/>

## Visão do Dashboard
- Apresentar os grandes números (Total Vendas, Total Quantidade, Ticket Médio).

- Gráficos
  - Vendas por Mês - gráfico misto de linhas (valor) e colunas (quantidades).
  - Vendas por Produto -  gráfico de barras horizontais representando valor e quantidade.
  - Vendas por Meio de Pagamento - gráfico de pizza 3D, representando os meios de pagamento utilizados pelos clientes.
  

- Filtros
  - Os filtros disponíveis são de Mês Ano Venda, Dia da Semana, Produto e Meio de Pagamento.
  - Eles são independentes a nível de seleção mas "agem conjuntamente" em todo o dashboard (grandes números e gráficos).
  - Cada filtro permite múltiplas escolhas e, da mesma forma, impactam todo o dashboard.

<br/>

# Dashboard - Imagens de Exemplo

- Neste primeiro exemplo, estamos vendo a situação geral das vendas, sem aplicação de qualquer filtro...

<img width="1150" height="1008" alt="Dashboard_Visão_Tela_Cheia_Ex1" src="https://github.com/user-attachments/assets/841e1738-a8e3-468e-9d87-32374c644093" />
<br>
<br>   
- No segundo exemplo, estamos vendo a situação das vendas com filtros aplicados. São eles, vendas dos meses de Janeiro, Fevereiro e Março (jan, fev, mar), ocorridas aos sábados (sab), dos produtos Petiscos / Porções e Sucos / Batidas, pagos com PIX.

<img width="1148" height="1014" alt="Dashboard_Visão_Tela_Cheia_Ex2" src="https://github.com/user-attachments/assets/379a443b-78a7-4743-b281-0e00dda3f8bb" />\

<br/>

## Como Reproduzir / Usar o Projeto
- Requisitos:
  - Microsoft Excel 365 (ou versão equivalente, com Tabelas Dinâmicas e Filtros).

- Passos para utilizar o arquivo depois de aberto no Excel:
  - para sair / retornar no modo tela cheia, pressione Ctrl + Shift + F1.
  - para ter mais controle nas planilhas, clique no menu Exibir e marque conforme sua necessidade "Títulos", "Linhas de Grade", "Ícones de Tipo de Dados" e "Barra de Fórmulas".
  - para reexibir as demais planilhas do Projeto, clique com o botão direito do mouse no nome da planilha Dashboard (barra inferior) -> Reexibir... e marque uma ou mais planilhas desejadas (Assets, Base, Cálculos) e clique em OK.

<br/>

## Agradecimentos

### Felipão e toda equipe da [DIO](https://www.dio.me/)

### [Santander Open Academy](https://www.santanderopenacademy.com/pt_br/index.html)

<br/>

## Créditos
[Perplexity AI](https://www.perplexity.ai/) - da geração dos dados fictícios a discussão de detalhes para aprimorar pontos aprendidos durante o curso com o **Felipão**.

### **Agradeço a todos!** :pray: :sparkling_heart:
<br/>
<hr/>
<br/>

## Apêndice - Prompt para Perplexity IA Simular os Dados

Consegue criar um arquivo .xlsx ou .csv com <ins>dados fictícios</ins> sobre vendas de uma barraca de praia?

Período das vendas:
- 01/01/2025 a 31/12/2025

Quantidade de registros:
- aproximadamente 2.000 registros

Considerar que:
- a barraca de praia não funciona nas segundas-feiras
- simular vários dias sem movimento devido a chuva

Campos desejados:
- data da venda
- estação do ano
- dia da semana (ter, qua, qui, sex, sab, dom)
- impacto (chuva, feriado, véspera de feriado, férias e normal) somente 1 deles, mesmo que seja feriado e férias, por exemplo - então as férias impactam mais... e no caso de chuva impacta mais, mesmo sendo férias.
- produto (bebida alcoólica, refrigerante / água, suco / batida, petisco / porção)
- quantidade
- valor unitário
- valor total
- pagamento (dinheiro, débito, crédito, pix)

Campos da base:
- Data da Venda
- Estação
- Dia da Semana
- Impacto
- Produto
- Quantidade
- Valor Unitário
- Valor Total
- Pagamento
- Mês Ano N
- Mês Ano Venda

[Retornar](#descrição-dos-dados-simulados)
