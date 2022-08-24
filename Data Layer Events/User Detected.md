# User Detected

### 

## Javascript Code
```js
window.appEventDataE = window.appEventDataE || [];
appEventDataE.push({
  "event": "User Detected",
    "user": {
        "affiliateCustomerID": "<affiliateCustomerID>",
        "anonymousUserID": "<anonymousUserID>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.affiliateCustomerID|string|The user ID of user who arrived at the website via a third party partner.||||||||
|user.anonymousUserID|string|When a user is not logged in,, this captures an anonymous user id.||||||||




