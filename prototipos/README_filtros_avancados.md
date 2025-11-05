# Painel de Monitoramento: Filtros Avançados e Quebra de Barras

## Visão Geral

Esta documentação descreve a nova funcionalidade de **filtros avançados** e **quebra de barras** implementada no painel de monitoramento de multiagentes PEERS Consulting. Agora, além de selecionar variáveis para os eixos dos gráficos, você pode filtrar e segmentar visualizações por diferentes categorias, tornando a análise muito mais flexível e poderosa.

---

## Descrição da Funcionalidade

- **Filtro Avançado:** Permite selecionar valores específicos de variáveis categóricas (ex: filtrar apenas um projeto ou usuário).
- **Quebra de Barras (Segmentação):** Permite dividir as barras do gráfico por uma segunda variável categórica, visualizando a distribuição interna (ex: barras por dia, segmentadas por usuário).

Essas opções tornam possível responder perguntas como:
- "Como está o uso diário apenas do projeto X?"
- "Dentro do projeto Y, como os diferentes usuários estão consumindo tokens ao longo dos dias?"
- "Quero ver o total por modelo, mas só para um usuário específico."

---

## Como Usar os Novos Controles

### 1. Filtro por Categoria

No topo do painel, novos campos de filtro permitem selecionar valores específicos para variáveis categóricas como **Projeto**, **Usuário**, **Modelo** ou **Job**.

- **Exemplo:** Para analisar apenas o projeto "Alpha", selecione "Alpha" no filtro de Projeto. Os gráficos e a tabela exibirão apenas dados desse projeto.

### 2. Quebra de Barras (Segmentação)

Nos controles do gráfico de barras, há uma nova opção chamada **"Quebrar barra por"** ou **"Segmentar por"**.

- **Como funciona:**
  - Escolha o eixo X normalmente (ex: "Dia").
  - No campo "Quebrar barra por", selecione uma variável categórica (ex: "Usuário").
  - O gráfico mostrará barras agrupadas por dia, mas cada barra será segmentada por usuário (cada cor representa um usuário diferente).

---

## Exemplos de Casos de Uso

### Caso 1: Filtrar por Projeto e Quebrar por Usuário

- **Objetivo:** Ver o consumo diário de tokens do projeto "Beta", detalhado por usuário.
- **Passos:**
  1. No filtro "Projeto", selecione "Beta".
  2. No gráfico de barras, defina eixo X como "Dia".
  3. Em "Quebrar barra por", selecione "Usuário".
  4. O gráfico exibirá, para cada dia, barras segmentadas por usuário do projeto "Beta".

### Caso 2: Filtrar por Usuário e Quebrar por Modelo

- **Objetivo:** Analisar como o usuário "joao@empresa.com" utiliza diferentes modelos.
- **Passos:**
  1. No filtro "Usuário", selecione "joao@empresa.com".
  2. No gráfico de barras, defina eixo X como "Modelo".
  3. Em "Quebrar barra por", selecione "Projeto" (opcional).
  4. O gráfico mostra o consumo por modelo, segmentado por projeto.

### Caso 3: Nenhum Filtro, Quebra por Projeto

- **Objetivo:** Visualizar o total diário de todos os projetos, com barras segmentadas por projeto.
- **Passos:**
  1. Não selecione nenhum filtro.
  2. Eixo X: "Dia".
  3. "Quebrar barra por": "Projeto".

---

## Ilustrações

> **Nota:** Substitua os exemplos abaixo por screenshots reais do painel após deploy.

### Exemplo 1: Filtro por Projeto + Quebra por Usuário

![Exemplo de gráfico de barras com filtro de projeto e quebra por usuário](./exemplo_filtro_projeto_quebra_usuario.png)

### Exemplo 2: Filtro por Usuário + Quebra por Modelo

![Exemplo de gráfico de barras com filtro de usuário e quebra por modelo](./exemplo_filtro_usuario_quebra_modelo.png)

---

## Observações

- Os filtros e quebras podem ser combinados livremente, dependendo dos dados disponíveis.
- As opções de filtro são populadas dinamicamente a partir dos dados retornados pela API.
- O comportamento padrão (sem filtros ou quebra) permanece o mesmo: soma total por categoria selecionada.

---

## Dúvidas ou Sugestões?

Entre em contato com a equipe PEERS Consulting para suporte ou para sugerir melhorias nesta funcionalidade.
