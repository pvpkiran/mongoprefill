# Initialize Mongo with data  
   This is a simple Mongo Equivalent for Liquidbase or Flyway. Provided seed data, this autoconfiguration  
prefills mongo with the data. This could be used with embedded or standalone MongoDB
   Mongo seed data should have file name **mongoseeddata.json** and should be in classpath(preferably resources folder). And as the name indicate, it should be of json format.
 
 Seed data should be in the following format  
 ```json
 {  
   "collectionName1" : [     
     {
       
     },
     {
     
     } 
   ],
   "collectionName2" : [  
     {
      
     },
     {
       
     }  
   ] 
}
