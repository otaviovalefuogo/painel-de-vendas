# 📊 Sistema de Inteligência Comercial - Painel de Análise de Vendas

## 🎯 Sobre o Projeto
Este projeto é um *dashboard* interativo de *Business Intelligence* desenvolvido para analisar as métricas financeiras e operacionais de uma empresa. O objetivo principal é transformar dados de vendas em informações visuais claras, facilitando a tomada de decisão estratégica por parte da equipe de gestão.

## 💡 Arquitetura e Experiência do Usuário (UX/UI)
O painel foi desenhado para simular o comportamento de uma aplicação web corporativa, fugindo do modelo tradicional de "planilha estática". Os destaques técnicos incluem:

* **Menu Lateral Fixo:** Navegação fluida e intuitiva entre as diferentes telas do relatório.
* **Painel de Filtros Inteligente:** Criação de uma "gaveta" oculta utilizando *Bookmarks* e botões. Permite aplicar filtros complexos (Data, Região e Categoria) sem ocupar espaço útil da tela, incluindo um botão rápido para Limpar Filtros.
* **Contexto Internacional:** Dados monetários formatados nativamente em Dólar, respeitando o *dataset* original e demonstrando adaptabilidade a cenários e dados internacionais.

## 🏗️ Estrutura do Sistema
O relatório está dividido em três camadas analíticas essenciais:

* **Home Page:** Capa de entrada minimalista com botões de navegação direta para os painéis de análise, garantindo uma recepção limpa ao usuário.
* **Visão Executiva:**
  * **Indicadores-Chave (KPIs):** Faturamento Total, Total de Pedidos, Ticket Médio e Itens Vendidos.
  * **Visualizações:** Análise percentual por Segmento de público (Consumer, Corporate, Home Office), evolução temporal do faturamento (2015-2018), ranking de subcategorias (Phones, Chairs, etc.) e o Top 10 de Estados com maior receita (liderado pela Califórnia e Nova York).
* **Detalhamento de Transações:** Uma tela de auditoria operacional focada na precisão. Apresenta uma matriz detalhada com cada transação, permitindo aos gestores rastrear o *Order ID*, a data, o nome do cliente, o produto exato e o valor faturado linha a linha.

## ⚙️ Tecnologias e Habilidades Aplicadas
* **Microsoft Power BI:** Importação, transformação e visualização dos dados.
* **MySQL:** Banco de dados relacional utilizado como fonte de dados, substituindo o CSV original. Os dados foram importados e estruturados via SQL antes de serem consumidos pelo Power BI.
* **Linguagem DAX:** Criação de medidas personalizadas e cálculos dinâmicos (Ticket Médio, Contagem Distinta de Pedidos).
* **Design de Interfaces Corporativas:** Utilização de um layout focado no contraste e alinhamento geométrico, com paleta de cores consistente e foco na legibilidade.

## 🚀 Acesso ao Projeto Interativo
O relatório foi publicado na web e pode ser acessado diretamente pelo navegador através da página HTML hospedada neste repositório:

🔗 **[Clique aqui para acessar o Dashboard Interativo](https://otaviovalefuogo.github.io/painel-de-vendas/)**

---
*Desenvolvido por Otávio Valefuogo.*
