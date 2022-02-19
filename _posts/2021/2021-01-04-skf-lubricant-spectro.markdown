---
layout: post
title: Lubrication spectroscopy
categories: coop
excerpt: ""
tags:
  - cooperation
  - environimagine
  - seges
image: avg-trmm-3b43v7-precip_3B43_trmm_2001-2016_A
date: '2020-06-01 11:27'
modified: '2020-06-01 T18:17:25.000Z'
comments: true
share: true
---

Amazon literature on spectroscopy:
https://www.amazon.se/s?k=spektrometer&page=2&qid=1612502274&ref=sr_pg_1

Benjamin R. Wiesent, Daniel G. Dorigo, Özlem Şimşek and Alexander W. Koch
Miniaturisierte Infrarot-Spektrometer zur Ölzustandsüberwachung in Offshore-Windkraftgetrieben
Oldenbourg Wissenschaftsverlag GmbH | 2012
DOI: https://doi.org/10.1524/teme.2012.0190

https://www.degruyter.com/document/doi/10.1524/teme.2012.0190/html

https://www.researchgate.net/publication/274360105_Miniaturisierte_Infrarot-Spektrometer_zur_Olzustandsuberwachung_in_Offshore-Windkraftgetrieben

MicroNIR

https://antech.ie/micronir-pro-viavi-nir/


Online spectral library:

http://www.ir-spectra.com/2012/indexes/index_d.htm

### Bearing lubrictants

Bearing failures are primarily caused by lubrication related issues, including inadequate/improper lubrication, and lubrication contamination. Also other major causes of bearing failure, including overload, and improper handling and installation leave traces as wear debris in the lubricants.

Monitoring the status of the lubricants is key to sustaining bearing functions and life cycles. One method is to use infrared light to estimate the abundance of different molecules indicate of degradation, wear and tear, and other contaminants. The spectral analysis of the infrared light for determining lubricant health and status requires Short Wave InfraRed (SWIR) wavelengths (around 2000 to 3000 nano metres). The more common (older) spectral sensors able to register SWIR data require cooling, but recent inventions have led to alternative sensors that operate at room temperature. The standard spectral method applied for lubricant testing is interferometry combined with a Fourier transformation. In interferometry the light source is split into a sample and a reference, and requires a setup of mirrors with extremely exact positions. Also the sample to analyse must be exactly positioned which is complex to achieve with high viscosity fluids like grease. The Fourier transformation is applied to enhance the information and facilitate the interpretation. Applying spectral analysis of lubricants with the present solution is thus rather expensive, cumbersome, and requires experts.

A new generation of miniaturised spectral sensors, including for SWIR wavelengths, as well as for interferometry, are now becoming commercially available. Combined with communication solutions from the development of Internet of Things (IoT), continuous spectral monitoring with devices the size of a mobile phone are emerging. xSpectre AB was started for exploring this market. We have developed prototypes of Visible and Near InfraRed (350 - 1100 nm) handheld spectrometers that are operated by a smartphone. The central part of xSpectre's development, however is a geometric-mathematical method for interpreting and modelling spectral data.

A fast screening of the literature on spectral properties of healthy and degraded lubricants indicate that the spectral signal changes significantly in the SWIR region with lubricant degradation and contamination. The application of Fourier transform infrared (FTIR) spectroscopy also shows that it is possible to use spectroscopy for determining lubricant quality. Requirements regarding spectral resolution (i.e. the width and number of wavelengths that need to be measured) for retrieving relevant information is unclear. The mathematical models, or "Decision Systems" that translate the spectral signal to information that is interpreted by the human operator are proprietary, held by the companies that offer FTIR spectroscopy of lubricants. With xSpectre's solution defining models that translate spectral properties to relevant information is facilitated and also easier to interpret in the graphical interface. While we are in the process of applying of a patent for the method as such, any model developed from the system can both be appleid outside of our solution as well as being kept as an Intellectual Property by the part developing the model. We, however, have no explicit experience with spectroscopy of lubricants, neither with developing our own SWIR spectrometers. The parts required for developing both an FTIR based as well as an ordinary reflectance SWIR spectroscopy solution with automated (IoT style) communication are commercially available.

### Lubricant analysis

[JASCO](https://jascoinc.com/applications/analysis-of-the-deterioration-of-industrial-grease-using-atr/)

### FTIR spectral analysers

[Hamamatsu FTIR engine](https://www.hamamatsu.com/eu/en/product/optical-sensors/spectrometers/ftir_engine/index.html)

[Hamamatsu miniature SWIR spectrometer, C14486GA](https://www.hamamatsu.com/eu/en/product/type/C14486GA/index.html) at 950 to 1750 nm and 256 bands.

[Hamamatsu C15511-01 spectrometer module with built-in Michelson optical interferometer](https://www.hamamatsu.com/eu/en/product/type/C15511-01/index.html)

[Overview over Hamamatus's InGaAs sensors](https://www.optecinc.com/astronomy/catalog/ssp/pdf/hamamatsu_g5851_series_ingaas_kird0005e.pdf)

### SWIR photodiods

The simplest is perhaps this [16 array diode from [Hamamatsu](https://www.hamamatsu.com/resources/pdf/ssd/g7150_g7151-16_kird1043e.pdf), but it only reaches 1750 nm.

[Polytech linear InGaAs photo arrays](https://www.polytec.com/eu/optical-systems/products/cameras-camera-systems/ir-cameras-arrays/swir-ingaas-photodiode-line-arrays/), with sensitivity up to 2600 nm.

[Pyreos](https://pyreos.com) is that company in Scotland that produces a new generation of SWIR sensors, including [linear arrays](https://pyreos.com/linear-arrays/). At least you can get the price of these from [Mouser](https://www.mouser.se/Pyreos/_/N-1y8tyiv?No=25&qty=1).

### Chinese alternative

I have found [Hasun optoelectronics HK co., LTD](http://www.hasunopto.com) that offer a range of sensors.
- [Photodiode arrays](http://www.hasunopto.com/supplier-210741-photodiode-array)
- [miniature spectroemters](http://hasunoptokr.sell.everychina.com/p-110163030-c14486ga-c14214ma-c12880ma-c14384ma-01-c11708ma-c10988ma-01-c13053ma-c12666ma.html)

### Resources

[Borin, A. and Poppi, R., 2004. Multivariate quality control of lubricating oils using Fourier transform infrared spectroscopy, Journal of the Brazilian Chemical Society](http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0103-50532004000400020)

[Wright, W., 2015, Benefits of Fourier transform infrared (FTIR) spectroscopy Oil Analysis, Machinery Lubrication](https://www.machinerylubrication.com/Read/30205/ftir-oil-analysis).

[Bots, S., 2013, Grease Analysis: Early Warning System for Failures and Proactive Maintenance Tool, Machinery Lubrication](https://www.machinerylubrication.com/Read/29284/grease-analysis-system)
