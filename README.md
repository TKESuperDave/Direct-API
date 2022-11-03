# Direct-API
README forthcoming.

## Header

ClientId - Application Identifier also known as API Key
merchantId - Merchant Identifier
merchantkey - Merchant Key
nounce - Secure Random number used only once
timestamp - Epcoch time stamp
authorization - Authorization token, HMAC value of: verb + url + body + merchantId + nounce + timestamp

