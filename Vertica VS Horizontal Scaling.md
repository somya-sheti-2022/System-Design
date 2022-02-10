
# Vertical Vs. Horizontal Scaling

***Scaling Systems*** is one of the most important things and we gonna discuss the **two main approaches** for the same here.   So lets get started.

## Real life Scenario

👋 Hi, So before we  directly dive into technical stuff let me give you a real life scenario:


*Suppose there is some School having one building to accomodate 500 students and they want to increase the intake of student this year.*\
**How can they expand the infrastructure for the same?** 🤔

To some extent they can construct ***more floors in same building*** 🏠	 -- this resemble ***Vertical Scaling***

**But what if they want even more intake ?** 🤔 

They can ***construct a new building right*** 🏠	🏠	 -- this resemble ***horizontal Scaling***


## Scalibility

So if you have understood the above example ***Congratulate***🤩 yourself as you have understood the concept of **vertical scaling and horizontal scaling** and you don't even realized right.

### What is Scalability?

Suppose your system can handle *100 request* at a time and suddenly it start recieving *150-200 request*.

Your system wont be able to handle so many request right. So here comes the concept of ***Scalability*** **[ which means expanding your system to handle more and more request ]**.

*This can be achieved by 2 major scaling methodologies namely:*

**1- Vertical Scaling**: Where we try to ***optimize process with the same resource (server) to handle more request.*** ( Similar to increasing floor in same builiding )

**2- Horizonatal Scaling**: Where we ***buy more resources to handle more incoming request***. ( Similar to inceasring number of builidings )

### Advantages of Horizontal Scaling over Vertical Scaling


1- ***Avoid Single Point of Failure*** as if one server goes down other server can serve the request. \
2- ***Has no hardware limitations*** as you increase the machines and not the power of single machine 

### Advantages of Vertical Scaling over  Horizontal Scaling

1- ***Doesn't require a load balancer*** to distribute the request across mutiple servers.\
2- ***Has interprocess communication*** which is more fast *( in horizontal communication is over a network. )*\
3- ***Data is more Consistent*** as only single system is there *( in horizontal there is a bit of data incosistency is there )*

### So what do we use in a real life system and why? 🤔

Both the methodologies have their own advantage and disadvantages and we use a ***hybrid model in majority cases*** to utilize the advantages of both the methodologies and get the best possible result.
## So here comes to the End 
🤞	 ***Hope you find this useful and you learnt something new today***
