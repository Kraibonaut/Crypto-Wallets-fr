# Level 4 - Crypto-Wallets

Dans ce module, vous apprendrez ce que sont les Crypto Wallets et comment en télécharger un. 🤔

## Introduction
Pour comprendre pleinement les portefeuilles de crypto-monnaies, nous devons comprendre certains concepts sur la blockchain, qui nous aideront à comprendre comment un portefeuille nous aide. Commençons par le début.

## What is an address? 🤨

Une adresse est une chaîne de texte générée par cryptographie pour représenter votre compte sur la blockchain. Cette adresse peut être partagée publiquement avec d'autres personnes, et ce, en toute sécurité. Vous pouvez envoyer et recevoir des fonds depuis et vers l'adresse de votre portefeuille. En fait, l'adresse est votre identifiant unique sur la blockchain et représente votre "compte". Voici un exemple d'adresse Ethereum : `0x01573Df433484fCBe6325a0c6E051Dc62Ab107D1`.

<Quiz questionId="3088223f-7ba3-4aee-9e75-c4a9dfee84e4" />

<Quiz questionId="12d7b8c0-59c7-4d3d-93f0-6dc7ede80d1d" />

## What are private keys? 🔐

Une clé privée est la contrepartie d'une adresse. Chaque adresse est associée à une clé privée. Comme son nom l'indique, cette clé est destinée à rester privée et à n'être partagée avec personne.

On peut l'assimiler à un mot de passe, très fort, contenant un ensemble de lettres et de chiffres qui vous permettent de prouver que vous êtes propriétaire de votre adresse. Toute personne qui possède la clé privée peut effectuer des transactions à partir de votre adresse, c'est-à-dire envoyer de l'argent de votre adresse à la sienne. 

Une clé privée ressemble à ceci: `E9873D79C6D87DC0FB6A5778633389F4453213303DA61F20BD67FC233AA33262`

Si vous considérez votre adresse comme le nom d'utilisateur de votre compte, la clé privée en est le mot de passe. Par conséquent, vous pouvez partager votre adresse, mais ne partagez jamais votre clé privée, sinon quelqu'un pourrait voler vos fonds - et il n'y aurait alors rien à faire. 

<Quiz questionId="2f0f1c91-7171-4039-bc84-8d6efbb717ff" />

**Attention : Les blockchains étant décentralisées, il n'y a pas d'option "mot de passe oublié". Si vous perdez votre clé privée, vous perdez l'accès à votre compte. De même, si quelqu'un vole votre clé privée et dérobe vos fonds, vous ne pouvez rien y faire. Il est TRÈS important de garder cette clé privée en sécurité.**

Pour les développeurs, nous utilisons souvent la clé privée dans le cadre de notre base de code pour effectuer certaines transactions, comme le déploiement de nos propres contrats intelligents sur le réseau Ethereum. Pendant que vous êtes encore en train d'apprendre, nous vous suggérons fortement d'utiliser un compte séparé entièrement pour le développement que vous utilisez pour stocker toute sorte de fonds. Malheureusement, les développeurs débutants utilisent souvent le même compte sur lequel ils ont des fonds, et partagent accidentellement leur base de code publiquement - et les pirates peuvent voir votre clé privée dans la base de code et finir par voler des fonds. Prenez cela comme un conseil de prudence.

<Quiz questionId="1d8fff7f-57ac-4555-ac2b-94c95c76f70d" />

## What is a seed phrase? 👮‍♀️

Une phrase de démarrage or seed phrase est comme un mot de passe principal - le mot de passe des mots de passe !

Pensez à un gestionnaire de mots de passe, comme Lastpass ou 1Password. Ces applications stockent en leur sein vos noms d'utilisateur et vos mots de passe pour d'autres applications en toute sécurité, et possèdent elles-mêmes un mot de passe. Ainsi, si quelqu'un pirate votre gestionnaire de mots de passe, il aura également accès à tous les comptes qui y sont stockés.

Un portefeuille cryptographique est un peu comme un gestionnaire de mots de passe, où vous pouvez gérer plusieurs comptes blockchain. Si la clé privée est le mot de passe d'un seul compte, la phrase de démarrage est en quelque sorte le mot de passe principal de ce portefeuille.

<Quiz questionId="530db4f0-937f-409f-ba7c-9456b0174151" />

Lorsque vous créez un nouveau portefeuille de crypto-monnaies, vous recevez une phrase de démarrage que vous devez absolument conserver et sauvegarder en toute sécurité. Tous les nouveaux comptes que vous créerez à l'intérieur de ce portefeuille seront tous liés à la phrase d'amorçage. Cette phrase d'amorçage générera toujours les mêmes comptes, avec les mêmes clés privées et les mêmes adresses pour chacun.

Ainsi, par exemple, si vous avez créé un portefeuille, puis 5 comptes, votre phrase d'amorçage gère les 5 comptes. Si vous voulez passer à un nouveau portefeuille, vous pouvez soit importer les 5 portefeuilles individuellement - en utilisant leurs clés privées individuelles - ou simplement importer en utilisant la phrase d'amorçage, et cela régénérera les 5 mêmes comptes.

Un exemple de phrase d'amorçage est : `dove lumber quote board young robust kit invite plastic regular skull history`

<Quiz questionId="d4eae61d-fcf7-4447-9dcd-0bd737a687ce" />

## What is a crypto wallet then? 😛

Les portefeuilles de crypto-monnaies sont un gestionnaire de vos comptes, et principalement de leurs clés privées. Ils vous permettent également d'interagir avec des applications décentralisées, et de vous connecter à une dApp par le biais du portefeuille, agissant comme une signature unique pour toutes les applications construites sur la blockchain. 

Chez LearnWeb3 aussi, vous pouvez aller dans le tableau de bord et connecter votre portefeuille cryptographique (après l'avoir configuré), ce qui nous permettra de savoir quelle est votre adresse afin que nous puissions vous envoyer des NFTs de malade lorsque vous serez diplômé de nos cours !

<Quiz questionId="6566fc7a-661a-4a6e-b426-d2f851f697f9" />

## Setting up a Wallet 🎉

Pour Ethereum, il y a un certain nombre d'options de portefeuille disponibles. Les plus faciles à utiliser, et les plus conviviales pour les développeurs, sont Metamask ou Coinbase Wallet. 

Tous deux sont des portefeuilles de crypto Ethereum qui peuvent être installés comme extensions de navigateur ou comme applications mobiles. Vous pouvez trouver les liens de téléchargement ci-dessous. Nous vous suggérons de télécharger l'un d'entre eux et de le configurer avant de passer à la piste.

- [Download Metamask](https://metamask.io/download.html)
- [Download Coinbase Wallet](https://www.coinbase.com/wallet)

<Quiz questionId="96c7e46e-5d73-420c-b9da-088f4ad2b29a" />

Parmi les autres possibilités, citons Trust Wallet, Atomic Wallet, Rainbow Wallet, Frame.sh, etc.
- [Trust Wallet](https://trustwallet.com/)
- [Atomic Wallet](https://atomicwallet.io/)
- [Rainbow Wallet](https://rainbow.me/)
- [Frame.sh](https://frame.sh/)

<Quiz questionId="0941bbfc-0bbc-4897-ae15-0a4a87c71b16" />

<SubmitQuiz />
