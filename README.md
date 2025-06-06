Análise de Produtividade por Equipe
Este repositório contém um script em Python (pandas) para análise de produtividade de equipes, com base em métricas como:
✅ Horas gastas vs. estimadas
✅ Status de tarefas (Concluídas, Pendentes, Em Andamento)
✅ Prioridades (Alta, Média, Baixa)
✅ Insights estratégicos para stakeholders

📌 Como Usar
Pré-requisitos
Python 3.x

Bibliotecas: pandas, numpy

Instalação
pip install pandas numpy


🔍 Insights Gerados
1. Desenvolvimento
Maior atraso: +7h em média por tarefa.

Sugestão: Revisar critérios de estimativa e alocar buffer para tarefas complexas.

2. Marketing
Bom desempenho: Atraso médio de apenas +2.5h.

Destaque: Tarefas concluídas com prioridade Baixa/Média.

3. RH
Eficiência: Conclusão -1.25h abaixo do estimado.

Alerta: Tarefa pendente (Prioridade Alta) com apenas 5h gastas (faltam 7h).

4. Vendas
Variabilidade: Tarefa pendente (ID 116) já consumiu 23h (estimado: 19h).

Ação urgente: Revisar escopo ou alocar recursos extras.

🚀 Recomendações para Stakeholders
Otimizar estimativas usando dados históricos (especialmente em Desenvolvimento).

Monitorar tarefas críticas (Pendentes/Em Andamento com Prioridade Alta).

Capacitar equipes (ex.: Vendas) em gestão de tempo.

Investigar gargalos no RH para tarefas paradas.

📌 Próximos Passos
Adicionar visualização com matplotlib/seaborn.

Implementar análise por membro da equipe.

📩 Contato
Feito por Lucas Vescovi
✉️ lucasvescovir@gmail.com
🔹 Licença: MIT
