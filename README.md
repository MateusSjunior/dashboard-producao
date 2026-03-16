# 🏭 Dashboard de Produção — Análise de Produtividade e Qualidade

> Dashboard desenvolvido em Power BI para monitoramento da performance produtiva de uma operação industrial,
> com foco em volume aprovado, taxa de rejeição, produtividade por operador e padrões sazonais de produção.

---

## 📌 Contexto do Projeto

O objetivo foi construir um painel operacional que permitisse acompanhar os principais indicadores de chão de fábrica em tempo real, identificar variações de produção ao longo do ano e analisar diferenças de desempenho entre operadores.

**Perguntas que o dashboard responde:**
- Qual o volume total produzido e aprovado no período?
- Qual é a taxa de rejeição e o percentual de qualidade?
- Como a produção se comporta mês a mês ao longo do ano?
- Qual o percentual de produtividade considerando horas produtivas e paradas?
- Existem diferenças de desempenho entre operadores?
- As quedas de produção estão associadas a problemas operacionais ou a outros fatores?

---

## 📈 Principais Indicadores

| Indicador | Valor |
|-----------|-------|
| **Total Aprovado** | **3.084.251 unidades** |
| Total Rejeitado | 21.076 unidades |
| Horas Produtivas | 30,96 Mil |
| Horas Paradas | 8,89 Mil |
| **Percentual de Produtividade** | **77,69%** |
| **Percentual de Qualidade** | **99,32%** |

---

## 🔍 Insights Encontrados

- **Qualidade excepcional:** O percentual de qualidade de 99,32% indica que apenas 0,68% das unidades produzidas foram rejeitadas — um nível de controle de qualidade muito acima da média industrial, sinalizando processos bem ajustados ou critérios rigorosos de inspeção.

- **Sazonalidade de produção com dois picos:** O volume produzido apresenta dois picos ao longo do ano — abril/maio (~310 Mil) e julho (~320 Mil, maior do ano) — com quedas expressivas em março (227 Mil) e no período de setembro a outubro (173–170 Mil, menores do ano).

- **Queda de produção não foi causada por problemas operacionais:** Um dado contra-intuitivo e relevante: setembro e outubro, os meses de menor produção, foram também os meses com menos horas paradas (0,31 Mil e 0,41 Mil respectivamente). Isso indica **correlação inversa entre horas paradas e volume produzido**, sugerindo que a queda foi causada por fatores externos — provavelmente baixa demanda ou parada programada de manutenção preventiva — e não por falhas ou ineficiências operacionais.

- **Horas paradas distribuídas ao longo do ano:** Ao contrário do que seria esperado, as paradas não se concentram nos meses de baixa produção. Essa distribuição uniforme sugere um plano de manutenção estruturado, o que é positivo para a continuidade operacional.

- **Diferenças significativas de produtividade entre operadores:** O filtro por operador revela variações expressivas de desempenho individual, especialmente nos meses de menor produção geral (setembro e outubro). Esse dado é estratégico para gestão de pessoas e pode orientar decisões de treinamento, realocação ou incentivos de performance.

---

## 🛠️ Ferramentas e Recursos Utilizados

| Recurso | Descrição |
|--------|-----------|
| Power BI Desktop | Desenvolvimento do dashboard e visualizações |
| Power Query (M Language) | Transformação e carregamento dos dados |
| DAX | Criação de medidas para KPIs de produtividade e qualidade |
| Gráfico de Área | Evolução mensal do volume produzido |
| Gráfico Gauge (velocímetro) | Percentual de produtividade e qualidade |
| Filtros interativos | Segmentação por Operador e Mês |

---

## 🖥️ Visualização do Dashboard

![Dashboard de Produção](https://github.com/MateusSjunior/dashboard-producao/blob/main/Prints%20e%20Fundos/Dashboard%20de%20Produ%C3%A7%C3%A3o.png)

---

> ⚠️ Os dados originais não estão disponíveis publicamente pois fazem parte de material de curso proprietário.
> O foco do projeto está na análise, nas visualizações e nos insights extraídos.

---

## 🚀 Próximos Passos

- [ ] Adicionar página de análise individual por operador com ranking de produtividade
- [ ] Criar indicador de OEE (Eficiência Global dos Equipamentos)
- [ ] Incluir análise de custo por unidade produzida
- [ ] Investigar os fatores externos que causaram a queda de setembro/outubro

---

## 👤 Autor

**Mateus da Silva Junior**
Analista de Dados em formação | Power BI · Excel · SQL · Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mateus-junior-7ab55b144/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MateusSjunior)

---

*Projeto desenvolvido como parte do meu portfólio de transição para a área de dados.*
