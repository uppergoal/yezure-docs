---
title: Order process
description: ''
position: 2.02
category: About
---

An order goes through several steps and each step executes different events.

## 1. Pending

the guest submits a rental request. At the time of submission, the order status is: `Pending`.

#### The guest
the guest can modify the offer or create a <nuxt-link to = "guide-counteroffer"> counter-offer </nuxt-link>.

#### The Rentor
The rentor can `accept` or` refuse` an order. He can also create a <nuxt-link to = "guide-counteroffer"> counter-offer </nuxt-link>.

## 2. Drop
the guest can drop the still `pending` order.

## 3. Approval of an offer
The rentor can `accept` or` decline` an offer. He can also make a <nuxt-link to = "guide-counteroffer"> counter-offer </nuxt-link>..

### 3.1 Accept

Accepting an order means that the order has been approved by the rentor according to the terms of the order. The order therefore remains open.

### 3.2 Refuse

Rejecting an order means that the order has been refused by the rentor according to the terms of the order.

## 4. The wait before the exchange

The step between approval and the start of the collection process.

### 4.1 Call-off

the guest can `call-off` a command. This action means that the order, which has been previously accepted, is canceled by the guest.

_It should be noted that this action is not very nice_

### 4.2 Cancel

The rentor can `cancel` an order. This action means that the order, which has been previously accepted, is canceled by the rentor.

_It should be noted that this action is not very nice_

## 5. Collection

Collection means the guest and rentor are ready to exchange the item.

### 5.1 Activate

The ad rentor or guest can `activate` an order 48 hours prior to the order start date. This action will activate the <nuxt-link to = "terms-general-deposit"> security deposit </nuxt-link> (If applicable) and execute payment for the order (if not already executed).

### 5.2 Disapprove

the guest may disapprove an offer stating that the item is not in good condition or does not represent the ad. If necessary, the guest will have to create a <nuxt-link to = "guide-contestation"> Contestation </nuxt-link>

## 6. Return of the item

The final stage of an order is the return of the order from the guest.

### 6.1 Finish

Completing an order means the guest has returned the item. This action will notify the rentor to `complete` the order.

### 6.2 Complete

Completing an order means that the rentor has received the item and that it is in good condition. We can therefore complete the order.

At this stage, the security deposit is released and each member of the order can evaluate it.