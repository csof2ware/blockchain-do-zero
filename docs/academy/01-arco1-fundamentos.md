# Arco 1 — Fundamentos: do caderno à chain (Dias 1-7)

Marco do arco: sua primeira transação verificada no explorer. Bronze.

---

## Dia 1 — O problema do Bob e o mapa da jornada

HISTÓRIA DE ABERTURA
Bob acompanha bandas locais: divulga, conecta, ajuda a cena a existir.
Uma banda viraliza, fica rica. E a parte de Bob? Nenhuma. Ele ajudou a
construir o ativo, mas não é dono de nada dele.

O QUE FAZ

Apresenta a promessa dos 21 dias: entender a estrutura que resolve o
problema do Bob — sem jargão, sem pressa, com um mapa na mão.

COMO FAZ

Narrativa primeiro, técnica depois. O aluno recebe a bússola dos 4
pilares (TOKEN, DAO, DEX, SMART CONTRACT) como promessa, não como
conteúdo: cada peça será destravada em uma aula específica.

PASSOS

    abrir assets/desenhos/bussola-defi.svg
    ler a história do Bob em voz alta (ou no thread da turma)
    escrever no diário: "que problema EU quero entender em 21 dias?"

SAÍDA ESPERADA

Diário com 1 frase própria + a bússola entendida como mapa, não como
matéria a memorizar.

ERRO DE INICIANTE

Querer decorar siglas no Dia 1. Não decore: a bússola existe pra você
se perder com segurança e achar o caminho de volta.

PROVA

Postar no thread do Dia 1: o problema do Bob com as SUAS palavras, em
uma frase. Mod aprova: /approve-day day:1

---

## Dia 2 — Wallets: o cofre, o vidrinho e o segredo

O QUE FAZ

Cria a primeira carteira e entende os 3 objetos: chave privada
(segredo), endereço (vidrinho público), seed (backup do segredo).

COMO FAZ

Metáfora do cofre: endereço é o vidrinho onde todos veem o saldo e
podem depositar; chave privada é o segredo que só abre pra fora;
seed é a frase que reconstrói o segredo se o cofre sumir.

PASSOS

    instalar MetaMask e criar carteira nova
    ritual do papel: anotar seed À MÃO, offline, sem foto, sem nuvem
    guardar endereço público num bloco de notas (esse pode circular)

SAÍDA ESPERADA

Carteira criada + seed em papel guardado + endereço anotado.

ERRO DE INICIANTE

Fotografar a seed "só pra não perder". Foto de seed é chave copiada
na porta do cofre. Nunca.

PROVA

Mostrar (sem revelar seed!) o papel guardado no local seguro +
postar seu endereço público no thread. /approve-day day:2

---

## Dia 3 — Transação é assinatura: o lacre de cera digital

O QUE FAZ

Entende que enviar na blockchain é assinar com a chave privada — e
que qualquer um pode verificar a assinatura sem conhecer o segredo.

COMO FAZ

Metáfora medieval: lacre de cera provava que a carta era do rei sem
que o mensageiro soubesse o conteúdo do sinete. Assinatura digital
faz o mesmo com matemática.

PASSOS

    assinar uma mensagem com a wallet (sign message no MetaMask)
    verificar a assinatura em um verificador público
    comparar: mensagem alterada em 1 caractere = assinatura inválida

SAÍDA ESPERADA

Uma assinatura sua verificada publicamente + o susto didático da
mensagem alterada.

ERRO DE INICIANTE

Confundir "assinar mensagem" com "enviar dinheiro". Assinar mensagem
não gasta nada e não move fundos — é só prova de autoria.

PROVA

Print da verificação verde com seu endereço. /approve-day day:3

---

## Dia 4 — Blocos, hash e por que o passado não muda

O QUE FAZ

Entende hash como impressão digital e por que alterar um bloco velho
quebra todos os seguintes.

COMO FAZ

Jogo do hash no papel: turma calcula "hash de brinquedo" (soma das
letras) de frases; muda 1 letra, muda tudo. Depois encadeia: cada
página cita o hash da anterior.

PASSOS

    calcular hash de brinquedo de 3 frases à mão
    alterar 1 letra e recalcular (o choque é o aprendizado)
    encadear 3 páginas: página 2 cita hash da 1, página 3 cita da 2

SAÍDA ESPERADA

3 páginas encadeadas no caderno + a frase própria: "mexeu no passado,
quebrou o futuro".

ERRO DE INICIANTE

Achar que bloco é arquivo guardado em um lugar. Bloco é página
copiada por milhares — por isso rasurar não adianta.

PROVA

Foto das 3 páginas encadeadas. /approve-day day:4

---

## Dia 5 — Consenso: por que ninguém manda

O QUE FAZ

Entende PoW e PoS como dois jeitos de escolher quem escreve a próxima
página sem dono central.

COMO FAZ

Simulação de turma: bingo dos validadores (PoW = corrida de cálculo;
PoS = fiança depositada que se perde se mentir). Quem trapaceia, perde.

PASSOS

    rodar a simulação com 5 participantes e 1 trapaceiro
    discutir: o que o trapaceiro perdeu em cada modelo?
    ler em voz alta: "consenso é custo de mentir"

SAÍDA ESPERADA

A simulação rodada + a conclusão própria sobre o custo de mentir.

ERRO DE INICIANTE

"Mineradores mandam na rede." Não: eles competem pra servir; quem
mente paga caro e sai.

PROVA

Relato de 3 linhas da simulação no thread. /approve-day day:5

---

## Dia 6 — Testnet e faucet: dinheiro de mentira, aprendizado de verdade

O QUE FAZ

Recebe ETH de teste e envia sua primeira transação a um colega.

COMO FAZ

Testnet é espelho da rede real com moeda sem valor: mesmo mecanismo,
zero risco. Faucet é a torneira que pinga esse dinheiro de treino.

PASSOS

    adicionar rede de teste no MetaMask
    pedir ETH em um faucet público
    enviar 0.01 de teste para o endereço de um colega da turma

SAÍDA ESPERADA

Transação de teste enviada + endereço do colega confirmado.

ERRO DE INICIANTE

Rede errada no MetaMask (mainnet na hora do teste, ou o contrário).
Conferir a rede ANTES de qualquer clique é hábito de profissional.

PROVA

Hash da transação de teste no thread. /approve-day day:6

---

## Dia 7 — Explorers: lendo o livro público como gente grande

O QUE FAZ

Acha sua própria transação no explorer e lê cada campo sem medo.

COMO FAZ

Explorer é o índice público do livro. De remetente, destinatário,
valor, taxa e status, tudo é auditável por qualquer pessoa online.

PASSOS

    colar seu hash no explorer da rede de teste
    identificar: from, to, value, fee, status, bloco
    achar a transação do colega pelo endereço dele

SAÍDA ESPERADA

Sua transação aberta no explorer com os 6 campos identificados.

ERRO DE INICIANTE

Confiar em print de terceiros. Print mente; explorer não. Verifique
sempre na fonte pública.

PROVA

Link público da sua transação + os 6 campos listados no thread.
/approve-day day:7 -> BADGE BRONZE + cargo Initiate.
