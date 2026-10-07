# Avaliação crítica do E6 — o que a banca vai cobrar

Revisão feita sobre o deck e a planilha E6 (set–out/2026). O que está bem: a tese é clara, a recomendação decorre dos números, a separação entre cálculo e hipótese é a parte mais madura da entrega, e a dívida foi considerada e descartada com motivo defensável. Abaixo, o que ainda falta ou está errado.

## 1. Os modelos das Sprints 5 e 6 não batem

| | Sprint 5 | Sprint 6 (E6) |
|---|---|---|
| Horizonte | 5 anos, ano 1 mensal | 3 anos, trimestral |
| Cenário oficial | Moderado | Tendencial |
| Taxa de serviço | R$ 120/módulo | ~R$ 200/viagem implícito |
| Capital necessário | R$ 559 mil | R$ 47,4 mil (A) / R$ 337,5 mil (B) |
| Governança | 5 sócios, 3 diretores | 2 founders |

São duas respostas diferentes para a mesma pergunta. A banca vai perguntar qual vale. **Reconciliar antes do Demo Day** — ou declarar explicitamente que o E6 é um exercício de comparação de estruturas sobre a trajetória de receita anterior, não o plano oficial.

## 2. Precificação, variável, fixo e margem de contribuição

- **Preço por viagem não aparecia** (corrigido no slide 6 do deck). O modelo usa ~R$ 200 (1.099 mil ÷ 5.508), acima do fee de R$ 50–150. Abrir fee + comissão.
- Só impostos, 3% de processamento e perdas são variáveis. **A linha "Total de custos" da DFC é custo fixo** (pessoal), com rótulo que confunde.
- **"Contribuição Bruta" da DFC não é margem de contribuição**, pois desconta esse fixo. A MC real é ~85–90% (R$ 170–180/viagem).
- **Ponto de equilíbrio** (adicionado): A ~90 viagens/trimestre, B ~300. Explica por que A vira no T3 e B no T9.

## 3. Problemas na planilha (aba `Viabilidade_S06`)

- **O aporte está contado duas vezes.** A linha "Acumulado / payback" parte de −R$ 47,4 mil (aporte como investimento no T0) e depois soma os FCLs, que já incluem CAPEX e custos. O aporte é financiamento, não investimento — existe para cobrir o vale do FCL. Somar os dois infla a "exposição máxima" (R$ 78,3 mil, quando o caixa mais baixo é R$ 31,3 mil) e deprime o VPL (A subiria de ~R$ 116 mil para ~R$ 160 mil).
- **Payback de A contraditório na própria aba:** a linha de métricas diz "> 12T", a linha de acumulado fica positiva no T10. Alinhar a fórmula.
- **Versão anterior tinha aportes divergentes entre abas** (47,8/339,7 nos Cenários × 47,4/337,5 nas DFCs). A revisão alinhou em 47,4/337,5; conferir que nenhum slide ficou com o valor antigo.

## 4. Premissas que parecem baixas ou inconsistentes

- **Pessoal:** R$ 148,8 mil para dois founders são ~R$ 6,2 mil/mês cada; em B, um Comercial/Parcerias sai a ~R$ 5,2 mil/mês bruto. Descontando staff, o OPEX não-pessoal de B no ano 1 (~R$ 38 mil) fica *abaixo* do de A (R$ 66 mil), sendo B a estrutura "profissional" com marketing. A frase "o OPEX total foi preservado" sugere que os salários foram encaixados num OPEX já fixado, não construídos de baixo para cima.
- **CAPEX de R$ 8/24/48 mil é incompatível com "plataforma 100% integrada"** (objetivo da Sprint 1) e com os R$ 110 mil de plataforma da Sprint 5. Ou o desenvolvimento é dos founders (mais sweat equity não contabilizado) ou o produto na entrada é concierge com ferramentas prontas — coerente com o aprendizado do Bruno Brant, mas precisa ser dito.
- **Tributação:** impostos sobem de 5,6% para 11,2% da receita em 12 trimestres. No ano 3 a alíquota efetiva já está em dois dígitos; se o enquadramento cair no Anexo V ou no Fator R, o modelo muda. O risco é o Anexo V, não o III.

## 5. Comparação A × B é de caixa, não econômica

O sweat equity de R$ 148,8 mil/ano é custo real que os founders bancam (~R$ 446 mil em 3 anos se mantido). Somado ao funding de A, a vantagem sobre B encolhe. Mostrar as duas leituras (caixa e econômica) para não parecer que a conclusão depende de esconder o custo dos fundadores.

## 6. A receita é idêntica em A e B

O modelo assume que uma equipe comercial contratada não vende mais que dois founders. Isso enfraquece B de propósito — ou é uma simplificação que a banca vai questionar. Se B "compra capacidade de execução", cabe um cenário em que B acelera a receita.

## 7. Sensibilidade sem os drivers já calibrados

Adesão de 50–70% e desconto de 20–30% vieram das entrevistas da Sprint 1 e não aparecem. Os cenários "restaurados da trajetória anterior" são opacos: mostrar a árvore escolas → turmas → alunos → viagens por aluno → fee, e testar preço separadamente de volume.

## 8. Menores

- O funding de A (R$ 47,4 mil) é pequeno o bastante para ser coberto pelos próprios founders — dizer se A precisa de capital externo ou não.
- O gate da recomendação não tem gatilho numérico (ver [`hipoteses-e-recomendacao.md`](hipoteses-e-recomendacao.md)).
- Canais de prospecção não estão definidos; o CAC está "não isolado".
