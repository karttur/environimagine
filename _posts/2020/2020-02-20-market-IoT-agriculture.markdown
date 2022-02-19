---
layout: post
title: Market for smart agriculture
categories: market
excerpt: "By 2022 the smart agriculture market will be 25 billion USD"
tags:
  - market
  - internet of things
  - agriculture
image: avg-trmm-3b43v7-precip_3B43_trmm_2001-2016_A
date: '2020-02-20 11:27'
modified: '2020-02-20 T18:17:25.000Z'
comments: true
share: true
---

### Introduction

[According to statista](https://www.statista.com/statistics/720062/market-value-smart-agriculture-worldwide/), the market for smart agriculture doubles in five years, and will reach 23 billion USD in 2022.

Smart Farming, also called Agriculture 4.0 or digitalfarming. is developing beyond the modern concept of precision agriculture, which bases its management practices on spatial measurements largely thanks to GlobalPositioning System (GPS) signals. Smart farming bases its management tasks also on spatial data but is enhanced with context-awareness and is activated by real-time events, improving the performance of hitherto precision agricultural resolutions, Additionally, Smart Farming usually incorporates intelligent services for applying and managing Information and Communication Technologies (ICT) in farming, and allows transverse integration throughout the whole agri-food chain in regards to food safety and traceability (Sundmaeker et al., 2016). IoT is therefore a key technology in smart farming since it ensures data flow between sensors and other devices, making it possible to add value to the obtained data by automatic processing, analysis and access, and this leads to more timely and cost-effective production and management effort on farms. Simultaneously, IoT enables the reduction of the inherent environmental impact by real-time reaction to alert events such as weed, pestor disease detection, weather or soil monitoring warnings, which allow for a reduction and adequate use of inputs such as agrochemicals or water.

application of IoT in agriculture, also called Ag-IoT

Several reviews have been done on IoT in agriculture in the relatively short time period in which publications about the subject have emerged (Ray, 2017; Stoces, Vanek, Masner,&Pavlı ́k,  2016;  Talavera  et  al.,  2017;  Tzounis,  Katsoulas,Bartzanas,&Kittas, 2017; Verdouw, 2016). In addition, review papers have been published with a focus on specific subjects related to IoT applied in agriculture, such as Big Data(Kamilaris, Kartakoullis,&Prenafeta-Boldu ́, 2017; Wolfertet al., 2017), modelling (O’Grady&O’Hare, 2017), Wireless Sensor Networks (WSN) (Jawad, Nordin, Gharghan, Jawad,&Ismail, 2017), food supply chain (Ramundo, Taisch,&Terzi,2016), Internet of Underground Things (Vuran, Salam, Wong,&Irmak, 2018), chemical wireless sensors (Kassal, Steinberg,&Murkovi, 2018), or Farm Management Information Systems(FMIS) (Fountas, Sørensen et al., 2015; Kaloxylos et al., 2012).

The number of IoT device installations in farms is expected to increase globally from 30 million installations in 2015 to 75 million in 2020. Furthermore, data points generated per day and farm are expected to increase from 190000 in 2014 to over half a million by 2020 (Meola, 2016). It was also estimated that by 2018 there would be 10 billion IoT devices employed in agriculture. However, the great amount of data generated is often unused or underutilised (Bennett, 2015), e.g.in countries like Denmark with a relative high ICT adoption in farms, in 2016 only 2e5% of farmers worked actively with the data generated (SEGES, 2016). Even if data usage is still relatively low, it is expected to increase rapidly (Bennett, 2015; Wolfert et al., 2017; World Bank, 2017)

The network layer communicates the data initially to an intermediary platform and eventually to the internet (cloud),and from there to, for example, employed actuators. When the data are transferred to the intermediary platform, it typically uses wireless communication technologies, for instance RFID, WSN with Zigbee, LoRa (Long Range), etc., and more recently Near-Field  Communication  (NFC)

The intermediary platform is normally an internet gateway located in the vicinity of the connected devices, also including sometimes a proxy server, where the data are collected and occasionally processed in order to send the in-formation further to the end user through the internet by the use of e.g. MQTT standards, or HTML or XMPP protocols.

Android and other smart devices can include GNSS and RGB camera sensors, and can relatively easily be programmed for computing data and displaying Graphical UserInterface (GUI) applications being able to straight forwardly update the software if necessary. In that manner, Android and similar smart devices are represented in all three IoT layers, i.e. sensing in the device layer, node or gateway in the network layer, and computing data and displaying GUI in the application layer. Furthermore, the automatic software updating possibilities of smart devices allow remote installation of updates with new functionalities, bug fixes, etc. and easily improve the interoperability of the system

Six main stages regarding data flow have been identified in the literaturere viewed:  sensing/perception,  communication/transport/transfer, storage, processing, analytics, and actuation and display (Fig. 4).

Monitoring

Sensors are used to monitor farming parameters such as
- leaf area index
- plant height
- leaf color and shape
- soil moisture
- irrigation water pH and salinity
- weather parameters (temp, rain, wind, radiation)

On-the-go sensors installed on vehicles and implements can be used for automated field mapping (Fountas, Sørensen et al., 2015),e.g. yield mapping used for later fertilisation planning (Lyle,Bryan,&Ostendorf, 2014), or soil mapping for site-specific amendment measures (Godwin&Miller, 2003; McBratney, Mendonc ̧a Santos, & Minasny, 2003). Remote sensing can also be used for mapping crop development (Khanal et al.,2017; N€asi et al., 2018; Viljanen et al., 2018), or soil texture and residue coverage (Khanal et al., 2017)

TAble 2 IoT application in arable farming - great table.

Different machine learning models have been employed, e.g. Artificial Neural Networks for forecasting maximum and minimum temperatures at field level (Aliev, 2018) or for estimating levels of phosphorus (P) in the soil (Estrada-Lopez,Castillo-Atoche, Vazquez-castillo,&Sanchez-Sinencio, 2018);support vector regression method for forecasting soil moisture (Goap et al., 2018) or plant disease detection (AashaNandhini, Hemalatha, Radha,&Indumathi, 2017); gradientboosting   for   predicting   irrigation   recommendations(Goldstein, Fink,&Meitin, 2018); Bayesian networks and random forest for frost prediction (Diedrichs, Bromberg,Dujovne, Brun-laguna,&Watteyne, 2018); multiple linearregression and random forest in estimating yield and fertil-isation requirements for forecasting harvest and fertilisationdates (Viljanen et al., 2018); or also for frost prediction usingfour different machine learning algorithms: decision tree, boosted tree, random forest, and regression (Moon, Kim, Zhang,&Woo, 2018).

Scientific modelling has also been employed for forecasting in an IoT context, e.g. soil moisture dynamics and contaminant migration forecasting using soil sensor data and precipitation forecasts for irrigation scheduling (Severinoet al., 2018); fungal disease forecast in winter wheat (ElJarroudi et al., 2017) and barley (M€ayr€a, Ruusunen, Jalli,Jauhiainen,&Leivisk€a, 2018); or forecasting field trafficabilityand  workability  for  field  operations  (Edwards,  White,Munkholm, Sørensen,&Lamande, 2016). These modelling tools have an important role in agriculture as they are conscientiously developed and validated by the scientific community, and can forecast events for which machine learning models are very limited. There is also considerable potential for integrating existing and acknowledged modelling tools such as the soil-crop-atmosphere system model DAISY (Abrahamsen&Hansen, 2000) or the soil erosion model RUSLE (Renard, Foster, Weesies,&Porter, 1991) into an IoT solution

Farm Management Information Systems (FMIS) most in use are designed in the 1980s by researchers for PC. Såklar funkar inte det!

Lack of data analysis the threshold that has grown the most fro all indicated challenges when asking around in alter years (Fig 5).

Often the investment for establishing an IoT-based solution is high and as such challenging for small-scale farmers, while larger farms can more easily acquire IoT-based technologies when investing in new equipment (Brewster et al.,2017). The uncertainty regarding required costs, e.g. fuel or water allocations, and selling prices of the product give little margin for many farmers for investing in new technologies(Higgins et al., 2017). Trust plays an important role when investing in IoT systems, and relieving the perceived risks by demonstrating the revenues from their adoption is essential (Ferrandez-Pastor et al., 2016; Jayashankar et al., 2018). Forexample, in Europe 70% of all fertilising and spraying ma-chinery is equipped with at least one precision agriculturetechnology, but only 25% of farmers actually use precisionagriculture components on their farms (Say, Keskin, Sehri,&Sekerli, 2017).

Technology providers need to increase the perceived value by demonstrating the financial return fromIoT in order to diminish the perceived risk of adoption many farmers have. Technology providers need also to provide robust tools that are aligned with farmer needs and practices in order to gain acceptance and trust of IoT technologies.

Organisational interoperability is a key element concerning scalability and flexibility (Serrano et al., 2015; Tzounis et al.,2017; Verdouw, 2016). Many of the systems described in the literature reviewed are centralised, closed, difficult to inte-grate in other existing platforms or difficult to implement onlarger scales, different farming systems or geographical areas.They are also challenging to integrate beyond the farm leve

European Union supported research and development efforts through multi-actor large-scale pilot projects, such as IoF2020 (Sundmaeker et al., 2016; Verdouw et al., 2017), AIOTI (Perez-Freire&Brillouet, 2015), SmartAgriFood (Kaloxyloset al., 2012), SMART AKIS (Djelveh&Bisevac, 2016), or morerecently SmartAgriHubs (Chatzikostas et al., 2019).

Comprimising between power and reach ZigBee and LoRa have been identified as appropriate candidates for many farming applications (Jawad et al., 2017).

The type of sensors that are mounted on vehicles and their implements is quite limited, being currently mainly camera-based (e.g.Midtibyet al., 2018; Steen, Villa-Henriksen, Therkildsen,&Green,2012).  Nevertheless,  there  is  for  example  potential  in employing sensors on the coulters of seed-drills for mapping soil properties (Nielsen et al., 2017), or other on-the-go sensors for mapping soil or crop variations (Peets et al., 2012

Sci-Dev-net
[Investing in agriculture](https://www.scidev.net/global/article-series.Hi-tech-farming.html?utm_medium=email&utm_source=SciDevNewsletter&utm_campaign=international+SciDev.Net+update:+30+December+2019&__cf_chl_jschl_tk__=ed683c0c37b5aedcffcfc90dbbef14c1d327d014-1582701707-0-AU4cPr2P-B8bFiRBHYrL6C3E5aUpdE8bHvLw5pv8Lxlk5AZuVbYwpw68sUEOoFWPBlqaqDlwC1CBbBEPX2Jud7bXwB06RSfwqsHSV7pXvZoeUlzuMq7f6F__2i4HoC5MAl3iT-v8BH6g88CNc-Kpl6PKkxLWOiQwbMbtqy87tEebTVQPoAR7brzSjK2wUO05vspui0dFlqr596yAycV7h7SKBtYBhYVX0mpcqKpGoRqjbjz_pZLgC88VOLvY4dfV20rrdC6q-ITDtoJjA9XNDJGCflXGAhbijWLo5dh8ezeDs6m0T8r9jgo6txFRVzQFItnYIVIdm_ewzP8LDvKjoRZvqgX25sJCXC3JclZ2egx5vN2hJv0FJfKlp9YmFCmEp8l1X1NgV1MCJnwijvtfLLN5IVFLoq5NRPdFnAfUXN6n1QXjmnfSIYtZGvsBPx7lb6LSV1vozyO-48IpiDRqi_yNqB72k0JnT-aSTLw9o7T3)

[INTERNET OF THINGS IN ARABLE FARMING SCIENTIFIC PAPER](https://www.iof2020.eu/latest/news/2020/iotarablepaper)

References

[Villa-Henriksen, A., Edwards, G.T., Pesonen, L.A., Green, O. and Sørensen, C.A.G., 2020. Internet of Things in arable farming: Implementation, applications, challenges and potential. Biosystems Engineering, 191, pp.60-84.](https://doi.org/10.1016/j.biosystemseng.2019.12.013).

[INTRODUCING INTERNET OF FOOD & FARM 2020](https://www.iof2020.eu/about)

IoT for all (2019): [Smart Farming: The Future of Agriculture](https://www.iotforall.com/soil-moisture-monitoring/)

IoT for all (2019): [How IoT Soil Condition Monitoring Is Empowering Farmers](https://www.iotforall.com/soil-moisture-monitoring/)
