**

# Springing into Action: Evolving Interactions with Thymeleaf, RabbitMQ, and WebSockets in Spring Boot

In this repository, I delved into the realm of application interaction and the crucial need for efficient means of communication. I introduced view technologies, such as Thymeleaf, and the engines that process them, illustrating how Spring Boot utilizes them to create and deliver functionality to the end user's browser. I also explored Spring Boot's handling of static content, including standard HTML and JavaScript, which can be delivered directly without processing by template engines. 

For my first project iteration, I showcased a Thymeleaf-driven application that retrieved and displayed aircraft positions in a pull-based model. 

Subsequently, I harnessed the power of messaging platforms with Spring Boot, leveraging Spring Cloud Stream and RabbitMQ. I refactored the PlaneFinder application to push real-time aircraft positions to the Aircraft Positions app, making the backend functionality event-driven. Although the front end still required manual or hard-coded refreshes to update user-visible results.

In the final part, I implemented WebSocket connections and handler code within the backend and frontend components of the Aircraft Positions application. This setup allowed the Spring+Java backend app to push live aircraft position updates received via RabbitMQ without requiring user or browser-initiated requests. This highlighted the bidirectional nature of WebSockets, their lack of required request-response patterns, and their low communication overhead.

**