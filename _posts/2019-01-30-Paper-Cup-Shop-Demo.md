---
layout: post
title: Paper Cup Shop Consent Demo
published: true
author: chris_cooper
comments: true
---

Here at Consentua we are often asked what we consider best practice consent management to be.  The answer is that it depends.  

It depends on:  

- What the different types of personal data are being used for what purpose.
- Whether the aim is to have a standardised consent view across your whole organisation?
- Or is it to have a single go-to place for consent for all parties?
- Perhaps it is to improve trust in your brand? 

All these variables shape how and when you get consent from customers. However, their is nothing like a real-life working example to help shape your thinking.  To that end and to help get the creative juices going the Consentua team have mocked up a fairly standard e-commerce site via our new spoof company - “The Paper Cup Shop”.

Note:  This is only one example of best practice consent management.

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/1.png">

> The Paper Cup Shop is an open source web app built in VueJS, if you want to check out the code for yourself and see how Consentua works, you can have a look at the [Github repo here](https://github.com/mrsideshowjack/cup-shop)

Note the Consentua icon in the bottom right corner.  We will see more of this later….

However, the first screen you see is this: 

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/2.png">

The aim of this consent demonstration is to show how a consent profile against a specific user id is built up (Consentua UID).  This consent building occurs as you the customer go through the different steps towards a purchase of some cups from the demo site.

## Consentua Pop-up

<img class="img-right" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/3.gif">

In these images, we can see the Consentua pop up accessed via the Consentua Info slider.  
The Consentua info slider can be found on the top right next to the trolley.

## Cookie Consent

The start of the consent journey is to get the OK to use your device ID.  This is quickly established with the first consent request.  

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/4.png">

This demo is showing off a number of aspects that demonstrate Consentua’s flexibility.  The ‘show consentua slider’ is an example of showing off the real-time nature of the Consent interaction.  

## One consent at a time

The image below is showing that one purpose has been agreed to.  This was the device ID (Cookie Consent) request.  The Consentua UID is the token issued by Consentua.  

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/5.png">

As you move to the checkout another set of consents appears.  

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/6.png">

The above image shows the consent request being finalised at the end of the customer journey at the checkout.  With the pop-up showing three purposes now being consented too.  

<img class="img-right" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/7.png">

The consent is always interactable via the consent dashboard.  Accessed via the padlock icon. This takes the user to a new screen. The consent dashboard. 

## The consent dashboard 

The next two images are showing the consent that was previously set at checkout.  However, if a change occurs; for example, with the user's consent is withdrawn for a specific purpose.  Interacting with the slider changes the status on the pop-up.  Notice the red X showing that consent for that purpose is no longer there.

This consent setting is for this users session.  Which can be as permanent or temporary as required.  Renew the Consentua UID anytime to start over.  

Maintaining a consent is best done when the users identity is validated. This provides the join between device and user.  Consentua creates a UID that is now linked to that device.  

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/8.png">

## “Come in number 999999”
Plus they may also want to invoke the right to be forgotten.  This creates a notification need due to its time-limited requirement for a formal response.  Which can be a web notification or email. 

## What about the Consent Administration View

The consent administration view is focused on the template being used.  These are recorded in the popup. Each template hosts a specific purpose. Also identified in the popup.  

The first image is showing the service details and the associated templates. The second image is showing the template for the location purpose.

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/9.png">

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2019-01-30-Paper-Cup-Shop-Demo/10.png">