---
layout: post
title: Smart farming with spectral data
categories: venture
excerpt: "Next generation perception for smart farming adjusted to the local landscape with handheld spectrometer and miniaturised sensors connected to mobile phone."
tags:
  - market
  - internet of things
  - agriculture
image: avg-trmm-3b43v7-precip_3B43_trmm_2001-2016_A
date: '2020-02-26 11:27'
modified: '2020-02-26 T18:17:25.000Z'
comments: true
share: true
---

### Background

Smart farming, also called Agriculture 4.0 or digital farming, is developing beyond location based precision farming. Smart farming is context aware, utilises Big Data and Machine Learning (ML), and Information and Communication Technologies (ICT) inherited from Internet of Things (IoT) technology. Smart farming is generally considered to stand on six legs:

- Sensing (perception and positioning) technology
- Network (gateway) ICT
- Hard- and software integration (e.g. fog and cloud computing)
- Processing (e.g. standardised protocols)
- Analysis (e.g. ML)
- Visualisation and actuation

<figure>
<img src="../../images/IoT_architecture.png">
<figcaption> Figure 1. Architecture of Smart farming with spectral data.</figcaption>
</figure>

One could say that smart farming is the application of IoT in agriculture (Ag-IoT), driven by the miniaturisation and efficiency improvements in sensing technology and connectivity (figure 1). But smart farming demands more than IoT, it needs to consider unpredictable environmental conditions, tugging on the sensors and the ICT hardware, and it must be spatially aware at different scales. Smart farming is the force behind the third agricultural revolution, with initiatives ranging from reaching out to subsistence farmers in Africa to billion dollar research projects in Europe and elsewhere.

