# Experience API Model - Inchcape CEX
--- 
#### Inchcape CEX ####

This Experience API Model exposes functionalities to end users in order to exchange data with SFDC. 
A specific data format could facilitate and provide quick integration with this experience api. 

### Connect with Anypoint MQ 

### How it works ### 

This application accepts JSON messages which contains <object> information into an [HTTPS Connector](https://docs.mulesoft.com/api-manager/https-reference), then validates minimal data format to finally uploads the message to Anypoint MQ. 

The [Anypoint MQ Connector](https://docs.mulesoft.com/anypoint-mq/) publish new messages in an Exchange. When the message has been published to the Exchange, this one will be routed to a specific queue according to certain header parameters.

### Documentation ###

This Experience API should be extended. 

### Go further ###

- Inchcape [About](https://www.inchcape.co.uk/about-us/) 