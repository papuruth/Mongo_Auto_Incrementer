# Mongo_Auto_Incrementer
For this, create a counters collection, which will keep track of the last sequence value for all the sequence fields.
Now, we will create a function getNextSequenceValue which will take the sequence name as its input, 
increment the sequence number by 1 and return the updated sequence number. In our case, the sequence name is productid.
Then we uses db.system.js.save(); method to save the js script
Then db.loadServerScripts(); to load the js
