# Arco 2 — O ecossistema: dinheiro, trocas e organizações (Dias 8-14)

Marco do arco: entender as 4 peças da bússola por dentro. Prata.
Todas as aulas deste arco terminam com o disclaimer educacional:
nada aqui é recomendação financeira; é alfabetização.

---

## Dia 8 — A retomada da bússola: agora destrava

O QUE FAZ

Reabre o mapa do Dia 1 com olhos novos: o aluno já tem wallet,
transação, explorer — agora cada peça da bússola ganha sentido.

COMO FAZ

Retomada narrativa: "lembra dos 4 quadrados? Você já segura as
ferramentas pra abrir cada um." Tokens primeiro, porque são a
matéria-prima dos outros três.

PASSOS

    reabrir assets/desenhos/bussola-defi.svg
    inspecionar 3 tokens reais no explorer (nome, símbolo, supply)
    anotar: o que esses 3 tokens têm em comum com o quadrado TOKEN?

SAÍDA ESPERADA

3 tokens inspecionados + a frase própria ligando ao quadrado dourado.

ERRO DE INICIANTE

Achar que token é arquivo dentro da wallet. Token é anotação no
livro do contrato; a wallet só mostra sua linha.

PROVA

Print dos 3 tokens inspecionados. /approve-day day:8

---

## Dia 9 — Stablecoins: o dólar que mora na chain

O QUE FAZ

Entende o que segura o valor de uma stablecoin e os 3 tipos de lastro.

COMO FAZ

Comparativo honesto: lastro em reserva (cofre auditado), em crypto
(colateralizado), algorítmico (promessa matemática — e os cemitérios
deles). Risco não é detalhe: é a aula.

PASSOS

    comparar 3 stablecoins de tipos diferentes
    achar o relatório de reservas (ou a ausência dele) de uma delas
    escrever: "eu confiaria meu aluguel aqui? por quê?"

SAÍDA ESPERADA

Tabela própria com 3 stablecoins, tipo de lastro e nível de confiança.

ERRO DE INICIANTE

"Stablecoin = dólar no cofre." Nem sempre: algumas são promessa
algorítmica. Leia o lastro antes do símbolo.

PROVA

Tabela postada no thread. /approve-day day:9

---

## Dia 10 — DEX e AMM: troca sem corretor, preço por proporção

O QUE FAZ

Executa o primeiro swap em testnet e entende a piscina de liquidez.

COMO FAZ

Metáfora da piscina: duas águas (dois tokens) em proporção; quem
tira uma, encarece ela. O preço nasce da proporção, não de um livro
de ofertas central.

PASSOS

    abrir uma DEX em rede de teste
    executar swap pequeno de token de treino
    observar: preço antes, preço depois, taxa paga

SAÍDA ESPERADA

Swap executado + explicação própria da proporção da piscina.

ERRO DE INICIANTE

Ignorar slippage e taxa: swap grande em piscina rasa come seu
dinheiro. Tamanho importa.

PROVA

Hash do swap + 2 linhas explicando a piscina. /approve-day day:10

---

## Dia 11 — Lending: banco sem banqueiro, com termômetro

O QUE FAZ

Entende colateral, juros e liquidação em protocolos de empréstimo.

COMO FAZ

Metáfora do penhor com termômetro: você deposita mais do que pega;
se o termômetro (preço) andar contra você, o contrato vende seu
colateral sozinho. Ninguém liga pra te avisar.

PASSOS

    simular colateral e liquidação na planilha da aula
    calcular: quanto o preço pode cair antes da liquidação?
    ler 1 posição real liquidada em protocolo público

SAÍDA ESPERADA

Simulação calculada + o caso real de liquidação resumido.

ERRO DE INICIANTE

Emprestar perto do limite achando que "dá tempo de reagir". O
contrato não espera: liquida sozinho.

PROVA

Cálculo da simulação no thread. /approve-day day:11

---

## Dia 12 — NFTs: escritura, não quadro

O QUE FAZ

Entende o que se possui de verdade num NFT: o apontador, não a arte.

COMO FAZ

Metáfora da escritura: o NFT é o registro de propriedade apontando
para um conteúdo; o conteúdo pode morar em qualquer lugar (e sumir).

PASSOS

    abrir 1 NFT público no explorer
    achar o metadata e o URI do conteúdo
    verificar: o conteúdo mora on-chain ou apontado fora?

SAÍDA ESPERADA

1 NFT dissecado: contrato, token id, metadata, onde mora o conteúdo.

ERRO DE INICIANTE

"Comprei o NFT, tenho a imagem." Você tem a escritura; a imagem
pode ser um link. Leia o URI.

PROVA

Dissecação postada no thread. /approve-day day:12

---

## Dia 13 — DAOs: o dia em que Bob vira dono

HISTÓRIA DE RETORNO
Lembra do Bob? Hoje ele para de ser espectador.

O QUE FAZ

Monta o raciocínio da BandaDAO passo a passo e fecha o loop do Dia 1:
quem ajuda a construir, participa da valorização.

COMO FAZ

Comparativo em 3 colunas: empresas (contrato social + ações),
governos (impostos + título de eleitor), DAOs (regras em código +
caixa on-chain + token de propriedade). A DAO é a fusão, nativa
digital. Depois, o passo a passo da BandaDAO: caixa no Aragon/DaoStack,
campanha no Mirror, token $BANDA, recompensas via SourceCred/Coordinape,
votos no Snapshot, portas token-gateadas no Discord/Telegram via
collab.land.

PASSOS

    votar em 1 proposta real de DAO pública via Snapshot
    comparar: collab.land (gate pronto) vs MintPass (nosso bot
    concedendo cargo por badge on-chain) — mesma ideia, dois mundos
    escrever: "que decisão da MINHA comunidade deveria viver numa DAO?"

SAÍDA ESPERADA

Voto on-chain registrado + o comparativo dos dois gates + a frase
própria sobre sua comunidade.

CAIXA DE HISTÓRIA
Krausehouse: 1000 ETH pra comprar um time da NBA.
PleasrDAO: NFT do Snowden por US$ 5,4 mi, fracionado em bilhões de tokens.
CityDAO: um pedaço de Wyoming onde a terra é NFT e o voto é token.

ERRO DE INICIANTE

Achar que DAO é empresa sem dono. DAO nasce centralizada nos
fundadores e descentraliza com o tempo — governança é jornada.

PROVA

Print do voto + a frase própria. /approve-day day:13

---

## Dia 14 — L1, L2 e pontes: por que a taxa muda de rua pra avenida

O QUE FAZ

Compara custo e velocidade entre redes e entende o papel das pontes.

COMO FAZ

Metáfora viária: L1 é avenida segura e cara; L2 é rua do bairro que
empacota entregas e confere na avenida; ponte é o pedágio entre elas.

PASSOS

    comparar gas da mesma ação em 3 redes
    identificar 1 ponte pública e seus riscos (o que ela tranca?)
    escrever a regra própria: "quando uso qual rua?"

SAÍDA ESPERADA

Tabela de custos nas 3 redes + a regra própria de escolha.

ERRO DE INICIANTE

Ponte nova com valor grande sem teste pequeno antes. Ponte é
contrato confiando em contrato: teste com moedas de centavo.

PROVA

Tabela + regra própria no thread. /approve-day day:14 -> BADGE PRATA
+ cargo Builder.
