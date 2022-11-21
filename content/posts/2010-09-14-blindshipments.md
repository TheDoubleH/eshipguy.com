---
title: Blind or Double Blind Shipments
description: What is a Blind Shipment, and what is a Doble Blind Shipment? 
author: Henrik Helgesen
type: post
date: 2010-09-14T22:58:17+00:00
url: /blindshipments/
Image: images/blind-man.gif
dsq_thread_id:
  - 141906658
Views:
  - 1
categories:
  - Dynamics NAV
  - E-Ship
tags:
  - Blind Shipment
  - Double Blind Shpment
  - FedEx
  - Label
  - UPS

---
In this world of easy e-commerce solutions we often find us in a situation companies manage orders for other companies, and want to ensure that end customers not know about it. This can be accommodated in Standard eShip using Blind or Double Blind Shipment.

When using **Blind Shipment**, the Return Address on the Package (and label) will be populated with the information from the **Bill-To Customer**.

<!--more-->Example:

You work for the Cronus Winery. One of your customers &#8216;Zin Lovers Society&#8217; sends you orders, that are to go to it&#8217;s members (Customers).

You create orders &#8211; one for each ship-to looking like this:

Sell-To / Bill-To:

&#8216;Zin Lovers Society&#8217;  
97 Red Wine Lane  
Paso Robles, CA 97531

Ship-To

Henrik Helgesen  
123 Zin Drinker Ave  
Beverly Hills, CA 90210

in this example, the Label would have a return address of

Cronus Winery,  
995 Winery Rd,  
Napa Valley, CA

To avoid the confusion; the &#8216;Zin Lovers Society&#8217; ask that we use their name and address as the sender. By selecting Blind Shipment on the eShip tab, the return address will now state:

&#8216;Zin Lovers Society&#8217;  
97 Red Wine Lane  
Paso Robles, CA 97531

as specified in the Bill-To section of the order.

But since the &#8216;Zin Lovers Society&#8217; do not have a warehouse, Cronus Winery have accepted to handle returns for &#8216;Zin Lovers Society&#8217;.

In order to change the Return Address we need to make the order (Package) **Double Blind Shipment**. When Double Blind Shipment is selected, you need to also select a Customer, from where the return address information is to be retrieved. This often happens when you mail the invoice to a PO Box or deal with bog box stores.

You need to create a customer card with the following information

&#8216;Zin Lovers Society&#8217;  
995 Winery Rd,  
Napa Valley, CA

and select the customer in the Double Blind Ship From Cust No.

_Please note that FedEx at times changes their label which the requires new setup for Blind and Double Blind Shipment Labels to print correctly. A post for the will be posted soon(ish)_
