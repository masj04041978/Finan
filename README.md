# Finan — Sistema Financeiro Flexível

Um sistema de organização financeira pessoal baseado em automação e psicologia comportamental, não em orçamento rígido por categoria.

## App unificado

[`app.html`](app.html) — os 7 módulos abaixo reunidos em um único app, com um perfil compartilhado (renda, despesas, idade, patrimônio, perfil de risco) preenchido uma vez e reaproveitado em todos eles, mais dois módulos que sintetizam os outros: **08 · CFO pessoal**, que lê os 7 módulos e gera vazamentos de dinheiro, oportunidades perdidas, erros financeiros e um plano ordenado de até 3 passos; **09 · Redesenho de gastos**, onde você lista os gastos reais linha por linha e cada um recebe um veredito (manter / cortar / automatizar) — com regra concreta para assinaturas duplicadas — e os totais por categoria são comparados com as metas do módulo 01; e **10 · Histórico de gastos**, que analisa transações ao longo de vários meses (não uma foto isolada) para detectar assinatura, vazamento escondido, aumento de padrão de vida e compra por impulso, e ranqueia as mudanças por maior economia anual com menor impacto no estilo de vida. Cada módulo mantém seus campos específicos (dívidas, metas, país, respostas do ritual) e tudo é salvo apenas no navegador local — nenhum dado sai daqui. Este é o ponto de entrada recomendado; os arquivos individuais abaixo continuam funcionando de forma independente.

## Estrutura

- [`docs/sistema-financeiro-flexivel.md`](docs/sistema-financeiro-flexivel.md) — a metodologia completa: os 4 baldes, a lógica de "pague-se primeiro", o valor sem culpa e as regras de automação.
- [`data/categorias.json`](data/categorias.json) — modelo de dados com os baldes, faixas percentuais de referência e a sequência de automação, pronto para alimentar futuras telas ou integrações.
- [`calculadora/index.html`](calculadora/index.html) — calculadora interativa (módulo 01): informe a renda mensal e veja a divisão nos 4 baldes, incluindo o valor sem culpa, em tempo real.
- [`docs/plano-quitacao-dividas.md`](docs/plano-quitacao-dividas.md) — comparação entre os métodos bola de neve, avalanche e híbrido para quitar dívidas, com estratégias psicológicas de motivação.
- [`calculadora/dividas.html`](calculadora/dividas.html) — calculadora interativa (módulo 02): liste suas dívidas e o extra mensal disponível, e compare a data de quitação e o total de juros dos 3 métodos.
- [`docs/fundo-emergencia-liberdade-financeira.md`](docs/fundo-emergencia-liberdade-financeira.md) — cálculo do fundo de emergência ajustado por risco (não um "3-6 meses" genérico), do número de liberdade financeira com taxa de retirada conservadora, e um plano por etapas.
- [`calculadora/liberdade-financeira.html`](calculadora/liberdade-financeira.html) — calculadora interativa (módulo 03): informe renda, despesas, poupança atual e perfil de risco, e veja as 4 etapas com valores e datas estimadas.
- [`docs/portfolio-passivo-bogleheads.md`](docs/portfolio-passivo-bogleheads.md) — construção de carteira passiva estilo Bogleheads: alocação ações/renda fixa por idade, risco e horizonte, com exemplos de fundos por país.
- [`calculadora/portfolio.html`](calculadora/portfolio.html) — calculadora interativa (módulo 04): informe idade, país, horizonte, risco e aporte mensal, e veja a alocação-alvo e os fundos sugeridos.
- [`docs/ritual-revisao-financeira-mensal.md`](docs/ritual-revisao-financeira-mensal.md) — roteiro cronometrado de 20 minutos para a revisão financeira mensal, com as perguntas exatas de cada bloco.
- [`calculadora/revisao-mensal.html`](calculadora/revisao-mensal.html) — formulário interativo do ritual (módulo 05): calcula patrimônio líquido e taxa de poupança, guarda o histórico mês a mês no seu navegador e mostra a tendência.
- [`docs/automacao-financeira-total.md`](docs/automacao-financeira-total.md) — a mecânica de execução do sistema: o calendário de transferências automáticas, o protocolo para decisões emocionais e o checklist de implementação no banco.
- [`calculadora/automacao.html`](calculadora/automacao.html) — calculadora interativa (módulo 06): informe renda, dia do pagamento, despesas fixas e metas, e veja o calendário do mês com cada transferência automática no dia certo.
- [`docs/simulador-futuro-financeiro.md`](docs/simulador-futuro-financeiro.md) — projeção de patrimônio em 5, 10 e 20 anos, os riscos que a simulação simples esconde (custo, sequência de retornos, inflação de estilo de vida) e os ajustes de maior impacto.
- [`calculadora/simulador-futuro.html`](calculadora/simulador-futuro.html) — calculadora interativa (módulo 07): informe poupança mensal, patrimônio atual e retorno esperado, e compare a trajetória atual com um ajuste simulado ao longo de 20 anos.

## A ideia em uma frase

Em vez de controlar 14 categorias de gasto, a renda se divide em 4 baldes largos e automáticos — e o dinheiro se move sozinho na ordem certa, começando sempre por "pague-se primeiro".
