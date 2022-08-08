---
title: "OutbreakFlow: Model-based Bayesian inference of disease outbreak dynamics with invertible neural networks and its application to the COVID-19 pandemics in Germany"
date: 2021-10-01
publishDate: 2022-05-31T17:48:50.272571Z
authors: ["Stefan T. Radev", "Frederik Graw", "Simiao Chen", "Nico T. Mutters", "Vanessa M. Eichel", "Till Bärnighausen", "Ullrich Köthe"]
publication_types: ["2"]
abstract: "Mathematical models in epidemiology are an indispensable tool to determine the dynamics and important characteristics of infectious diseases. Apart from their scientific merit, these models are often used to inform political decisions and interventional measures during an ongoing outbreak. However, reliably inferring the epidemical dynamics by connecting complex models to real data is still hard and requires either laborious manual parameter fitting or expensive optimization methods which have to be repeated from scratch for every application of a given model. In this work, we address this problem with a novel combination of epidemiological modeling with specialized neural networks. Our approach entails two computational phases: In an initial training phase, a mathematical model describing the epidemic is used as a coach for a neural network, which acquires global knowledge about the full range of possible disease dynamics. In the subsequent inference phase, the trained neural network processes the observed data of an actual outbreak and infers the parameters of the model in order to realistically reproduce the observed dynamics and reliably predict future progression. With its flexible framework, our simulation-based approach is applicable to a variety of epidemiological models. Moreover, since our method is fully Bayesian, it is designed to incorporate all available prior knowledge about plausible parameter values and returns complete joint posterior distributions over these parameters. Application of our method to the early Covid-19 outbreak phase in Germany demonstrates that we are able to obtain reliable probabilistic estimates for important disease characteristics, such as generation time, fraction of undetected infections, likelihood of transmission before symptom onset, and reporting delays using a very moderate amount of real-world observations."
featured: false
publication: "*PLOS Computational Biology*"
tags: ["COVID 19", "Disease dynamics", "Epidemiology", "Germany", "Machine learning", "Network analysis", "Neural networks", "Pandemics"]
url_pdf: "https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009472"
doi: "10.1371/journal.pcbi.1009472"
---

