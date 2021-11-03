# Vendor Management

Many types of vendors like Desludging Operators (DSOs), Self-Help Groups (SHGs), Treatment Agency, Testing Laboratories, etc can be managed on the platform.

### Background

The urban local body&#x20;

### Common Use Cases

* A vendor can have different types of employees or no employees, with the same or different permissions.
* A vendor can register and update their information
* A vendor can o service requests

### Roles and Actions

### Login and Profile

#### Personal Protection Information

### Workflow

### Notifications

### Vendor (User) Registry and APIs

{% swagger method="get" path="" baseUrl="/fsm/v1/create_vendor" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" required="true" name="type" %}
Type of vendor (DSO, Lab, SHG,..)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="400: Bad Request" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

#### Error Codes

