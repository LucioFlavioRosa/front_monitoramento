# Teste Manual: Filtros e Quebra no Painel de Monitoramento

## 1. Aplicar filtro de categoria
- Selecione uma categoria no controle "Filtrar Categoria" (ex: Projeto).
- Aguarde o carregamento dos valores disponíveis no controle "Valor do Filtro".
- Selecione um valor específico (ex: um projeto).
- **Esperado:** A tabela e os gráficos exibem apenas dados referentes ao valor filtrado.

## 2. Selecionar variável de quebra
- No controle "Quebrar/Dividir por", escolha uma categoria diferente do eixo X (ex: Usuário).
- **Esperado:** O gráfico de barras passa a mostrar barras empilhadas, cada cor representando um valor da categoria de quebra.

## 3. Combinar filtro e quebra
- Selecione uma categoria no filtro, depois um valor.
- Em seguida, escolha uma categoria para quebra.
- **Esperado:** O gráfico de barras mostra apenas os dados filtrados, divididos/empilhados por valores da categoria de quebra.

## 4. Testar diferentes combinações
- Varie o eixo X (Dia, Projeto, Modelo, Usuário).
- Combine diferentes filtros e quebras (inclusive sem filtro ou sem quebra).
- **Esperado:** O gráfico de barras e a tabela refletem corretamente os dados para cada combinação.

## 5. Responsividade
- Reduza o tamanho da janela do navegador (desktop, tablet, mobile).
- **Esperado:** Os controles de filtro e quebra permanecem utilizáveis, alinhados e visualmente integrados ao painel.

## 6. Casos de borda
- Selecione uma categoria de filtro sem valores disponíveis.
- Selecione um valor de filtro que não retorna dados.
- **Esperado:** Mensagens adequadas são exibidas na tabela e gráficos (ex: "A consulta não retornou dados.").

## 7. Performance
- Troque rapidamente entre filtros e quebras.
- **Esperado:** O painel responde de forma fluida, sem travamentos ou erros de renderização.
