# cncf-datawarehouse

**Author** - Ajay Pillai 

One of the spaces where I dont see a lot of movement is building Cloud Native Cloud Foundation datawarehouses. People are still stuck in the legacy batch processing mindset using ETL toolsets like Informatica and Abinitio.
The power of streaming architecture using tools like Kafka, AWS Kinesis and Datahose and building on the analogy from multiple streams (streaming data from IoT sensors), relational databases, unstructured social media feeds etc.,
to a lake (Data Lake) which stores data in its pure raw format then curated via the plumbing [Kakfka , Kinesis, Data pipelines etc] into a repository that is clean for drinking in a water tower (a.k.a Datawarehouse) and finally 
distributed to the residents/consumers (visualization, data science etc.)

Here is my attempt  to get the blue-prints build for it
