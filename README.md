# 📊 Análise de Satisfação do Cliente (NPS) em E-commerce

## 🎯 Objetivo

Este projeto tem como objetivo identificar os principais fatores operacionais que influenciam a satisfação do cliente em um e-commerce, utilizando o **NPS** como métrica central.

A análise busca responder:  
**Quais fatores impactam a satisfação e como antecipar a geração de detratores?**

---

## 📁 Base de Dados

Base contém ~2.500 registros com informações da jornada completa do cliente:

- Dados do pedido (valor, itens, descontos)
- Logística (tempo de entrega, atrasos, tentativas)
- Atendimento (contatos, resolução, reclamações)
- Indicadores internos (CSAT, recompra em 30 dias)
- Variável alvo: `nps_score` (0 a 10)

---

## 🔍 Metodologia

O projeto foi desenvolvido em três etapas principais:

1. **Entendimento do Negócio**
2. **Definição da Target** (NPS)
3. **Análise Exploratória de Dados (EDA)** com foco em negócio

---

## 📊 Principais Insights

- 🚚 **Atraso na entrega** é o principal driver do NPS
- 🔴 A partir de **3 dias de atraso**, mais de 90% dos clientes tornam-se detratores
- 📞 Maior número de reclamações e contatos com atendimento reduzem significativamente a satisfação
- ⏱ Tempo de resolução impacta negativamente
- 💰 Clientes com melhor NPS apresentam maior taxa de recompra

---

## 🚀 Recomendações

- Priorizar redução de atrasos logísticos (principal alavanca)
- Implementar alertas preventivos para pedidos em risco
- Otimizar o atendimento e reduzir tempo de resolução
- Utilizar CSAT interno como indicador antecipado

---

## ⚠️ Limitações

- NPS é coletado apenas após a jornada completa (viés temporal)
- Análise baseada em correlações (não necessariamente causalidade)

---

## 🛠 Tecnologias Utilizadas

- Python 3
- Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook

