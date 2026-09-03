# Sistema Totalmente Automatizado de Finanças

Enquanto o sistema flexível (`docs/sistema-financeiro-flexivel.md`) define os baldes e as faixas, este documento é a **mecânica de execução**: em que dia exato cada transferência acontece, e o protocolo que substitui decisão em tempo real por regra decidida com antecedência — porque toda decisão financeira tomada no calor do momento é uma decisão emocional.

## O princípio

Um sistema "totalmente automatizado" não é sobre planilha nem sobre força de vontade — é sobre **remover o momento de decisão**. Se uma transferência depende de você lembrar e decidir todo mês, não é automação, é uma tarefa recorrente que eventualmente vai falhar. A regra: tudo que se repete todo mês vira ordem permanente, TED/PIX agendado ou débito automático — configurado uma vez, revisado uma vez por mês.

## O calendário do mês

Todo mês tem 3 tipos de evento automático, sempre nesta ordem relativa ao dia do pagamento:

1. **Dia do pagamento (dia 0):** pague-se primeiro — transferência automática para poupança/investimento, antes de qualquer outra coisa.
2. **Dia 0 a +1:** débitos automáticos das despesas fixas, cada uma no seu dia de vencimento — configuradas uma vez no banco/operadora, nunca pagas manualmente.
3. **Dia +1:** fundo sem culpa e, se houver, o aporte para uma meta específica — transferidos para contas/cartões separados.

A ferramenta em `calculadora/automacao.html` gera esse calendário automaticamente a partir da sua renda, despesas fixas (com dia de vencimento) e metas.

## Meta específica (opcional)

Se você tem um objetivo com valor e prazo definidos (viagem, entrada de imóvel, etc.), o aporte mensal necessário é:

**Aporte mensal = (valor da meta − valor já guardado) ÷ meses restantes até a data-alvo.**

Esse valor entra como mais uma transferência automática, no mesmo dia do fundo sem culpa — não como algo que você decide mês a mês se vai ou não guardar.

## Protocolo para decisões emocionais

O objetivo não é nunca sentir vontade de gastar por impulso — é ter uma regra pronta para quando isso acontecer, para que a decisão não seja tomada no calor do momento:

1. **Regra das 72 horas.** Qualquer compra não planejada acima de um valor definido por você (ex.: 5% da renda mensal) espera 72 horas antes de ser feita. Se depois de 72 horas ainda fizer sentido, use o saldo do fundo sem culpa — não outra fonte.
2. **Uma única fonte para gasto livre.** O fundo sem culpa é a única conta/cartão de onde saem gastos não planejados. Nunca mexer na conta de pague-se primeiro ou nas contas fixas para cobrir um impulso — isso quebra a automação em vez de ajustá-la.
3. **Sem decisão fora da revisão mensal.** Mudanças nas automações (valores, percentuais, novas metas) só acontecem durante o ritual mensal de revisão (`docs/ritual-revisao-financeira-mensal.md`) — nunca em resposta a um gasto isolado ou a uma notícia do dia.
4. **Gatilho identificado, regra pronta.** Liste os 2-3 momentos em que você mais historicamente gasta por impulso (fim de expediente estressante, comparação em rede social, comemoração) e defina, com antecedência, o que fazer no lugar de abrir o cartão — a regra substitui a força de vontade no momento exato em que ela costuma faltar.
5. **Cartão fora de vista, automação fora de alcance.** Se possível, guarde o cartão físico e remova-o de carteiras digitais durante a fase inicial do sistema — reduzir o atrito para gastar automatizado é tão importante quanto automatizar o quê poupar.

## Checklist de implementação no banco

1. Configurar transferência automática (TED/PIX agendado) para a conta de investimento, na data do pagamento.
2. Configurar débito automático de cada despesa fixa, na respectiva data de vencimento — nunca pagar boleto manualmente se a opção de débito automático existir.
3. Configurar transferência automática para a conta/cartão do fundo sem culpa, um dia após o pagamento.
4. Se houver meta específica, configurar a transferência do aporte mensal para a conta dedicada à meta, no mesmo dia do fundo sem culpa.
5. Revisar as automações uma vez por mês, dentro do ritual de revisão — nunca fora dele.
