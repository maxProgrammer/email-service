# email-service
It's a REST API responsible for sending an email using gmail smtp. It's prepared to work in the synchronous mode for HTTP Request or asynchronous mode for RabbitMQ dispatcher broker
<h1> ✉️ api-email ✉️</h1>

> Status: Completed ✅

### It's a REST API responsible for sending an email using gmail smtp. It's prepared to work in the synchronous mode for HTTP Request or asynchronous mode for RabbitMQ dispatcher broker

<h1 align="center">
  <img alt="Readme" title="Readme" src="https://user-images.githubusercontent.com/87916631/167322821-580a859b-df58-4382-95ee-63313a0b9a30.png"/>
</h1>



## 🔘 Fields ofEmailModel are:
+ emailID
+ ownerRef
+ emailFrom
+ emailTo
+ subject
+ text
+ sendDateEmail
+ statusEmail


## 📔 Features
Send email in synchronous mode and asynchronous mode.

## 🤝🏽 Business Rules
Emails can be sending in two ways:
- Created a queue on RabbitMQ that monitored for one consumer and when it realize that has a new email it call the method sendEmail fot emailService.
- The second way is to call the route responsible to send email by HTTP requisition.

## ⚒️ Technologies
+ Java 11
+ Spring Boot
+ Maven
+ PostgreSQL
+ Smtp server
+ RabbitMQ

## 🌱 Starters
+ Spring WEB
+ Spring Data JPA
+ Spring Boot DevTools
+ Spring for RabbitMQ
+ Validation
+ PostgreSQL Driver
+ Lombok
+ Swagger UI

## 🪖 Patterns
+ MVC
+ IOC
+ DTO

## 📲 contact
+ linkedin: https://www.linkedin.com/in/maxwneto/
