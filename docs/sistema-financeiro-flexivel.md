# Sistema Financeiro Flexível

Um método para organizar o dinheiro sem depender de força de vontade, planilhas de categoria por categoria ou culpa. A premissa: orçamento rígido falha porque compete com o cérebro humano — automação e "baldes" largos vencem porque não competem.

## Por que não um orçamento tradicional

Orçamento por categoria (ex.: "R$ 340,00 em alimentação este mês") cria três problemas psicológicos:

1. **Fadiga de decisão** — cada compra vira uma checagem mental contra um limite.
2. **Efeito "já era"** — ao estourar uma categoria, a reação comum é abandonar o controle inteiro no resto do mês.
3. **Associação negativa com dinheiro** — o sistema vira uma fonte de culpa em vez de uma ferramenta.

A alternativa: menos categorias, mais automação, e um valor explícito para gastar sem prestar contas a ninguém — nem a si mesmo.

## Os 4 baldes (em vez de 14 categorias)

As despesas informadas (moradia, contas da casa, alimentação, restaurante e delivery, transporte, saúde, pessoal, lazer, família/filhos, pessoas, financeiro, seguro, investimentos, extras) são reais e continuam existindo — mas não precisam de 14 limites separados. Elas se agrupam em 4 baldes, cada um com uma faixa de referência (não um número fixo):

| Balde | Faixa sugerida | Categorias que entram |
|---|---|---|
| **Fixos essenciais** | 45–55% | Moradia, contas da casa, alimentação, transporte, saúde, seguro, financeiro |
| **Pague-se primeiro** | 15–20% | Investimentos (poupança, reserva de emergência, aportes) |
| **Família & pessoas** | 8–12% | Família/filhos, pessoas (presentes, ajuda a terceiros) |
| **Sem culpa** | 20–30% | Restaurante e delivery, lazer, pessoal, extras |

A soma é 100% da renda líquida. As faixas são pontos de partida — o sistema é seu se você mover os números; o que não muda é a **ordem** em que o dinheiro se move.

## Pague-se primeiro (o núcleo do sistema)

A regra: investimentos não são "o que sobra no fim do mês" — são a primeira transferência automática do mês, no mesmo dia em que o salário cai. Antes de contas, antes de qualquer gasto.

Isso inverte a lógica padrão (*renda − despesas = poupança*) para *renda − poupança = despesas*, e resolve o problema comportamental real: ninguém "sobra dinheiro" no fim do mês por acidente. Automatizar remove a decisão.

**Regra de bônus — captura de aumento:** todo aumento de renda (reajuste, bônus, freela extra) direciona a primeira metade automaticamente para o balde "pague-se primeiro" antes de qualquer ajuste no padrão de vida. Isso neutraliza a inflação de estilo de vida, que é o maior inimigo silencioso de quem ganha mais e não percebe para onde o dinheiro foi.

## O valor sem culpa

Uma fatia fixa da renda (20–30%, sugestão de partida: 25%) é transferida automaticamente para uma conta ou cartão separado logo após o pagamento. Esse dinheiro:

- Pode ser gasto em qualquer coisa dentro do balde (delivery, lazer, roupas, hobbies, extras).
- **Não precisa ser justificado, categorizado ou revisado.**
- Se acabar antes do fim do mês, a resposta é esperar o próximo ciclo — não é motivo para abandonar o sistema inteiro.
- Se sobrar, pode ir para o próximo mês ou virar um aporte extra — mas isso é opcional, nunca obrigatório.

Esse valor é o que torna o sistema psicologicamente sustentável: ele dá permissão explícita para gastar, o que reduz o gasto por impulso/compensação que normalmente surge da restrição excessiva.

## Regras de automação

A sequência importa mais que os números. Ordem recomendada, a partir do dia do pagamento:

1. **Dia 0 — Pague-se primeiro.** Transferência automática (TED/PIX agendado ou débito programado) para investimentos, antes de qualquer conta ser paga.
2. **Dia 0–1 — Fixos essenciais.** Débito automático ou boleto agendado para moradia, contas da casa, seguro, saúde, transporte e compromissos financeiros. Nenhum desses pagamentos deve depender de ação manual mensal.
3. **Dia 1 — Sem culpa.** Transferência automática do valor livre para uma conta/cartão dedicado.
4. **Dia 1 — Família & pessoas.** Transferência automática para uma conta ou "envelope" dedicado a filhos, família e apoio a terceiros.
5. **Revisão mensal leve (5 minutos).** Não é revisão de cada gasto — é apenas conferir se as 4 automações rodaram. Se rodaram, o mês está resolvido antes de começar.

## Categorias e para onde vão

| Categoria original | Balde |
|---|---|
| Moradia | Fixos essenciais |
| Contas da casa | Fixos essenciais |
| Alimentação | Fixos essenciais |
| Transporte | Fixos essenciais |
| Saúde | Fixos essenciais |
| Seguro | Fixos essenciais |
| Financeiro (dívidas, taxas, mensalidades) | Fixos essenciais |
| Investimentos | Pague-se primeiro |
| Família/filhos | Família & pessoas |
| Pessoas | Família & pessoas |
| Restaurante e delivery | Sem culpa |
| Lazer | Sem culpa |
| Pessoal | Sem culpa |
| Extras | Sem culpa |

## Como usar

1. Defina a renda líquida mensal.
2. Ajuste as faixas dos 4 baldes se necessário (ver `data/categorias.json` para os valores padrão em formato de dados).
3. Configure as 4 transferências automáticas no banco, na ordem da seção acima.
4. Nunca acompanhe gasto por categoria dentro do balde "sem culpa" — isso reintroduz a rigidez que o sistema existe para eliminar.
5. Revise uma vez por mês, só para confirmar que as automações rodaram.

A ferramenta interativa em `calculadora/index.html` aplica essa lógica a qualquer valor de renda e permite ajustar os percentuais ao vivo.
