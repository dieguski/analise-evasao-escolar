# Análise Exploratória — Evasão Escolar

Análise exploratória e estatística de fatores socioeconômicos e acadêmicos
associados à evasão escolar em instituição de ensino superior.

## Contexto

Dataset com 150 registros de estudantes, contendo informações como idade,
renda familiar, situação de emprego, período cursado e desempenho acadêmico.

## Perguntas respondidas

- Existe uma faixa etária predominante entre os evadidos?
- Estudantes que trabalham têm maior probabilidade de evadir?
- A renda familiar influencia na evasão?
- Qual período do curso concentra maior taxa de evasão?
- Qual o motivo de evasão mais frequente?
- O desempenho acadêmico tem relação com a evasão?

## Tecnologias utilizadas

- Python
- pandas
- matplotlib
- estatística descritiva (média, mediana, moda, desvio padrão, correlação)

## Principais etapas

1. Análise exploratória inicial do dataset
2. Estatística descritiva por grupo (evadidos vs. não evadidos)
3. Cálculo de correlações entre variáveis socioeconômicas e evasão
4. Tabelas cruzadas com percentuais para comparação entre grupos
5. Visualizações para comunicação dos insights

## Principais achados

- Faixa etária com maior evasão: 18 a 25 anos (moda 20, média 24)
- Trabalhar está levemente associado a NÃO evadir (correlação negativa)
- Renda familiar isoladamente não determina a evasão
- 5º período concentra a maior taxa de evasão
- Motivo mais relatado: baixo desempenho — porém a correlação objetiva
  entre desempenho e evasão é positiva (0.15), sugerindo diferença entre
  percepção subjetiva e métrica registrada

## Arquivos

| Arquivo | Descrição |
|---|---|
| `analise_evasao_escolar.ipynb` | Análise exploratória completa |
