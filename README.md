# Spring-batch-mongoDB
Read data from MongoDB and map into XML file and trigger email based on filter

To upload data into mongodb=>

1. Open compass
2. Click on Add data
3. Select insert document
4. copy paste following


[
  { "_id" : 1, "name" : "Divine Comedy", "email" : "Dante@gmail.com", "contactNo" : 1, "dbo":null, "status": "Complete", "outstandingAmount": 123 },
  { "_id" : 2, "name" : "The Odyssey", "email" : "Homer@gmail.com", "contactNo" : 10, "dbo":null, "status": "Complete", "outstandingAmount": 123  },
  { "_id" : 3, "name" : "Iliad", "email" : "Homer@gmail.com", "contactNo" : 10 , "dbo":null, "status": "Complete", "outstandingAmount": 123 },
  { "_id" : 4, "name" : "Eclogues", "email" : "Dante@gmail.com", "contactNo" : 2 , "dbo":null, "status": "Complete", "outstandingAmount": 123 },
  { "_id" : 5, "name" : "The Banquet", "email" : "Dante@gmail.com", "contactNo" : 2 , "dbo":null, "status": "Complete", "outstandingAmount": 123 }
]


To Run application

Just go to springApplicaion main class and run as java application