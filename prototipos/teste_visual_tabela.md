# Checklist de Teste Visual - Tabela: Prévia dos Dados Filtrados

Este checklist deve ser utilizado para validar visualmente a implementação do destaque do cabeçalho (thead) da tabela na seção "Prévia dos Dados Filtrados" da página `prototipos/painel-monitoramento.html`.

## Itens de Verificação

1. **Cor de Background do `<thead>`**
   - [ ] O `<thead>` da tabela utiliza uma cor de fundo escura, consistente com a paleta de cores da marca PEERS (exemplo: `bg-peers-blue` ou equivalente definido em `layout_peers/layout.html`).
   - [ ] O destaque visual do cabeçalho é evidente em relação ao restante da tabela.

2. **Legibilidade do Texto**
   - [ ] O texto dos nomes das colunas no `<thead>` possui contraste suficiente com o background escuro (exemplo: texto branco `text-white`).
   - [ ] Não há dificuldade de leitura em diferentes níveis de luminosidade de tela.

3. **Bordas Arredondadas**
   - [ ] As bordas superiores do cabeçalho possuem as classes `rounded-tl-xl` (canto superior esquerdo) e `rounded-tr-xl` (canto superior direito).
   - [ ] O efeito visual das bordas arredondadas é perceptível e consistente com o design do restante da página.

4. **Layout Responsivo**
   - [ ] O cabeçalho da tabela mantém o destaque visual e a legibilidade em dispositivos mobile, tablet e desktop.
   - [ ] Não há sobreposição, corte de texto ou distorção visual em diferentes larguras de tela.

5. **Regressão Visual**
   - [ ] Nenhuma outra parte da página foi afetada negativamente pela alteração do cabeçalho da tabela.
   - [ ] Outros elementos de tabela (se houver) mantêm seu estilo e funcionalidade originais.

## Documentação dos Resultados

- **Data do Teste:** ____/____/____
- **Responsável:** ______________________

| Item | Resultado | Observações |
|------|-----------|-------------|
| 1    | [ ] OK / [ ] NOK |             |
| 2    | [ ] OK / [ ] NOK |             |
| 3    | [ ] OK / [ ] NOK |             |
| 4    | [ ] OK / [ ] NOK |             |
| 5    | [ ] OK / [ ] NOK |             |

**Observações Gerais:**

- ______________________________________________________________________
- ______________________________________________________________________

**Conclusão:**

- [ ] Alteração aprovada
- [ ] Ajustes necessários
