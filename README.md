                                                           # ** CRUD Serverless-API ** #

Prerequistes
1. AWS Dynamodb
2. API Gateway
3. AWS Lambda
4. POSTMAN
5. Common sense

CRUD - Create Read Update Delete

1. Create New table in Dynamodb according to the requirments

![dynamodb-dash](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/3f323887-c81f-4217-b27d-cb827d1f0fcb)

2. Create AWS Lambda function along with IAM role with permission DynamodbfullAccess and CloudwatchlogfullAccess

![lambda-dash](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/b9bd8924-55fd-4c59-b7bf-cf819d9e2c46)

![lamda_input](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/9b495bdb-e77f-4908-9ff0-85b26ab8492a)


4. Create API Gateway with API type REST API and all persmission required and use node.js file for code source.

5.  Create method and resources like below

![apidateway-input](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/eaf788bd-da93-4c11-80af-8e51dd67d5a7)

6.  Put the URL from deploying the api into POSTMAN

![image](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/b60f5741-985c-4b0b-bfd1-136470381d31)

7.  GET Request (READ)

![get product](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/704c21e9-6f0b-414d-87d5-a81736d003f0)

8.  PATCH Request (UPDATE)

![update](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/f5f78a28-8014-4b94-94c0-1ebfe741940c)

9.  DELETE Request (DELETE)

    [delete](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/b2bd238c-15fd-4182-8d25-65d2ba20c6bf)

11.  POST Request (CREATE)

 [create](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/2c96021a-d4cd-4c78-865b-612f63df18da)

12.  Check ouput in Dynamodb
  
  ![dynamodb-output-last](https://github.com/hijackhim/CRUD-Serverless-API/assets/105789918/6b1e72aa-5003-4abe-97c2-28c9ab5fe5ed)
