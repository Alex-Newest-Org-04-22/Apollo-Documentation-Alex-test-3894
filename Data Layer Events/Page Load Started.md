# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_view",
  "detailed_event": "Page Load Started",
    "page_data": {
        "affiliate_id": "<affiliate_id>",
        "breadcrumb": "<breadcrumb>",
        "country": "<country>",
        "day_of_week": "<day_of_week>",
        "email_message_id": "<email_message_id>",
        "email_message_link_id": "<email_message_link_id>",
        "email_recipient_id": "<email_recipient_id>",
        "language": "<language>",
        "owner": "<owner>",
        "page_location": "<page_location>"
    },
    "user_data": {
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.affiliate_id|string|Captures the ID of the affiliate related to a given event||||||||
|page_data.breadcrumb|string|A delimited list of hierarchical sections that describe the current page's location within the navigation of the site.|Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|page_data.country|string|The country the site is associated with.||||||||
|page_data.day_of_week|string|The day of the week the activity occured.||||||||
|page_data.email_message_id|string|Captures the ID associated with a given email message||||||||
|page_data.email_message_link_id|string|Captures the ID associated with the specific link within an email||||||||
|page_data.email_recipient_id|string|Captures the ID of the recipient to whom an email was sent||||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_data.owner|string|Captures the licensee or owner of content \(i.e. HBO\).|XX product management, marketing, vendor name|||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||




