# Arco 3 — Autonomia: segurança e primeira criação (Dias 15-21)

Marco do arco: seu próprio token deployado e sua jornada apresentada.
Ouro.

---

## Dia 15 — O manual do ladrão: golpes, phishing e o carimbo roubado

O QUE FAZ

Reconhece os 5 golpes mais comuns e revoga approvals perigosos.

COMO FAZ

Metáfora do carimbo: approve infinito é entregar seu carimpo assinado
em branco. Revogar é pegar o carimbo de volta.

PASSOS

    analisar 5 golpes reais documentados (o que o ladrão tocou?)
    abrir um revogador público e listar approvals da sua wallet
    revogar 1 approval velho ou infinito

SAÍDA ESPERADA

5 golpes identificados por mecanismo + 1 approval revogado.

ERRO DE INICIANTE

Clicar em link de "suporte" que pede seed. Suporte que pede seed é
ladrão com crachá falso. Sempre.

PROVA

Print da revogação + os 5 mecanismos em 1 linha cada. /approve-day day:15

---

## Dia 16 — Cofre frio e o ritual da seed

O QUE FAZ

Monta seu plano pessoal de backup e entende quente vs frio.

COMO FAZ

Escada de segurança: valor de treino em wallet quente; valor real em
cofre frio; seed em metal ou papel, nunca em foto, nunca em nuvem.

PASSOS

    escrever seu plano: o que fica quente, o que fica frio, onde mora a seed
    conferir o plano contra o checklist da aula (foto? nuvem? terceiros?)
    simular: "perdi o celular hoje" — quanto você perde?

SAÍDA ESPERADA

Plano escrito + resposta da simulação de perda.

ERRO DE INICIANTE

Deixar tudo na exchange "porque é prático". Prático até a exchange
virar manchete.

PROVA

Plano próprio no thread (sem revelar seed, óbvio). /approve-day day:16

---

## Dia 17 — Raio-x de contratos: auditando um token em 10 minutos

O QUE FAZ

Lê contrato no explorer: nome, supply, holders, permissões de mint.

COMO FAZ

Checklist de raio-x: quem pode mintar? supply é travado? há blacklist?
contrato é verificado? Quatro perguntas separam curiosidade de susto.

PASSOS

    aplicar o raio-x em 1 token suspeito sugerido pela turma
    aplicar em 1 token confiável e comparar os dois raio-x
    escrever o veredito próprio de cada um

SAÍDA ESPERADA

2 raio-x lado a lado com veredito.

ERRO DE INICIANTE

Confundir "contrato verificado" com "contrato seguro". Verificado =
código visível; seguro = código bom. São coisas diferentes.

PROVA

Os 2 raio-x no thread. /approve-day day:17

---

## Dia 18 — Gas: o pedágio da rodadura on-chain

O QUE FAZ

Entende por que se paga gas e como pagar menos sem virar refém.

COMO FAZ

Metáfora do pedágio: hora de pico custa mais; empacotar bem custa
menos por passageiro (batch!).

PASSOS

    comparar gas da mesma ação em 3 horários diferentes
    achar 1 exemplo de batch e calcular a economia por pessoa
    definir seu horário próprio de transação

SAÍDA ESPERADA

Tabela de horários + economia do batch + sua regra própria.

ERRO DE INICIANTE

Transação urgente em pico pagando 10x. Urgência cara é escolha, não
destino: saiba o preço antes.

PROVA

Tabela no thread. /approve-day day:18

---

## Dia 19 — Sua address fala: reputação on-chain

O QUE FAZ

Lê o histórico da própria wallet como um currículo público.

COMO FAZ

Tudo que você fez está escrito: primeiras txs, padrões, badges.
Reputação on-chain é o que seu endereço conta sem você abrir a boca.

PASSOS

    abrir seu endereço no explorer e ler sua própria história
    identificar: o que seu endereço já prova que você sabe fazer?
    escrever a frase que você quer que seu endereço conte em 1 ano

SAÍDA ESPERADA

Autoleitura do endereço + a frase de intenção.

ERRO DE INICIANTE

Achar que wallet é anônima de verdade. É pseudônima: o padrão conta
mais que o nome.

PROVA

Autoleitura no thread. /approve-day day:19

---

## Dia 20 — Sua primeira criação: um token seu, em testnet

O QUE FAZ

Deploya um token próprio usando template guiado no Remix.

COMO FAZ

Fábrica de moedas com 3 botões: nome, símbolo, supply. O template é
auditado; o aluno configura e assina — a mágica é ver o endereço
nascer do SEU clique.

PASSOS

    abrir o template no Remix em rede de teste
    configurar nome, símbolo e supply próprios
    deployar e achar seu token no explorer

SAÍDA ESPERADA

Endereço de contrato próprio, verificado no explorer.

ERRO DE INICIANTE

Deployar na rede errada por pressa. Conferir rede é o ritual que
separa criador de vítima.

PROVA

Endereço do SEU token no thread. /approve-day day:20

---

## Dia 21 — Graduação: o diploma que é uma transação

O QUE FAZ

Apresenta sua jornada completa à turma: endereço, transações, token.

COMO FAZ

Roda de formatura: cada aluno abre o próprio explorer ao vivo e conta
sua história em 5 minutos. A prova não é um papel: é o livro público.

PASSOS

    montar sua linha do tempo: primeira tx, primeiro swap, seu token
    apresentar na roda (ou no thread de formatura)
    escrever: "o que eu faria diferente no Dia 1?"

SAÍDA ESPERADA

Apresentação feita + linha do tempo pública + a frase do Dia 1 revisitada.

ERRO DE INICIANTE

Achar que formou porque terminou. Formou porque agora você verifica
sozinho — e isso não termina nunca.

PROVA

Apresentação + linha do tempo. /approve-day day:21 -> BADGE OURO +
cargo On-Chain Master. Bob, onde você estiver: agora você é dono.
