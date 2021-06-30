---
title: processus de commande
description: ''
position: 2.20
category: About
---

Une commande passe par plusieurs étapes et chaque étape exécute différents événements. 

## 1. En attente

l'invité soumet une demande de location. Au moment de la soumission, Le statut de la commande est: `En attente`. 

#### L'invité
l'invité peu modifier l'offre ou créer une <nuxt-link to="guide-counteroffer">contre-offre</nuxt-link>.

#### Le propriétaire
Le propriétaire peut `accepter` ou `refuser` une commande. Il peut aussi créer une <nuxt-link to="guide-counteroffer">contre-offre</nuxt-link>.

## 2. Laisser faire
l'invité peut laisser faire la commande qui est toujours `en attente`

## 3. Approbation d'une offre
Le propriétaire de l'article (annonce) peut `accepter` ou `refuser` une offre. Il peut aussi faire une contre-offre.

### 3.1 Accepter

Accepter une commande signifie que la commande à été approuvée par le propriétaire selon les modalitées de la commande. La commande reste donc ouverte.

### 3.2 Refuser

Refuser une commande signifie que la commande à été refusée par le propriétaire selon les modalitées de la commande.

## 4. L'attente avant l'échange

L'étape entre l'approbation et le début du processus de collect.

### 4.1 Raccrocher

l'invité peut `raccrocher` une commande. Cette action signifit que la commande, qui à été préalablement acceptée est annulée par l'invité. 

_Il est à noté que cette action n'est pas très gentille_

### 4.2 Annuler

Le propriétaire peut `annuler` une commande. Cette action signifit que la commande, qui à été préalablement acceptée est annulée par le propriétaire.

_Il est à noté que cette action n'est pas très gentille_

## 5. La collecte

La collecte signifie que l'invité et le propriétaire sont prêts à échanger l'article.

### 5.1 Activer

Le propriétaire de l'annonce ou l'invité peut `activer` une commande 48h avant la date de début de la commande. Cette action activera le <nuxt-link to="terms-general-deposit">dépôt de sécurité</nuxt-link> (S'il y a lieu) et executera le paiement de la commande (si pas déjà executé).

### 5.2 Désapprouver

l'invité peut désapprouver une offre stipulant que l'article n'est pas en bonne état ou ne représente pas l'annonce. Le cas échéant, l'invité devra créer une <nuxt-link to="guide-contestation">Contestation</nuxt-link>

## 6. Le retour de l'article

L'étape finale d'une commande est celle du retour de celle-ci du l'invité.

### 6.1 Finir

Finir une commande signifie que l'invité a retourné l'article. Cette action informera le propriétaire de `compléter` la commande. 

### 6.2 Compléter

Compléter une commande signifie que le propriétaire à reçu l'article et que celle-ci est en bonne état. On peut donc terminer la commande. 

À cette étape, le dépôt de sécurité est libéré et chaque membre de la commande peuvent évaluer celle-ci. 