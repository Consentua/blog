---
layout: post
title: Cookie Consent with Consentua 
published: true
author: jack_mason
comments: true
---

>One of Consentua's best features is that it can be used almost anywhere

Let's use [Consentua](https://consentua.com) and the consentua [webSDK](https://websdk.consentua.com) to create a cookie consent dialog which have been *popping up* a lot recently 😁.

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2018-07-10-Cookie-Consent-with-Consentua/consentua-cookie.jpg" alt="img">

## Creating Cookie Consent Dialog

Firstly, set up the [webSDK](https://websdk.consentua.com) just like any other web integration.

I am using a new single purpose interaction with the webSDK, which will be available soon!

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2018-07-10-Cookie-Consent-with-Consentua/carbon-1.svg" alt="img">

Then create a modal/dialog and place the iframe within. Be sure to add a 'no thanks' button which will let the user continue without enabling the cookies you're getting consent for.

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2018-07-10-Cookie-Consent-with-Consentua/carbon-2.svg" alt="img">

Add logic for handling cookies, Here I'm using a simple JavaScript API for cookies \([js-cookie](https://github.com/js-cookie/js-cookie)\), but using vanilla JavaScript would work just fine.

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2018-07-10-Cookie-Consent-with-Consentua/carbon-3.png" alt="img">

All that's left is to add some fancy styles 🎨 or animations and to create whatever cookies the user is consenting to in the `isConsented()` function.

### Done! 🎉🎉

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2018-07-10-Cookie-Consent-with-Consentua/consented.png" alt="img">

Here is a codepen snippet of the complete cookie consent dialog, you can view the full code needed here.

You can also see the [consentua home page](https://consentua.com) use this to enable google analytics cookies (you might need to clear your cookies).

<p data-height="700" data-theme-id="32866" data-slug-hash="BPaRRv" data-default-tab="result" data-user="sideshowjack" data-embed-version="2" data-pen-title="Consentua Cookie Consent" class="codepen">See the Pen <a href="https://codepen.io/sideshowjack/pen/BPaRRv/">Consentua Cookie Consent</a> by <a href="https://codepen.io/sideshowjack">sideshowjack</a> on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

If you've not signed up with a Consentua account yet, or need some help implementing and setting up Consentua, contact us here; or head to [Consentua.com](https://consentua.com) for more information.

<a class="btn btn-main" href="https://consentua.com/contact">Contact us</a>



## Extras

Code snippet images where created with [carbon.now.sh](https://carbon.now.sh)
