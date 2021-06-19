# springboot-aws-dynamoDB
In this project, a simple MVC pattern is followed to demonstrate AWS DynamoDB using Spring Boot and the project is deployed to Elastic Beanstalk.

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


