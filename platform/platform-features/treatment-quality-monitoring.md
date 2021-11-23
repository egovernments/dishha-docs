# Treatment Quality Monitoring

### Context

With limited data available for STPs and FSTPs, only [578 of 1093 operational STPs](https://cpcb.nic.in/openpdffile.php?id=UmVwb3J0RmlsZXMvMTIyOF8xNjE1MTk2MzIyX21lZGlhcGhvdG85NTY0LnBkZg==) have complied treatment in 2020. The failure in compliance can be due to multiple reasons like lack of knowledge of treatment or disposal standards, expensive and infrequent lab tests, and several others listed [here](https://miro.com/app/board/o9J\_lbLj6ps=/?moveToWidget=3074457358634878411\&cot=14). Of these, we are focusing on the availability of the record-keeping of quality data.&#x20;

To ensure compliance of treatment at STPs and FSTPs, it is important to know the effluent and biosolids quality on a regular and, preferably, high-frequency basis so that any deviation from the desirable state can be addressed quickly.

The quality data can be collected through one or more means. For instance, laboratory tests, manual entry through calibration tools, IoT sensors are different sources for the data.&#x20;

#### Effluent Parameters

| Parameter                        | Value Range                                                 | Location                                                                                                                                                                                                                                                                                                                                         |
| -------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| pH                               | 6.5 - 9                                                     | Anywhere in the country                                                                                                                                                                                                                                                                                                                          |
| Bio-Chemical Oxygen Demand (BOD) | <ul><li>20 mg/l</li><li>30 mg/l</li></ul>                   | <ul><li>Metro Cities*, all State Capitals except in the State of Arunachal Pradesh, Assam, Manipur, Meghalaya Mizoram, Nagaland, Tripura Sikkim, Himachal Pradesh, Uttarakhand, Jammu and Kashmir and Union territory of Andaman and Nicobar Islands, Dadar and Nagar Haveli Daman and Diu and Lakshadweep</li><li>Other areas/regions</li></ul> |
| Total Suspended Solids (TSS)     | <ul><li>&#x3C; 50 mg/l</li><li>&#x3C; 100 mg/l ()</li></ul> | <ul><li>Metro Cities*, all State Capitals except in the State of Arunachal Pradesh, Assam, Manipur, Meghalaya Mizoram, Nagaland, Tripura Sikkim, Himachal Pradesh, Uttarakhand, Jammu and Kashmir and Union territory of Andaman and Nicobar Islands, Dadar and Nagar Haveli Daman and Diu and Lakshadweep</li><li>Other areas/regions</li></ul> |
| Faecal Coliform                  | < 1000 MPN/100ml                                            | Anywhere in the country                                                                                                                                                                                                                                                                                                                          |

{% hint style="info" %}
* \*Metro Cities are Mumbai, Delhi, Kolkata, Chennai, Bengaluru, Hyderabad, Ahmedabad and Pune.
* Reference: [Ministry of Environment, Forest, and Climate Change October 13, 2017 Notification ](http://ismenvis.nic.in/database/notification\_13th\_oct\_2017-gsr1265e\_15634.aspx)
{% endhint %}

There are three possible modes of fetching this information.

1. Laboratory Reports
2. Manual Log (measuring through calibration tools/sensors)
3. IoT-based Sensors

Note: There are no IoT-based sensors for measuring Faecal Coliform directly.

#### Biosolids Parameters

{% hint style="warning" %}
Regulations for biosolids are unclear - we currently don't have a definitive GoI-notified standard for faecal sludge-derived biosolids. Still, from what we know, a draft has been in the works for a few months. In the interim, the Advisory and Primer on FSSM (along with the CPHEEO Manual) recommended US EPA Class A Biosolids criteria (looking at E Coli/F Coli, Salmonella, Helminth Eggs). The National Policy on FSSM issued after all these three makes mention of SWM Rules, 2016, as the guiding document for processed sludge quality
{% endhint %}

To design for the future, we enable the stakeholders to know about the important parameters based on the policy and treatment type they select during a one-time setup. The list of parameters look like this:

| Parameter                                        | Value Range                                                                | Policy                     |
| ------------------------------------------------ | -------------------------------------------------------------------------- | -------------------------- |
| Faecal Coliform                                  | <ul><li>1000 MPN/ dry gram solids</li></ul>                                | US EPA Class A (pathogens) |
| Salmonella sp                                    | <ul><li>3 MPN per 4 grams of total dry solids</li></ul>                    | US EPA Class A (pathogens) |
| Arsenic                                          | <ul><li>10 mg/Kg</li></ul>                                                 | SWM Rules 2016             |
| Cadmium                                          | <ul><li>5 mg/Kg</li></ul>                                                  | SWM Rules 2016             |
| Chromium                                         | <ul><li>50 mg/Kg</li></ul>                                                 | SWM Rules 2016             |
| Copper                                           | <ul><li>300</li></ul>                                                      | SWM Rules 2016             |
| Lead                                             | <ul><li>100</li></ul>                                                      | SWM Rules 2016             |
| Mercury                                          | <ul><li>0.15</li></ul>                                                     | SWM Rules 2016             |
| Nickel                                           | <ul><li>50</li></ul>                                                       | SWM Rules 2016             |
| Zinc                                             | <ul><li>1000</li></ul>                                                     | SWM Rules 2016             |
| C/N Ratio                                        | <ul><li>&#x3C; 20</li></ul>                                                | SWM Rules 2016             |
| pH                                               | <ul><li>6.5 - 7.5</li></ul>                                                | SWM Rules 2016             |
| Moisture, percent by weight, maximum             | <ul><li>15.0 - 25.0 </li></ul>                                             | SWM Rules 2016             |
| Bulk Density                                     | <ul><li>&#x3C; 1.0 g/ cm^3</li></ul>                                       | SWM Rules 2016             |
| Total Organic Carbon, percent by weight, minimum | <ul><li>12.0</li></ul>                                                     | SWM Rules 2016             |
| Total Nitrogen, percent by weight, minimum       | <ul><li>0.8</li></ul>                                                      | SWM Rules 2016             |
| Total Phosphate, percent by weight, minimum      | <ul><li>0.4</li></ul>                                                      | SWM Rules 2016             |
| Total Potassium, percent by weight, minimum      | <ul><li>0.4</li></ul>                                                      | SWM Rules 2016             |
| Color                                            | <ul><li>Dark brown to Black</li></ul>                                      | SWM Rules 2016             |
| Odour                                            | <ul><li>Absence of foul odour</li></ul>                                    | SWM Rules 2016             |
| Particle size                                    | <ul><li>Minimum 90% material should pass through 4.0 mm IS sieve</li></ul> | SWM Rules 2016             |
| Conductivity, not more than                      | 4.0                                                                        | SWM Rules 2016             |

{% hint style="info" %}
Reference: [Plain English Guide Part 503 Biosolids Rule](https://www.epa.gov/sites/default/files/2018-12/documents/plain-english-guide-part503-biosolids-rule.pdf), [SWM Rules 2016](https://moef.gov.in/wp-content/uploads/2017/08/SWM-2016-English.pdf)
{% endhint %}

{% hint style="warning" %}
Of all these parameters, only pH and Moisture can be monitored through IoT sensors. However, biosolids quality monitoring for other parameters using IoT is yet to be explored.
{% endhint %}

#### Frequency of Measurement

Based on SLA and the parameter, the frequency of measuring can differ from a few minutes (if IoT) to several days.&#x20;

#### Process Flow

To understand the context of treatment monitoring, we take a look at what happens on the ground with various monitoring avenues (lab reports, sensors) in play. We assume that FSTPs have at least one of the monitoring mechanisms.

![Process flow for treatment monitoring](<../../.gitbook/assets/Screenshot 2021-11-23 at 9.25.42 AM.png>)

### Platform Scope

#### Summary

Real-time monitoring using IoT sensors OR Laboratory testing enables the stakeholders to be informed about the compliance status of the treatment plants. The samples from several locations in the treatment flow help to drill down the compliance problem to a particular step in treatment technology. While platform enables capturing treatment monitoring data by defining the required registries and services, the exemplar application provides below functions:-&#x20;

* Create Data:&#x20;
  * Manual input to enter readings for quality parameters using calibration tools or laboratory reports
  * IoT input for monitoring parameters
* Read Data:
  * Visualization to analyze the quality over a period of time
* Modify Data:
  * We do not allow modification of quality parameters unless it is a manual mistake
* Delete Data:
  * We do not delete the data

#### Data Layer

Coming soon :hourglass:

#### Services Layer

Coming soon :hourglass:

### On-boarding&#x20;

#### One-time Configuration

1. Treatment Technology
2. Selection of Parameters
3. Frequency of Update

#### Sensor Support

Coming soon :hourglass:

###

