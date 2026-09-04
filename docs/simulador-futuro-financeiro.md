# Simulador de Futuro Financeiro (5, 10 e 20 anos)

Projeção de patrimônio a longo prazo a partir da situação atual (renda, poupança mensal, investimentos), com os riscos que a matemática do juro composto costuma esconder e os ajustes que mais pesam no resultado final.

## A projeção

Patrimônio projetado = patrimônio atual crescendo a juros compostos mensais, mais os aportes mensais (que também podem crescer todo ano, refletindo aumentos de renda acima da inflação). Tudo em termos **reais** (acima da inflação) — é a única forma de a simulação dizer algo sobre poder de compra futuro, não apenas sobre um número nominal maior.

**Retorno líquido = retorno bruto esperado − custo anual dos fundos/taxas.** A diferença entre os dois parece pequena ano a ano e é o fator que mais silenciosamente corrói patrimônio de longo prazo — ver "Risco de custo" abaixo.

## Os riscos que a simulação simples esconde

1. **Usar retorno nominal em vez de real.** Se a taxa usada não descontar a inflação, o número final parece maior do que o poder de compra que ele realmente representa.
2. **Risco de sequência de retornos.** Quedas de mercado nos anos próximos ao momento de usar o dinheiro fazem mais dano do que a média histórica sugere — mesmo com o mesmo retorno médio ao longo do período. Isso pede realocação para mais renda fixa conforme o horizonte encurta (ver `docs/portfolio-passivo-bogleheads.md`).
3. **Interrupção de renda.** Desemprego, doença ou mudança de carreira param os aportes por meses — sem um fundo de emergência (`docs/fundo-emergencia-liberdade-financeira.md`), a simulação para de valer a partir desse ponto.
4. **Inflação de estilo de vida.** Cada aumento de renda que vira gasto novo em vez de aporte maior reduz o crescimento composto de forma silenciosa e cumulativa — o efeito só aparece claramente depois de 10-15 anos.
5. **Risco de custo.** Uma diferença de 1 ponto percentual ao ano em taxa de administração parece irrelevante mês a mês, mas ao longo de 20 anos de juros compostos costuma consumir uma fração de dois dígitos do patrimônio final.
6. **Reação comportamental a quedas.** Vender na baixa por pânico, ou parar aportes durante uma crise, é o desvio mais comum entre a projeção teórica e o resultado real — mais impactante que a escolha exata de qual fundo usar.

## Os ajustes que mais pesam

Não são dezenas de mudanças — são poucas, aplicadas cedo:

- **Aumentar a taxa de poupança em alguns pontos percentuais**, mesmo que pareça pouco no mês, composto ao longo de 20 anos muda a ordem de grandeza do resultado.
- **Reduzir o custo dos fundos/taxas de administração** — trocar um fundo de custo alto por um de índice de baixo custo equivalente é o ajuste de maior impacto por menor esforço.
- **Manter os aportes durante quedas de mercado**, em vez de pausar — é justamente quando os aportes compram mais barato.

## Uso

1. Informe renda, poupança/investimento mensal atual, patrimônio já investido, retorno real esperado e custo anual dos fundos.
2. Veja a projeção em 5, 10 e 20 anos, e a renda passiva mensal que esse patrimônio sustentaria a uma taxa de retirada conservadora.
3. Simule um ajuste (aporte mensal extra) e compare a diferença acumulada em 20 anos na ferramenta `calculadora/simulador-futuro.html`.
