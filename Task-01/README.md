## Basic Understanding Of SpringBoot By Creating A Project :

- In this project we have 4 packages :

  1- Pojo
  
  2- Controller
  
  3- Service
  
  4- Repository
   
- Pojo Package consist of one class name as Payment . In this class , 5 variables are there name as paymentId , status , transactionId , price and orderId . Other than that we have getter-setters , constructors and toString method .

- Controller Package consist one class name as PaymentController . This class contains Rest-Api for Add , Update , Search , Delete And findAll payment details .

- Service Package consist one class name as PaymentService . This class contains all the business logics which helps to manipulate the records . 

- Repository Package consist one interface name as PaymentRepository which extends JPA-Repository which helps to connect business logic with database , so we can also say that repository interface is for database logic .

- At last we have Application.properties which contains all the logic for connections with mysql server and we can add a server-port for restApi .
