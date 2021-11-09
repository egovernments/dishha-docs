# Treatment Quality Monitoring

### Context

With limited data available for STPs and FSTPs, only [578 of 1093 operational STPs](https://cpcb.nic.in/openpdffile.php?id=UmVwb3J0RmlsZXMvMTIyOF8xNjE1MTk2MzIyX21lZGlhcGhvdG85NTY0LnBkZg==) have complied treatment in 2020. The failure in compliance can be due to multiple reasons like lack of knowledge of treatment or disposal standards, expensive and infrequent lab tests, and several others listed [here](https://miro.com/app/board/o9J\_lbLj6ps=/?moveToWidget=3074457358634878411\&cot=14). Of these, we are focusing on the availability on the record-keeping of quality data.&#x20;

To ensure compliance of treatment at STPs and FSTPs, it is important to know the effluent and biosolids quality on a regular and, preferably, high-frequency basis so that any deviation from the desirable state can be addressed quickly.

The quality data can be collected through one or more means. For instance, laboratory tests, manual entry through calibration tools, IoT sensors are different sources for the data. Further, laboratory tests,&#x20;

### Real-time Monitoring

Real-time monitoring using IoT sensors enables the stakeholders to be informed about the compliance status of the treatment plants. The sensors embedded at several locations in the treatment flow help to drill down the compliance problem to a particular step in treatment technology.

#### Effluent Monitoring

The list of mandatory parameters enabled on the platform are:

1. pH
2. Temperature
3. Moisture
4. TSS (Total Suspended Solids)
5. Faecal Coliform
6. BOD (Biological Oxygen Demand)

{% hint style="info" %}
To know more about the quality parameters DISHHA supports, please refer to the [Designated Best Use of Water Quality Criteria - CPCB](https://cpcb.nic.in/wqm/Designated\_Best\_Use\_Water\_Quality\_Criteria.pdf)
{% endhint %}



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

####

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
3.

### Dashboards
