# Teste Manual: Validação Visual da Tabela de Prévia dos Dados

## Objetivo
Garantir que a tabela de prévia dos dados no painel de monitoramento apresenta nomes de colunas corretos, design moderno e responsivo, efeitos visuais adequados e barra de rolagem customizada, mantendo consistência após renderização dinâmica.

---

## Cenários de Teste

### 1. Nomes das Colunas
- **Ação:** Verifique se cada coluna da tabela possui um nome claro e legível no cabeçalho.
- **Colunas esperadas:** Projeto, Usuário, Modelo, Dia, Valor (ou métrica selecionada).
- **Critério de sucesso:** Todos os nomes estão visíveis, alinhados e semanticamente corretos.

### 2. Responsividade
- **Ação:** Redimensione a janela do navegador para simular mobile (≤480px), tablet (≤768px) e desktop (≥1024px).
- **Critério de sucesso:**
  - A tabela se adapta ao tamanho da tela sem perder legibilidade.
  - O cabeçalho permanece fixo ou visível.
  - A rolagem horizontal aparece apenas quando necessário.

### 3. Efeitos de Hover e Zebra Striping
- **Ação:** Passe o mouse sobre as linhas da tabela.
- **Critério de sucesso:**
  - O efeito de hover destaca a linha de forma sutil e elegante.
  - Zebra striping (linhas alternadas com fundo diferente) facilita a leitura.
  - O estilo segue o padrão visual do layout principal (cores, bordas, sombras).

### 4. Barra de Rolagem Customizada
- **Ação:** Caso haja muitos dados, utilize a barra de rolagem da tabela.
- **Critério de sucesso:**
  - A barra de rolagem possui cor, largura e bordas customizadas conforme o design do layout_peers/layout.html.
  - O comportamento de rolagem é suave e funcional em todos os navegadores suportados.

### 5. Consistência após Renderização Dinâmica
- **Ação:** Atualize os filtros ou parâmetros para forçar a tabela a renderizar novos dados.
- **Critério de sucesso:**
  - O design, os efeitos visuais e a responsividade permanecem consistentes após a atualização dos dados.
  - Não há quebra de layout, sobreposição de elementos ou perda de estilos.

---

## Observações Adicionais
- Testar em navegadores modernos (Chrome, Firefox, Edge, Safari).
- Validar acessibilidade básica (leitura por leitores de tela, contraste de cores).
- Registrar screenshots dos principais cenários para documentação.

---

## Tempo Estimado
**30 minutos**
