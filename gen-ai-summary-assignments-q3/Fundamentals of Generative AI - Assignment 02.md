* What are microservices, and how can AI-based microservices be developed?  
    * Microservices is an architetural pattern where we can structure the application 
    into loosely coupled multiple services, where each ervice performs a specific function and is independently developable and deployable
    * It is in contrast with the monolithic application where all the functionality is 
    tightly coupled and tightly integrated application
    * Services can be scaled independently instead of spinning the whole application instance we can independently spin only the services for which the demand is high and scale down as well. This approach should optimize resource utilization.
    * Decentralized Data management, each service can has its own database or store
    * Services communicate with each other grpc or  message queues
    * Different tech stack ,languages can be used for each service allowing technology stack decoupling and more flexibility
    * Faliure of one service doesnt bring down the entire application 
    * More Services means more componnets to manage
    * Ensuring data consistency across multiple services can be challenging
    * Requires sophisticated deploymnet strategies like containerization (docker) and orchestration(kubernetes)

    * **AI  Microservices** 
    * We can place each AI model in a separae microservice. For example: text generation, music, image synthesis can have their own separate microservice
    * Different AI models might require different frameworks (pytorch, tensorflow), which can be managed more easily with microservices
    * Resource Intensie AI models can be scaled independently optimizing the usege of computational resources
    * Multiple instances of critical AI services can be run to ensure high availability and fault tolerance
    * Microservices integrate via APIs so we can integrate multiple AI services just via the APIs
    * There are operational challenges since multiple microservices require sophisticated orchestration and monitoring tools
    * Inter-Services Communication can introduce latency which needs to be handeled 
    * Ensiring consitent data flow and storage across multiple services can be challenging
    
    * **Summary**
    * Microserivces and Gen AI can be a perfect match allowing modularity, flexibility and scalability but there are some challenges to deal with like ensring consistent data flow and storage , orchestration and monitoring of the services mesh
