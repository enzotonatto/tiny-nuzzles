---
layout: default
lang: pt-BR
title: Política de privacidade
permalink: /privacidade/
alt: /en/privacy/
---

# Política de privacidade

**Versão de 28 de setembro de 2026.**

O Tiny Nuzzles é um app de conexão familiar: o adulto usa o iPhone, a criança
usa o Apple Watch, e os dois trocam recados de voz, fotos e partidas de jogos.
Esta política explica que dados o app guarda, por quê, onde e por quanto tempo.

## Quem é o responsável

Equipe Tiny Nuzzles. Contato para qualquer assunto de privacidade, inclusive
os pedidos da LGPD: **enzotonatto@gmail.com**.

## Crianças

- A conta é sempre de um **adulto**. É ele quem cria a família, cadastra a
  criança e pareia o relógio dela, e ao fazer isso consente, como responsável
  legal, com o tratamento dos dados da criança descrito aqui (art. 14 da LGPD).
- A criança **não tem login, e-mail nem senha**. O relógio recebe uma credencial
  no pareamento feito pelo iPhone do adulto.
- Os dados da criança só são vistos pelos adultos e pelas crianças da própria
  família. Não há perfil público, busca de pessoas nem contato com quem está
  fora da família.
- O app não mostra anúncios e não usa os dados de ninguém para publicidade.

## Que dados guardamos

**Do adulto**
- E-mail, nome, data de nascimento e, se enviada, foto de perfil.
- Senha, guardada só como hash (argon2id). Ninguém consegue lê-la de volta.
- Parentesco com as crianças (por exemplo, "Mãe").

**Da criança** (cadastrados pelo adulto)
- Nome ou apelido, data de nascimento, personagem ou foto de avatar e
  parentesco.

**Da família**
- Nome e foto da família e fuso horário.
- **Recados de voz** gravados pelos adultos e pelas crianças, e o registro de
  quem já ouviu cada um.
- Fotos enviadas pelos adultos (uma por dia por família).
- Partidas dos jogos e o histórico de momentos da família.

**Dos aparelhos**
- Token de notificação (push) do iPhone e do relógio, para avisar de recados
  novos.
- Credencial do relógio (guardada só como hash no servidor) e códigos
  temporários de convite e de pareamento.
- Sessões de login (o token de renovação é guardado só como hash).

O app **não** coleta localização, contatos, dados de saúde nem identificadores
de publicidade. O microfone só é usado enquanto você grava um recado, e a câmera
só enquanto lê o QR Code de quem vai entrar na família.

## Para que usamos

Só para o app funcionar: entrar na conta, montar a família, entregar recados,
fotos e partidas às pessoas certas e avisar quando chega algo novo. Não
vendemos, alugamos nem compartilhamos dados para marketing.

## Onde os dados ficam

- **Supabase**: banco de dados e armazenamento dos arquivos (áudios e fotos).
- **Railway**: servidor da API.
- **Apple Push Notification service**: entrega das notificações.
- **Apple TestFlight**: durante o teste, a Apple pode coletar relatórios de
  falha e o feedback que você envia pelo app TestFlight, conforme a política
  de privacidade da própria Apple.

Esses serviços processam os dados em nosso nome e podem ficar fora do Brasil.
A comunicação entre o app e o servidor é sempre criptografada (HTTPS).

## Por quanto tempo

- Enquanto a conta existir.
- Itens removidos da linha do tempo ficam 30 dias restauráveis e depois são
  apagados.
- Convites e códigos de pareamento expiram em minutos. Sessões expiram em 30
  dias sem uso.

## Excluir a conta

Em **Configurações → Conta → Excluir conta**, com a sua senha. A exclusão é
imediata e não pode ser desfeita:

- Se você for o **único adulto** da família, a família inteira é apagada junto:
  crianças, recados, fotos, partidas e relógios pareados.
- Se houver outros adultos, a família continua com eles, e os recados e fotos
  que você enviou são apagados com a sua conta. Se você for o dono, transfira
  a posse antes, em Família.

## Seus direitos (LGPD)

Você pode pedir confirmação de que tratamos seus dados, acesso, correção,
exclusão e informações sobre com quem eles são compartilhados. Escreva para
enzotonatto@gmail.com; respondemos em até 15 dias.

## Mudanças nesta política

Quando ela mudar, a versão e a data no topo mudam junto. Mudanças que afetem
dados de crianças serão avisadas dentro do app antes de valer.
