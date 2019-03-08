---
layout: post
title: I need a Consent Service. What to do Next
published: true
author: chris_cooper
comments: true
redirect_from: "/2017/10/26/I-need-a-Consent-Service-What-to-do-Next//"
---


This is a blog aimed at developers, CTO’s, CIO’s.  It will also be of interest to DPO’s, compliance leaders, heads of marketing, customer service & operations. At a stretch CFO’s & CEO’s.

It all starts with the...

## Privacy Impact Assessment

Hopefully, your organisation has completed the Privacy Impact Assessment (PIA) as a result of GDPR. This exercise teased out where the data is in your organisation and the intended use for that data.  The PIA articulates what purposes personal data is being used for. 

Which then leads to...

## A new requirement for a CMP

With the PIA completed a high-level list of requirements are now building up. These requirements are probably along these lines:

I need an easy method of capturing consent to use certain types of data for certain purposes. I need to put my customers in control! But it has to offer a great user experience. 

This consent capture has to be unambiguous, ongoing and understandable. But don’t impact the customer experience. Nor damage my brand.

I want to ask for consent at different points in the customer journey.  I want to break up the purposes I ask for.  Only asking for consent when I really need it.

I want a trusted, inviolable audit point. This consent receipt should be in a secure, centrally managed space so that it can be easily shared with multiple parties both inside & outside my organisation, yet always in a controlled manner.

As a business person, I need to be able to change what I am asking for permission to process.  Because my service is going to change its data types and purposes over time.  I do not want to have to ask the IT team to make my changes.  I simply cannot wait that long.

I need to have a local language capability but at the same time… stay in the confines of the corporate framework.

Re-use existing investments (the PIA included) and minimise the impact to my enterprise (it has to be quick to deploy).

## Keep Calm and Get Consentua

The good news is that a consent management API service is available already and it can meet all of the above requirements. The service is called Consentua.

<img class="img-center" src="{{ site.baseurl }}/public/post_imgs/2017-10-13-Why-GDPR-is-good-for-Business-and-Citizens/keep-calm-and-get-consent-6.png" alt="img center">

Consentua does one thing very well. It provides end users with a transparent and easy to understand explanation of the types of data and the purposes their personal data will be used for. 

Whilst also giving the data controller flexible control over what is asked for and the ability to change this anytime. As well as providing both parties with a central audit point of the consent granted; plus it is secure, lightweight and easy to install.

## So I want this new service? How long will it take?

Anywhere from half a day upwards depending on the scale and complexity of your organisation, app deployment schedules and resources to work on the project. From our end the set up takes minutes. From your perspective it depends… but to gauge the effort here is what it takes.

The first step is to agree on the consent language to be used (more of an internal team effort here) and the build of the consent template.  Use the already completed PIA as a starting point.   This defines what the data purposes are and what purpose groups are required. 

Then the team at Consentua create your unique client consent service.  A short training session (less than hour), will set you up to take control of your service.  

Next step is to make the links between your consent services and your templates. Finally, the webSDK is seamlessly dropped into your existing browser or mobile app code.

Once the service has gone through a test cycle the production service is live. Ideally within two weeks of successful completion of testing. But this can happen the same day if all goes smoothly. The biggest impact is on your organisation and how prepared you are in terms of the use of a new language to describe the data types and purposes.

## What does the end user see?

Once the Consentua webSDK is in your code, the desired css is applied from then the consent service is ready to go in front of customers.   The customer can be introduced to any type of purpose at any point in the customer journey.  They are now in control.  
Check out the cup-shop e-commerce demo we have created.  [cupshop.consentua.com](http://cupshop.consentua.com)  - the aim of the demo is show off different styles, the way different purposes can be presented at different times in the customer journey.  

Their is a blog associated with the release of the demo: [consentua.com/blog/2019/01/30/Paper-Cup-Shop-Demo](https://consentua.com/blog/2019/01/30/Paper-Cup-Shop-Demo/) 

Note:  A user has their own unique Consentua ID and only that user can access the consent settings they have set. 

Check out the Consentua consent dashboard.  Remember this is what you have consented too.  [consentua.com/consent-dashboard](https://consentua.com/consent-dashboard.html)

## Developer Flexibility

Consentua is not just about apps though. The service is also enabled to handle consent interactions from systems too.  These could be your emailing and campaign manager, to your CRM or perhaps a 3rd party.

Options include a customer engagement system that is looking to check whether a 3rd party can see this personal data.  Or a customer has changed the consent set and the campaign management system needs to know that change has occurred automatically.  

To check out the API, see some WebSDk examples and use a set of credentials to test the API out, go to this page:  [consentua.com/get-started](https://consentua.com/get-started)

## Any gotchas?

Only one.  Consentua is identity agnostic.  Consentua does not store any user identifiable data.  What Consentua does though is create a unique Consentua identifier.  This will need to be stored then retrieved as required.

## What can the Business See?

From a business perspective, Consentua answers this question. What has the customer consented to? 

The answer can be queried either via the API or via the administrator's dashboard as a report.  Or a developer can create their own interface.   Check out this demo of the get consent views: [consentua.com/get-consent-page](https://consentua.com/get-consent-page/)

The business can view who has consented to a particular type of interaction/purpose or by a user or even by service

The by user view is useful as well to support notification of a data breach, as well as notifying a customer on the data the business holds on them. The by user view can be a handy way of establishing the right to be forgotten proof as well.

Third parties can access a consent service only if approved by you the consent service owner. Nice and secure, fully encrypted end-to-end too and in your control.

## I wanna change my mind

Yes is the answer.  Over time the data types and purposes can change.  Consentua out of the box is fully configurable and in the business’ control. 

The changes to a consent service can be made in real time. Next time the user goes to the consent view they will see the new data types and purposes.

## Tactical v Strategic

Consentua can be used as a mix of both. It could act as a ‘swing’ technology helping an organisation move to a more automated, streamlined future by enabling an evolutionary approach rather than a big bang. 

It could be part of tactical short term fix before a more strategic solution is deployed, but still allows re-use of the PIA and creates a standard based interoperable consent receipt. Or it could be part of a strategic shift the organisation undertakes to be more transparent and trustworthy with the aim of asking for and using personal data for the benefit of both consumer and provider.

## Must be expensive?

Actually no. Test is Free to use and we can set up a no obligation free trial.   Pricing for Consentua can be found here:  [consentua.com/pricing](https://consentua.com/pricing.html)

## Key things to consider are: 

1. How many users do I / will I have registered?
2. Do I want the Consentua service close to my servers or do I use the SaaS offering?
3. What brand do I want on the CMP?  Mine or Consentua?
4. Where do I go to sign up?

Simply go to the contact page and don't forget to give your consent! [consentua.com/contact](https://consentua.com/contact.html)