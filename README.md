# 📊 VA Dashboard — Monitoramento de Base de Clientes

> Dashboard desenvolvido em **Power BI** para acompanhamento diário da base de clientes, com foco em variações de ativação, desempenho por grupo e ranking por empresa.

---

## 🎯 Objetivo

Centralizar indicadores operacionais em uma única tela, permitindo que times de operações e gestão identifiquem rapidamente oscilações na base ativa, quedas por empresa e evolução mês a mês por categoria de plano.

---

## 📌 Funcionalidades

| Recurso | Descrição |
|---|---|
| 📦 **KPIs com variação** | Δ Dia e Δ Mês por categoria: Básico, Destaque, Plus, Essencial e Geral |
| 📋 **Tabela de Desempenho** | Ranking por grupo com indicadores visuais de alta e queda |
| 🏆 **Rankings automáticos** | Top Maiores Aumentos e Maiores Quedas por empresa |
| 🍩 **Distribuição por Categoria** | Gráfico donut com % da base por plano |
| 🔎 **Filtros interativos** | Região, Grupo, Empresa e Categoria com botão Limpar Filtros |
| 🗂️ **Navegação entre páginas** | Visão do Dia · Outros Dias · Mês a Mês |

---

## 🛠️ Tecnologias e Técnicas

- **Power BI Desktop** — desenvolvimento do relatório
- **DAX** — medidas de variação delta, rankings com `TOPN + ADDCOLUMNS`, detecção de nível de drill com `ISINSCOPE`
- **Power Query (M)** — ETL, limpeza e transformação dos dados
- **Modelagem Star Schema** — tabelas fato e dimensão separadas para performance otimizada

---

## 📈 Resultados e Aprendizados

- Implementação de **medidas DAX avançadas** para variação diária e mensal
- Uso de **rankings dinâmicos** com `TOPN` para Maiores Aumentos e Quedas
- Design de **navegação por páginas** com botões e marcadores (bookmarks)
- Redução do tamanho do modelo via **Star Schema**, com ganho de performance

---

## 👤 Autor

**Vinicius Ribeiro Abel**
- 💼 Analista de BI Jr. | iGaming
- 🎓 Ciência da Computação — Universidade Anhembi Morumbi
- 🐙 [GitHub](https://github.com/Viniboricuo)
- 💼 [LinkedIn](https://www.linkedin.com/in/viniciusribeiroabel/)

---

*Desenvolvido por Vinicius Ribeiro Abel*
