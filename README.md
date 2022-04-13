# todolistapp_mongo
A todo list app that captures the input and actions which then populated into MongoDB database. 


## MongoDB cloud database
This app is connected to the MongoDB database. 
Create a new database under a cluster in MongoDB Atlas called "todolistDB" <br/> 
Select 'connect your application' option and copy the SRV command line.


**Ensure you app.js contains the following SRV command that looks something like this**
mongoose.connect("mongodb+srv://<USERNAME>:<PASSWORD>@<CLUSTER_PATHWAY>.mongodb.net/todolistDB",{useNewUrlParser: true, useUnifiedTopology: true}); <br/>

**Testing** 
