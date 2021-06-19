# springboot-aws-dynamoDB
In this project, a simple MVC pattern is followed to demonstrate AWS DynamoDB using Spring Boot and it is deployed to AWS Elastic Beanstalk.
### What is DynamoDB?
DynamoDB is a fully managed NoSQL database service by Amazon that provides fast and predictable performance with seamless scalability. DynamoDB lets you offload the administrative burdens of operating and scaling a distributed database so that you don't have to worry about hardware provisioning, setup and configuration, replication, software patching, or cluster scaling.
### What is Elastic Beanstalk?
AWS Elastic Beanstalk can help you deploy and scale your applications and services with ease and without you having to worry about provisioning components and implementing high availability features such as elastic load balancing and auto-scaling.  All of this and more is managed and handled by Elastic Beanstalk.


### Person Id - 116ca0c2-6b1f-42e5-8a6e-811af675fec4

### Request JSON to save/edit/delete person from AWS DynamoDB
```
{
	"name":"Srini",
	"email":"srini@gmail.com",
	"age":22,
	"address":{
		"city":"Chennai",
		"state":"Tamilnadu",
		"pinCode":"123456"
	}
}
```

### URL for the CRUD operation:

* Read data from DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//getPerson/{personId}

* Save data to DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//savePerson

* Edit data to DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//editPerson

* Delete data from DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//deletePerson


