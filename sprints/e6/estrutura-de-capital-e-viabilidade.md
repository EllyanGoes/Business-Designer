# Estrutura de capital e indicadores de viabilidade

Fonte: aba `Viabilidade_S06` da planilha E6. Cenário tendencial; TMA de 15% a.a. (premissa acadêmica, a validar).

## Três caminhos considerados

| | **A — Capital próprio / Bootstrap** | **B — Investidor-anjo / Equity** | **C — Dívida (descartada)** |
|---|---|---|---|
| O que é | Founders executam a operação e aportam o caixa necessário | Equity financia staff profissional e runway | Crédito de sócios/bancário, com carência e amortização, foi simulado |
| Vantagem | Preserva equity e minimiza custo fixo | Capacidade de execução desde o ano 1 | — |
| Custo | Sweat equity (R$ 148,8 mil no ano 1, não desembolsado) | Diluição + cheque inicial 7,1× maior | Serviço da dívida incompatível com a geração de caixa inicial |
| Funding · VPL · payback | R$ 47,4 mil · R$ 116,2 mil · T10 | R$ 337,5 mil · (R$ 476,7 mil) · > 12T | — |

A análise de dívida foi útil justamente porque mostrou o descasamento com a fase de validação. C permanece como alternativa estudada e descartada; a comparação final concentra-se em A × B.

## Break-even × payback

Resultado operacional positivo não é o mesmo que recuperação do capital investido. Os dois precisam ser nomeados com precisão:

| Métrica | A | B |
|---|---|---|
| Break-even operacional (resultado de caixa > 0) | T3 | T9 |
| Exposição máxima* | R$ 78,3 mil | R$ 621,3 mil |
| Trimestre da exposição máxima | T5 | T9 |
| Payback econômico | T10 | > T12 |

\* Aporte inicial somado ao caixa acumulado negativo, como calculado na aba `Viabilidade_S06`. Ver ressalva em [`avaliacao-critica.md`](avaliacao-critica.md): esse cálculo conta o aporte duas vezes.

## Indicadores

| Indicador | A — Bootstrap | B — Angel |
|---|---|---|
| VPL do projeto | R$ 116,2 mil | (R$ 476,7 mil) |
| TIR trimestral | 14,4% | (14,5%) |
| TIR anual equivalente | 71,3% | (46,4%) |
| Payback simples | T10 | > 12T |

**Não confundir:** o cenário B não é um valuation do equity do investidor — mede-se a viabilidade econômica do projeto sob a estrutura B. A leitura é que capital deve acompanhar a evidência de tração, não antecedê-la.

## Sensibilidade: a demanda decide o tamanho do cheque

| Cenário | Funding A | Funding B | Diferença |
|---|---|---|---|
| Pessimista | R$ 328,5 mil | R$ 776,4 mil | R$ 447,9 mil |
| Tendencial | R$ 47,4 mil | R$ 337,5 mil | R$ 290,1 mil |
| Otimista | R$ 29,0 mil | R$ 177,1 mil | R$ 148,1 mil |

No pessimista, a necessidade de A salta de ~R$ 47 mil para ~R$ 328 mil. O funding tendencial não deve ser confundido com capital suficiente em qualquer cenário. Drivers críticos: alunos captados, frequência de viagens, fee, comissão, perdas e OPEX.
