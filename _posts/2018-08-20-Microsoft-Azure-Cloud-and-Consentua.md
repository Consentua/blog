---
layout: post
title: Microsoft Azure Cloud and Consentua
published: false
author: chris_cooper
comments: true
---


# Microsoft Azure Cloud and Consentua

<img class="img-right" src="https://github.com/Consentua/blog/blob/master/public/post_imgs/2018-08-20-Microsoft-Azure-Cloud-and-Consentua/1.jpg" alt="Microsoft Azure Cloud image" width="200px" height="200px">
<a href="https://azure.microsoft.com">Microsoft Azure Cloud</a> was an obvious choice for hosting Consentua. The scalability and flexibility of the cloud services meant that we were able to set up and build the service very quickly. This article provides some insight into how we have set up Consentua to take advantage of some of the capabilities offered by Azure.

## A cloud is needed
We secured our <a href="http://shapingportsmouth.co.uk/shaping-blog/1223-innovate-uk-award">first sale of Consentua</a> to Innovate UK and Sharing Economy UK in 2016. Until then it was hosted on our development environment. We therefore had the question of which platform, and in which geography the production Consentua service would be hosted.    

We always knew from the outset that Consentua would be cloud hosted. This is because we already had experience within the team of using cloud services. Plus we did want to buy a server. In short  we were not scared to have a cloud first policy and the Consentua service was designed from the outset to be platform agnostic.

## The cloud platform picks you.
A developer usually has a bias in approach, tools and even the code style. Our Director of development Tom Ashcroft said 

> “I wanted to use Microsoft Azure Cloud for Consentua from the beginning. I was comfortable with their services and it was really quick to set up”

With Consentua the first version was written for a .net platform, that is because Tom uses C# and SOLID principles. As we want a cloud based solution which has to support a .Net platform, especially for the right price, our choice of platforms is more limited.    

## Microsoft Azure Cloud it is then… 
Therea are two reasons why Azure won over its competitors. Firstly, Azure was the only cloud platform that supported the .Net version that Consentua required. The second was price and performance. This was especially valid during the development phase because Azure comes with a healthy free allocation which meant we would not be paying for any compute resources in the short term. A good proposition for a product in development.

## Maximising your investment
<img class="img-right" src="https://github.com/Consentua/blog/blob/master/public/post_imgs/2018-08-20-Microsoft-Azure-Cloud-and-Consentua/2%20(1).jpg" alt="A desk with a laptop and papers" width="200px" height="200px">
Once we have made the strategic decision to use Azure it is necessary to maximise this investment. Azure gives us lots of flexibility in terms of where a service is geographically located.    

The use of resource groups allows for easier accounting and management. Managing cost is an important aspect of any responsible application service provider. The resource group also allows us to consolidate common functions (systems management) and yet offer separate landscapes for development & test.  This improves security and enforces best practice code and release management.  

Scaling up and down as demand dictates is another feature Consentua relies on. This again helps Consentua contain cost, whilst maximising the processing demand (as this drives revenue). Alongside a comprehensive reporting (live stream analytics) and systems availability/alerting capability.

## Consentua on Azure
<img class="img-right" src="https://github.com/Consentua/blog/blob/master/public/post_imgs/2018-08-20-Microsoft-Azure-Cloud-and-Consentua/3.png" alt="Map of Europe in multiple colours" width="280px" height="200px">
The Consentua service on Azure is hosted in Western Europe with the production service multi-redundant across datacenters. The development and test landscapes run in their own dedicated resource groups. Europe was chosen simply as this is where the majority of our customers are located. 

Offering continuous integration for new releases is typical feature of code management on cloud hosted services. Consentua is no different. Again, Azure and Consentua have a good fit here in terms of capability offered and requirement demanded. 

The production service when it gets busier requires more resources to be dynamically allocated.   This is also used when we conduct performance testing. The ability to quickly mimic the production set up and work load is another plus point for the Azure platform.

## What next?
The plan is that Consentua will eventually integrate natively with Microsoft and partner provided tools, applications and services.    
To know more about Consentua go to <a href="www.consentua.com">Consentua · Consent Choice and Control</a>