The market for smart agriculture doubles in five years, and is estimated to reach 23 billion USD in 2022 ([statista](https://www.statista.com/statistics/720062/market-value-smart-agriculture-worldwide/)).

### Initiatives

This is an arbitrary list of Smart farming initiatives and projects with private/public funding. The list only covers initiatives and projects where the funding or business is related to Sweden or the European Union.

#### Internet of Food & Farm 2020 (IoF2020)

IoF2020 is a research initiative financed through [Horizon 2020 Industrial Leadership](https://www.iof2020.eu), focusing on IoT technologies for supporting Europe's food and farming industry.

####  Alliance for Internet of Things Innovation (AIOTI)

[AIOTI](https://aioti.eu/) is a European initiative for strengthening IoT including for standardisation.

#### smart AKIS

[smart AKIS](https://www.smart-akis.com) was a European network trying to make Smart Farming more accessible for use in practice, providing links between research and practice. The project ended 31 dec 2019, but the accumulated knowledge is available online.

#### SmartAgriHubs

[SmartAgriHubs](https://smartagrihubs.eu), "unleashing the innovation potential for the digital transformationof the European Agrifood Sector" is funded by EU's Horizon 2020. SmartAgriHubs is organised with Regional Cluster and national research centres responsible for flagship experiments, of which some are: Satellite based spectral mapping (UK and Ireland); IoT based information (France); mobile app based precision agriculture (Austria); drones for mapping and fertiliser optimisation (Poland); Sensing and ML for crop disease detection and irrigation management with IoT (Spain);  machinery attached sensing for vineyard precision farming (Italy); mapping of filed grown vegetables (Greece).

#### Precision cultivation for sustainable food production

This is a Swedish research project under [Research Institute of Sweden (RISE)](https://www.ri.se/en/our-stories/precision-cultivation-sustainable-food-production). The project focus is on adapting cultivation to conditions in the field using sensors and IoT technology. The aim is to improve yields by up to 20% without increasing climate gas emissions or nutrient leakage.

#### Digitalised agriculture

[Testbed for digitalised agriculture](https://www.ri.se/en/what-we-do/projects/testbed-digitalised-agriculture) is another RISE project. The purpose of the testbed is to create an arena for collaboration on new technology for agriculture. The project is financed by [Vinnova](https://www.vinnova.se/en/) and is a private-public cooperation.

#### WEFARM

[Wefarm](https://wefarm.co) is a free peer-to-peer service that enables farmers to share information via SMS, without the internet and without having to leave their farm. Wefarm is supported by [Zennström philanthropies](https://www.zennstrom.org).

#### IGNITIA

[Ignitia](https://www.ignitia.se) has developed a high-resolution tropical weather forecast model raising accuracy from 39% to 84%, which means that small scale farmers in the tropical regions can plan their farming a lot better. Better planning improves their farming yields and puts food on the table. Ignitia is supported by [Zennström philanthropies](https://www.zennstrom.org).

### Barriers

Despite the public and private initiatives, Smart farming is only affecting parts of the chain from planting to food on the table. Identified barriers relate both to lack of acceptance by different stakeholders in the productions chain, system designs originating from earlier scientific models, technological shortcomings and lack of standards. These barriers are clearly linked to each other, causing investors (farmers) to be reluctant towards the initially high costs for establishing Smart farming infrastructure with a considerable risk for becoming obsolete.

Comparing identified challenges towards smart farming, sensor and communication efficiency (power and data transfer, standardisation) are at the top, but the fastest growing concern regards data analysis [(Villa-Henriksen et al., 2020)](https://www.sciencedirect.com/science/article/pii/S1537511020300039). The tools for reliant data analysis and visualising results and opportunities to farmers and other managers and decision makers are lacking. This erodes the trust in smart farming. The dual problems of model 1) formulation and accuracy, and 2) visualising results and opportunities, is at the core of the systems that I have developed. But I need to marry my system with modern ICT and IoT technology to assure data transfer, information access and a modern app interface.

### Opportunity

Pushing the third agriculture revolution depends on trust in the technology and a lower financial threshold for testing smart farming and its financial benefits. Especially for small-scale farmers. Smart farming requires better integration from sensors to the app informing the user on alternatives, but also new solutions for context-based co-operation across both space, time and the production chain.

We propose a five pronged strategy extending the IoT based Smart farming with locally calibrated spectral libraries and satellite images (figure 2):

- A handheld and mobile phone connected multi-purpose sensor centred around a spectrometer and with miniaturised and exchangeable sensors for temperature, humidity and soil moisture, pH, conductivity and leaf area.
- Network solution based on BLE or LoRa enabled microcontrollers and smart phones, where the smartphones also act as middleware and for visualisation of result and information of alternative actions.
- Peer-cognition with sharing data, information and know-how (like in the [We Farm farmer-to-farmer digital network](https://wefarm.co)) allowing build-up of local and context relevant datasets and spectral libraries, scientific ML models and better predictions of risks and opportunities; a smarter "business logic" combining local knowledge and data with ML.
- Upscaling from sensor observation to landscape maps using satellite images and spectral libraries for local or regional conditions (soil, bedrock, crop types, moisture).
- Modern app with optimised efficiency utilising both fog (middleware) and cloud based computing and with interactive graphical user interface; localised scientific prediction models (like for instance [Ignitia Tropical Weather Forecasting](https://www.ignitia.se)).

<figure>
<img src="../../images/geoimagine_architecture.png">
<figcaption> Figure 2. Architecture of Smart farming with spectral data extended with landscape level estimates of biophysical conditions using spectral libraries and satellite images.</figcaption>
</figure>

The handheld spectrometer is at the core of the proposed venture; it can be used as a stand-alone IoT multi-sensor. Equally important, it also allows the building of spectral libraries \- libraries that correlate spectral properties to physical, chemical and biological properties. Once the library is built, the spectral sensor alone can be used for estimating soil, water and crop conditions. Further, the spectral library can be used for locally adjusted interpretation of satellite or drone imagery, translating the point collected sensor data to a full coverage landscape map. Freely available satellite imagery can be used for monitoring at spatial resolutions down to 10 m, commercial satellite imagery or images from drones can deliver more detailed images.

We envision that the proposed strategy would open up for a very large cohort of small and middle scale farmers to step in to smart farming, at an investment cost of around 100 USD, excluding the smartphone and subscription costs. The investment is rather in collecting the spectral library. A library which value does not depend on the technology itself.

## Resources

[Villa-Henriksen, A., Edwards, G.T., Pesonen, L.A., Green, O. and Sørensen, C.A.G., 2020. Internet of Things in arable farming: Implementation, applications, challenges and potential. Biosystems Engineering, 191, pp.60-84.](https://doi.org/10.1016/j.biosystemseng.2019.12.013).

[Introducing Internet of Food & Fram 2020](https://www.iof2020.eu/about)

[Alliance for Internet of Things Innovation AIOTI](https://aioti.eu/)

[We Farm farmer-to-farmer digital network](https://wefarm.co)

[Ignitia Tropical Weather Forecasting](https://www.ignitia.se)

[Testbed for digitalised agriculture](https://www.ri.se/en/what-we-do/projects/testbed-digitalised-agriculture)

[Precision cultivation for sustainable food production](https://www.ri.se/en/what-we-do/projects/testbed-digitalised-agriculture)

[Alliance for Internet of Things Innovation (AIOTI)](https://aioti.eu/)

[smart AKIS](https://www.smart-akis.com)
