# 📊 FluxoLog — Sistema de PDV e Inteligência de Negócio

O **FluxoLog** é um sistema completo e moderno de Frente de Caixa (PDV), controle de inventário e inteligência financeira desenvolvido para rodar diretamente no navegador. O sistema une a agilidade operacional do balcão com relatórios estratégicos para tomada de decisão, funcionando de forma rápida e com persistência de dados local.

---

## 🚀 Funcionalidades Principais

### 💰 Frente de Caixa (PDV) Avançada
* **Abertura e Fechamento de Caixa:** Controle rigoroso por operador. O sistema exige um fundo de troco inicial e, no fechamento, cruza os valores do sistema (Dinheiro, PIX, Cartão) com o valor físico da gaveta, apontando quebras ou sobras.
* **Descontos e Acréscimos Flexíveis:** Permite aplicar descontos ou acréscimos (em R$ ou %) diretamente no total do carrinho antes de finalizar a venda.
* **Impressão de Cupom Não Fiscal:** Layout otimizado via CSS (`@media print`) para bobinas de impressoras térmicas (58mm e 80mm), gerando comprovantes limpos e padronizados.

### 📈 Inteligência de Negócio & Relatórios
* **Análise de Lucro Líquido Real:** Painel que calcula o faturamento total e subtrai o Custo de Mercadoria Vendida (CMV), exibindo a margem de lucro real do período.
* **Curva ABC de Produtos:** Classificação automática dos produtos com maior giro e maior impacto financeiro no faturamento (Categoria A).
* **Média de Markup Consolidada:** Indicador centralizado que exibe a média de markup praticada em todos os produtos cadastrados no banco.

### 📦 Cadastro e Precificação Inteligente
* **Cálculo Automático de Margem/Preço:** Insira o custo e a margem desejada para o sistema calcular o preço de venda, ou altere o preço final para recalcular a margem automaticamente.
* **Interface Responsiva:** Modais de cadastro otimizados com limites de altura e rolagem interna, evitando que botões de ação sumam atrás de barras de tarefas ou em telas menores.

---

## 🛠️ Linguagens Utilizadas

* **HTML5:** Estruturação semântica da aplicação.
* **CSS3 / Tailwind CSS:** Interface moderna, layout escuro (dark mode) focado em performance visual e responsividade.
* **JavaScript (Vanilla):** Lógica de negócios, cálculos de margem/markup e manipulação de estado.
* **LocalStorage:** Armazenamento local e persistente dos dados de produtos, vendas e histórico de caixa sem necessidade de banco de dados externo complexo.
* **Chart.js:** Renderização de gráficos compactos de faturamento e categorias.

---

Como o projeto foi desenvolvido com foco em simplicidade e portabilidade, ele não precisa de instalação de dependências pesadas:

