# User Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "detect_user",
  "detailed_event": "User Detected",
    "user_data": {
        "affiliate_customer_id": "<affiliate_customer_id>",
        "anonymous_user_id": "<anonymous_user_id>",
        "employee_id": "<employee_id>",
        "organization_id": "<organization_id>",
        "user_age_or_birth_year": "<user_age_or_birth_year>",
        "user_city": "<user_city>",
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user_data.affiliate_customer_id|string|The user ID of user who arrived at the website via a third party partner.||||||||
|user_data.anonymous_user_id|string|When a user is not logged in, this captures an anonymous user ID.||||||||
|user_data.employee_id|string|Captures the employee ID associated with website or mobile app traffic.|Gold, Bronze, Platinum, Diamond, Silver|||||||
|user_data.organization_id|string|Captures the user Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|user_data.user_age_or_birth_year|string|Captures the birth year or current age of the user.||||||||
|user_data.user_city|string|Captures the city associated with the user.||||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||




