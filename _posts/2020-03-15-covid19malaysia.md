---
title: Trying to model the spread Covid-19
subtitle: Logistic modelling and prediction of Covid-19 based on Malaysian data
bigimg: /img/banners/big_epi_image.jpg
---

With news outlets and my social media feed constantly being filled with news and updated data on the number of cases of Covid-19, that was not what I really wanted to know. I wanted to know when this epidemic would end or at least slowdown. So I decided to do some research into this and perhaps implement a simple model of my own to predict or have a ballpark value when we would get zero cases based on the Malaysian data.

Additionally, my first reaction with Malaysia moving into what is called a "Movemenet Control Order" for a duration of 2 weeks (and with people already complaining how long this is), is 2 weeks enough? 

Modelling epidemics is no easy task, especiallly for a disease like Covid-19 wehre the rate of transmission seems to be relatively high casued by the possibilty of asymptomatic cases and the long time it takes for symptoms to develop (virus incubation period). These factors make the job of modelling the spread of the disease even more difficult than it already is considering  the general uncertainties there are in epidemiology. 

I have read about the SIR model which I will probably look more into in a future document because it seems pretty cool and is more realistic. 

I decided to approach this in a very simple and starightforward matter, just with the use of the number of new cases daily. I did this by fitting the data we have to well mathematical functions. We can then use this model to predict the number of cases we would get over the next few days and eventually when we would end up with zero number of new cases. 

The logistic model is validated and known to be a very simple first pass for a model of an epidemic. The figure below shows how this looks like. As you can imagine, there are many flaws and unaccounted uncertainties and situations in using a logistic model so the disclaimer fr the predictions here is obvious. DISCLAIMER: I am not a epidemiologist or even close to being an expert in mathematical modelling. 

Note: Updated as of 29/3/2020
![](/img/posts/covid19malaysia_logisticmodel_280320.png)

Of course, this is definitely not the end of it in Malaysia. With the rest of the world sturggling to contain this virus, there is bound tobe imported cases and we risk the arrival of another outbreak if policies and regulations are not setup after the MCO or even when we have the first day with no new cases. 
