
# node-twilio-integration

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/56b0d6e266064776a6e4482c43185a59)](https://app.codacy.com/manual/naivedeveloper95/node-twilio-integration?utm_source=github.com&utm_medium=referral&utm_content=naivedeveloper95/node-twilio-integration&utm_campaign=Badge_Grade_Dashboard)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)

## Routes

### POST /sms

```javascript
Content-Type: application/json

{
  "recipient" : "+91xxxxxxxxx",
  "message": "Hello, this is a sms sent to one person!"
}
```

### POST /smsCopilot

```javascript
Content-Type: application/json

{
  "recipient" : "+91xxxxxxxxx",
  "message": "Hello, this is a sms sent to one person!"
}
```

### POST /sendGroupSMS

```javascript
Content-Type: application/json

{
  "recipients" : ["+91xxxxxxxx1","+91xxxxxxxx2","+91xxxxxxxx3","+91xxxxxxxx4","+91xxxxxxxx5"],
  "message": "Hello, this is a group sms"
}
```
