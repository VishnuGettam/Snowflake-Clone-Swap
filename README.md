# Snowflake-Clone-Swap

# Clone  : 

1.clone metadata of one table/schema/database to another uses the same storage layer .

2.Any kind of time travel historical infomation will be lost in cloned object .

3.Further DML operations are independent to each other and only the similar data will be shared b/w the objects and newly created or modified data will be                  pointed wrt to the object metadata.
         
# Swap  :

1.swaps the metadata of one object with another object . 
         
2.Holds time travel history on the swaped object .
         
3.Further DML operations are independent to each other and only the similar data will be shared b/w the objects and newly created or modified data will be                  pointed wrt to the object metadata.
         
