# Treatment Quality Monitoring

### Context

With limited data available for STPs and FSTPs, only [578 of 1093 operational STPs](https://cpcb.nic.in/openpdffile.php?id=UmVwb3J0RmlsZXMvMTIyOF8xNjE1MTk2MzIyX21lZGlhcGhvdG85NTY0LnBkZg==) have complied treatment in 2020. The failure in compliance can be due to multiple reasons like lack of knowledge of treatment or disposal standards, expensive and infrequent lab tests, and several others listed [here](https://miro.com/app/board/o9J\_lbLj6ps=/?moveToWidget=3074457358634878411\&cot=14). Of these, we are focusing on the availability on the record-keeping of quality data.&#x20;

To ensure compliance of treatment at STPs and FSTPs, it is important to know the effluent and biosolids quality on a regular and, preferably, high-frequency basis so that any deviation from the desirable state can be addressed quickly.

The quality data can be collected through one or more means. For instance, laboratory tests, manual entry through calibration tools, IoT sensors are different sources for the data.&#x20;

#### Effluent Parameters

| Parameters                       | Value Range                                                                                                                                                                                                                                                                                                                                                                   | Details                                                                                                                                                                         |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| pH                               | 6.5 - 9                                                                                                                                                                                                                                                                                                                                                                       | <p>Can be fetched through manual entry, laborartory reports, and pH sensors. </p><p></p><p>The frequency of data point updating could be as low as seconds, days, or months</p> |
| Bio-Chemical Oxygen Demand (BOD) | <p>20 mg/l (Metro Cities*, all State Capitals except in the State of Arunachal Pradesh, Assam, Manipur, Meghalaya Mizoram, Nagaland, Tripura Sikkim, Himachal Pradesh, Uttarakhand, Jammu and Kashmir and Union territory of Andaman and Nicobar Islands, Dadar and Nagar Haveli Daman and Diu and Lakshadweep)</p><p></p><p>30 mg/l (Other areas/regions) </p>               | <p>Can be fetched through laborartory reports and BoD sensors</p><p></p><p>The frequency of data point updating could be as low as seconds, days, or months</p>                 |
| Total Suspended Solids (TSS)     | <p>&#x3C; 50 mg/l (Metro Cities*, all State Capitals except in the State of Arunachal Pradesh, Assam, Manipur, Meghalaya Mizoram, Nagaland, Tripura Sikkim, Himachal Pradesh, Uttarakhand, Jammu and Kashmir and Union territory of Andaman and Nicobar Islands, Dadar and Nagar Haveli Daman and Diu and Lakshadweep)</p><p></p><p>&#x3C; 100 mg/l (Other areas/regions)</p> | <p>Can be fetched through laborartory reports and pH sensors</p><p></p><p>The frequency of data point updating could be as low as seconds, days, or months</p>                  |
| Faecal Coliform                  | < 1000 mg/l                                                                                                                                                                                                                                                                                                                                                                   | <p>Can be fetched through laboraroty reports</p><p></p><p>The frequency of data point updating could be days or months</p>                                                      |

{% hint style="info" %}
Reference: [Ministry of Environment, Forest, and Climate Change October 13, 2017 Notification ](http://ismenvis.nic.in/database/notification\_13th\_oct\_2017-gsr1265e\_15634.aspx)
{% endhint %}

#### Biosolids Parameters

coming soon

### Process



### Real-time Monitoring

Real-time monitoring using IoT sensors enables the stakeholders to be informed about the compliance status of the treatment plants. The sensors embedded at several locations in the treatment flow help to drill down the compliance problem to a particular step in treatment technology.

{% swagger method="get" path="effluent_quality" baseUrl="/" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" %}

{% endswagger-parameter %}
{% endswagger %}

{% swagger method="put" path="" baseUrl="/effluent_quality" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" %}

{% endswagger-parameter %}
{% endswagger %}



#### Biosolids Monitoring

{% hint style="warning" %}
While effluent monitoring using IoT sensors has been around for a few years now, biosolids quality monitoring using IoT is still an upcoming development.

Besides, the biosolids' quality parameters for human waste are not standardized.
{% endhint %}

To design for the future, we enable the stakeholders to know about the important

### On-boarding&#x20;

#### Sensor Support

Coming soon :hourglass:

#### One-time Configuration

1. Treatment Technology
2. Frequency of Update



### Dashboards
