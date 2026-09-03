# Plano de Quitação de Dívidas

Metodologia para eliminar dívidas o mais rápido possível, combinando matemática (juros) com psicologia (motivação). A ferramenta interativa em `calculadora/dividas.html` aplica isso aos seus números reais.

## Antes de tudo: o "orçamento de ataque"

Some o **pagamento mínimo de cada dívida** + o **valor extra mensal** que você consegue destinar além dos mínimos. Esse total é o seu orçamento de ataque — ele não muda entre os métodos. O que muda é **a ordem** em que as dívidas recebem o valor extra. Quando uma dívida é quitada, o mínimo que ela consumia **rola automaticamente** para a próxima da fila (efeito bola de neve/avalanche real) — o orçamento de ataque nunca diminui até a última dívida sumir.

## Os 3 métodos

### Bola de neve (snowball)
Ataca primeiro a dívida de **menor saldo**, independente da taxa de juros.

- **Vantagem:** primeira dívida some rápido → vitória rápida e visível → motivação para continuar. É o método com maior taxa de adesão até o fim, segundo estudo da Kellogg School of Management (Kettle, Trudel et al., 2016): pessoas que usam bola de neve têm mais chance de quitar todas as dívidas do que quem tenta otimizar matematicamente.
- **Desvantagem:** matematicamente sub-ótimo — pode pagar mais juros no total se a dívida pequena tiver taxa baixa e uma dívida grande tiver taxa alta.

### Avalanche
Ataca primeiro a dívida de **maior taxa de juros**, independente do saldo.

- **Vantagem:** sempre o menor total de juros pagos e, quase sempre, a data de quitação mais cedo — matematicamente ótimo.
- **Desvantagem:** se a dívida de maior taxa também tiver saldo alto, a primeira vitória pode demorar meses para aparecer, e a falta de progresso visível é a principal razão de abandono do plano.

### Híbrido (recomendado na prática)
Combina os dois: primeiro elimina as dívidas pequenas (abaixo de um limiar, ex.: 10% do total devido ou um valor fixo como R$ 1.000–2.000) na ordem da bola de neve, para gerar vitórias rápidas logo no início. Depois, com o momentum e a confiança já construídos, muda para a lógica da avalanche nas dívidas restantes, atacando sempre a de maior taxa.

- **Vantagem:** captura o benefício psicológico da bola de neve (motivação inicial) sem abrir mão de boa parte da economia de juros da avalanche.
- **Quando escolher:** é a opção padrão para quem tem 1–2 dívidas pequenas de taxa baixa (ex.: um financiamento parcelado) misturadas com dívidas de taxa alta (cartão, cheque especial) — cenário muito comum.

## Como comparar as datas de quitação

A ferramenta simula mês a mês: aplica juros sobre o saldo, paga os mínimos, e joga o valor extra na dívida prioritária de cada método (com o efeito de rolagem descrito acima), até o saldo total chegar a zero. O resultado de cada método mostra:

- **Data prevista de quitação**
- **Total de juros pagos** até lá
- **Ordem de ataque** das dívidas

Como referência geral (sem substituir a simulação real): avalanche costuma ganhar em juros totais e, com frequência, também em tempo; a diferença entre avalanche e híbrido costuma ser pequena (dias a poucas semanas); a diferença entre bola de neve pura e avalanche cresce quanto maior for o desequilíbrio entre as taxas de juros das dívidas.

## Estratégias psicológicas para manter a motivação

1. **Congele o cartão antes de começar.** Guarde o cartão físico (ou bloqueie compras online) enquanto durar o plano. Nenhum método funciona se a dívida cresce mais rápido do que você paga.
2. **Automatize o valor extra.** Configure uma transferência automática no dia do pagamento para a dívida prioritária, do mesmo jeito que a lógica de "pague-se primeiro" do sistema de orçamento. Disciplina não escala; automação escala.
3. **Visualize o progresso, não só o objetivo.** Uma barra ou termômetro de "dívida total restante" caindo é mais motivador do que um número estático — o cérebro responde a movimento visível, não a metas abstratas.
4. **Comemore cada dívida quitada, por menor que seja.** Um marco pequeno e concreto (a última fatura do cartão de loja, por exemplo) sustenta a motivação até o próximo. É exatamente o mecanismo por trás do sucesso da bola de neve.
5. **Reformule a narrativa.** Trocar "estou preso pagando dívida" por "estou comprando minha liberdade financeira, uma parcela de cada vez" muda a relação emocional com o pagamento — de punição para progresso.
6. **Torne o esforço temporário e nomeado.** Dê um prazo e um nome ao período ("Operação zerar 2026") em vez de tratá-lo como um novo estilo de vida permanente. Sacrifício com prazo definido é mais sustentável do que restrição indefinida.
7. **Tenha um espectador.** Compartilhar o progresso mensal com alguém (parceiro, amigo, grupo) cria responsabilidade social — uma das alavancas mais fortes contra a procrastinação financeira.
8. **Não puna uma recaída — ajuste e continue.** Se um mês o valor extra não sair como planejado, o plano recalcula a data automaticamente; abandonar o sistema custa muito mais do que um mês de atraso.

## Uso

1. Liste cada dívida com saldo atual, taxa de juros mensal e pagamento mínimo.
2. Informe quanto consegue destinar de extra por mês, além dos mínimos.
3. Compare a data de quitação e o total de juros dos 3 métodos na calculadora.
4. Escolha o método pelo equilíbrio entre economia (avalanche) e motivação (bola de neve) — na dúvida, comece pelo híbrido.
5. Automatize o pagamento extra e revise apenas quando uma dívida for quitada (para redirecionar o valor liberado).
