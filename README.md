## sample-razor-pay-spring-java

A Simple application developed for using Razor pay with Java.

These options are used:

- Spring Boot
- Maven
- Thymeleaf
- Bootstrap

Before Running this project create an account in RazorPay **(https://dashboard.razorpay.com/#/access/signup)** Generate secretID and secretKey. save this values.

1. Clone the project
2. Do a maven update on the project if necessary
3. use the above generated secretID and secretKey and replace this values in Home.java
4. Run the main Class (RazorPayApp.java)
5. Now use the URL **http://localhost:8001/razorpayapp** Fill the form click the Pay button. That's it!
In this application I have only done how to do payment in Razor Pay with an order. For more reference **https://docs.razorpay.com/v1/page/orders**