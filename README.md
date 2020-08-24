![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)
![Node.js CI](https://github.com/naivedeveloper95/node-twilio-integration/workflows/Node.js%20CI/badge.svg)

# node-twilio-integration

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

## References

### Bulk SMS

- https://www.twilio.com/blog/2017/12/send-bulk-sms-twilio-node-js.html

### Receiving Two-way SMS Messages

- https://support.twilio.com/hc/en-us/articles/235288367-Receiving-two-way-SMS-messages-with-Twilio

### How to receive sms in Node.js with Twilio

- https://www.twilio.com/blog/2016/08/how-to-receive-an-sms-in-node-js-with-twilio-and-hyperdev.html
