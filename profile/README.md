# Frame Forge Suite (FFS)

What is the Frame Forge Suite (**FFS**)? The **FFS** is a collection of microservices that are designed to work together to provide a complete (or partial) solution for the creation of a **Information System** (IS). The **FFS** is designed to be a flexible and scalable solution that can be used to create a wide variety of **Information Systems** (ISs).

## Description

### What is an Information System (IS)?

An **Information System** (IS) is a system that is designed to collect, store, process, and distribute information. An **IS** can be used to support decision-making, control, analysis, and visualization of information. An **IS** can be used to support a wide variety of activities, including business, science, engineering, and education.

### What is the Frame Forge Suite (FFS)?

Before we dive into the details of the **FFS**, let's take a step back and look at the big picture. The **FFS** is a collection of microservices, but what exactly is a microservice ?

#### Monolithic Architecture _VS_ Microservices Architecture

The difference between monolithic architecture and microservices architecture is significant in how applications are designed, deployed, and managed. Here’s a quick comparison of both:

##### Monolithic Architecture

_Definition_: A monolithic architecture is a single, unified software application that is self-contained and built as one indivisible unit.

_Characteristics_:

- _Single Codebase_: The entire application resides in a single codebase, often resulting in a large codebase.
- _Scaling_: Typically scaled vertically (by adding more resources to a single server).

_Advantages_:

- Simplicity in development and deployment.
- Performance can be highly efficient due to direct memory access.

_Disadvantages_:

- As the application grows, it becomes complex and hard to manage.
- Any change requires the entire application to be redeployed.
- Scalability limitations, as it’s challenging to scale individual components independently.
- Higher risk of entire application downtime due to a single point of failure.

##### Microservices Architecture

_Definition_: A microservices architecture breaks down an application into smaller, independent services that communicate over well-defined APIs.

_Characteristics_:

- _Multiple Codebases_: Each microservice has its own codebase and can be developed, deployed, and scaled independently.
- _Independent Deployment_: Services can be deployed independently, allowing for more frequent and reliable updates.
- _Scaling_: Can be scaled horizontally (by adding more instances of a particular service).

_Advantages_:

- Flexibility in using different technologies for different services.
- Improved fault isolation, where failure in one service does not necessarily bring down the entire system.
- Better scalability, as services can be scaled independently based on demand.

_Disadvantages_:

- Increased complexity in communication between services.
- Requires a robust infrastructure for handling inter-service communication, load balancing, and service discovery.
- Potential for higher latency and overhead due to network communication between services.

##### Conclusion

Both architectures have their use cases and choosing between them depends on the specific requirements, scale, and goals of the project. Monolithic architectures might be suitable for simpler, smaller-scale applications, while microservices architecture is better suited for complex, large-scale applications needing flexibility and independent scalability.

#### The Frame Forge Suite (FFS)

Now that we have a better understanding of microservices, let's dive into the **FFS**. The **FFS** collection of microservices is designed to work together to provide a complete (or partial) solution for the creation of an **Information System** (IS).

We have a lot of microservices available in the **FFS** collection, and each microservice has its own unique functionality. Here are some of the key microservices available in the **FFS**:

- **AuthSquared**: A microservice that provides authentication and authorization services (e.g., login, registration, password reset, role-based access control).
- **UserManager**: A microservice that manages user accounts and profiles.
- **ContentManager**: A microservice that manages content (e.g., articles, blog posts, images, videos).
- **PartnerManager**: A microservice that manages partner relationships and integrations.
- **PartnerRemManager**: A microservice that manages partner relationship remunerations confgiurations.
- **RelayMailer**: A microservice that sends transactional emails (e.g., welcome emails, password reset emails) using various email providers (e.g., Amazon SES, SendGrid, Mailgun).
- **TicketManager**: A microservice that manages support tickets and customer inquiries.

These are just a few examples of the microservices available in the **FFS** collection. Each microservice is designed to be modular, scalable, and flexible, allowing you to mix and match the microservices to create a custom **Information System** (IS) that meets your specific requirements.
