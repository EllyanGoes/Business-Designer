# E6 — Custos, despesas, investimentos e DFC: founder-led × professional-led

**Objetivo (Squeeze do Encontro 6, Parte 2):** responder que estrutura é necessária para implementar o negócio projetado — e o que essa estrutura faz com o caixa. A sprint compara duas alternativas de entrada, consolida cada uma em DFC de 3 anos (12 trimestres) e recomenda uma.

> ⚠️ **Mesmo enunciado da Sprint 5, modelo diferente.** A Sprint 5 já responde ao Encontro 6; esta pasta guarda a versão alternativa entregue pelo grupo. A Sprint 5 trabalha com horizonte de 5 anos, cenário Moderado, taxa de R$ 120 e capital de R$ 559 mil. O E6 parte de outra planilha (`entregaveis/Antevia_Modelo_EcoFin_E6.xlsx`): 3 anos, três cenários (P/T/O) herdados da trajetória anterior, preço médio de ~R$ 200 por viagem e duas estruturas de pessoal. Os dois modelos **não foram reconciliados** — ver [`avaliacao-critica.md`](avaliacao-critica.md). Enquanto isso, cada deck deve ser apresentado com o seu próprio modelo, sem misturar números.

## Resposta em uma linha

A entrada **founder-led (A)** é a alternativa financeiramente mais robusta; a estrutura profissional **(B)** deve ser condicionada à validação comercial.

## As duas alternativas

| | **A — Bootstrap / Founder-led** | **B — Angel / Professional-led** |
|---|---|---|
| Equipe ano 1 | 2 founders, sem pró-labore (sweat equity R$ 148,8 mil) | 1 Ops/CS + 1 Comercial/Parcerias (R$ 176,4 mil) |
| Equipe anos 2–3 | +1 Ops/CS → 2 Ops/CS | 2 Ops/CS + 1 Comercial |
| OPEX (ano 1 → 2 → 3) | R$ 66,0 → 198,8 → 381,6 mil | R$ 214,8 → 324,0 → 477,6 mil |
| CAPEX (anos 1–3) | R$ 8 → 24 → 48 mil | idem |
| **Aporte inicial (tendencial)** | **R$ 47,4 mil** | **R$ 337,5 mil** |
| Caixa mínimo sem aporte | (R$ 31,3 mil) no T5 | (R$ 286,0 mil) no T9 |
| Resultado operacional > 0 | T3 | T9 |
| Caixa acumulado no T12 (com aporte) | R$ 292,5 mil | R$ 212,6 mil |
| VPL (TMA 15% a.a.) | R$ 116,2 mil | (R$ 476,7 mil) |
| Payback simples | T10 | > T12 |

A receita é **idêntica** nas duas alternativas. Toda a diferença de caixa vem da estrutura de pessoal: B compra capacidade de execução antes de existir demanda para usá-la.

## Cenários de receita (3 anos)

| Cenário | Ano 1 | Ano 2 | Ano 3 | 3 anos | Viagens | Choque de custos |
|---|---|---|---|---|---|---|
| Pessimista | R$ 38 mil | R$ 140 mil | R$ 372 mil | R$ 550 mil | 2.763 | OPEX +10% · perdas 2% |
| **Tendencial** | R$ 71 mil | R$ 284 mil | R$ 744 mil | **R$ 1,099 mi** | 5.508 | OPEX base · perdas 1% |
| Otimista | R$ 113 mil | R$ 455 mil | R$ 1,270 mi | R$ 1,838 mi | 9.180 | OPEX −5% · perdas 0,5% |

Funding requerido por cenário: A = R$ 328,5 / 47,4 / 29,0 mil; B = R$ 776,4 / 337,5 / 177,1 mil (P/T/O).

## Documentos desta pasta

- [`unit-economics-e-ponto-de-equilibrio.md`](unit-economics-e-ponto-de-equilibrio.md) — preço, custo variável, margem de contribuição por viagem e quantas viagens pagam o fixo de A e de B
- [`dfc-a-vs-b.md`](dfc-a-vs-b.md) — as duas DFCs trimestrais, a curva de caixa acumulado sem aporte e como o aporte é dimensionado
- [`estrutura-de-capital-e-viabilidade.md`](estrutura-de-capital-e-viabilidade.md) — os três caminhos (capital próprio, anjo, dívida), break-even × payback, VPL e TIR
- [`hipoteses-e-recomendacao.md`](hipoteses-e-recomendacao.md) — o que ainda é hipótese, os gates e a recomendação em três passos
- [`avaliacao-critica.md`](avaliacao-critica.md) — **o que a banca vai cobrar**: lacunas do modelo, inconsistências da planilha e correções sugeridas

## Entregáveis

- [`entregaveis/Sprint_E6_Kairos_Antevia.pptx`](entregaveis/Sprint_E6_Kairos_Antevia.pptx) — deck de 17 slides no padrão Minimal Future (gráficos nativos; abrir no PowerPoint)
- [`entregaveis/Sprint_E6_Kairos_Antevia.pdf`](entregaveis/Sprint_E6_Kairos_Antevia.pdf) — o mesmo deck em PDF, com fontes embutidas
- [`entregaveis/Antevia_Modelo_EcoFin_E6.xlsx`](entregaveis/Antevia_Modelo_EcoFin_E6.xlsx) — planilha-fonte (abas `E6_*` e `Viabilidade_S06`)

## Roteiro do deck

1. Capa · 2. Do macroprocesso aos recursos · 3. Estrutura de pessoal · 4. Arquitetura de custos · 5. Cenários de receita · 6. Unit economics e ponto de equilíbrio · 7. DFC A · 8. DFC B · 9. Curva de caixa acumulado · 10. O que muda de A para B · 11. Sensibilidade · 12. Estrutura de capital (A/B/C) · 13. Break-even e exposição · 14. Indicadores de viabilidade · 15. Hipóteses · 16. Recomendação · 17. Encerramento

## Próxima etapa

Esta pasta não é a Sprint 6 (Plano de implementação), que segue a fazer. Pendências do E6: reconciliar os modelos das Sprints 5 e 6 num único cenário oficial; abrir a composição do preço (fee + comissão); transformar os gates da recomendação em números; e seguir com EAP, cronograma, matriz de responsabilidades, BSC e matriz de riscos.
