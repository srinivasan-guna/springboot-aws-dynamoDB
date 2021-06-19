# springboot-aws-dynamoDB
In this project, a simple MVC pattern is followed to demonstrate AWS DynamoDB using Spring Boot and the project is deployed to Elastic Beanstalk.

Person Id - 116ca0c2-6b1f-42e5-8a6e-811af675fec4

Request JSON to save/edit/delete person from AWS DynamoDB
{
	"name":"Santosh",
	"email":"santosh@gmail.com",
	"age":30,
	"address":{
		"city":"Bangalore",
		"state":"karnataka",
		"pinCode":"560037"
	}
}

URL for the CRUD operation:

READ DATA FROM DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//getPerson/{personId}

SAVE DATA TO DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//savePerson

EDIT DATA TO DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//editPerson

DELETE DATA FROM DynamoDB - http://springbootdynamodb-env.eba-4kypmin3.us-east-2.elasticbeanstalk.com//deletePerson


