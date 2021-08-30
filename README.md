## Question 2

Amongst what would be an endless list of aspects that encompasses “quality software”, here is a list of 5 general aspects that would be of high priority when it comes to quality software.


- Testing

Making sure that the application (and/or individual components/functions of the application) works as expected involves the use of a testing framework such as Jest. This ensures that function output and behaviour is as expected during and after the development process. User testing would also help to catch bugs, logic errors and facilitate User Interface adjustments based on user feedback and product alpha/beta testing.

- Scalability

The application needs to be engineered to be capable of growing to support the size of its increasing userbase. The foundation architecture of the application may have an effect in this outcome. Is it a Monolith application? ... or does the application use microservices? - perhaps both server side and client side. Database architecture is also an important consideration in terms of scalability. A document-based database (such as Mondo DB) is considered to be more easily and quickly deployable and scalable than an table/relational-based database. Mongo DB requires less planning and it is not as rigid in the way that table/relational-based database are to implement.

- Maintainability

The application needs to be easily maintainable by its engineers. The code base needs to be refactorable and re-implemented without causing significant interruption to users. This may perhaps come down to how the application was architecturally implemented. This is also one of many reasons that microservice architecture is generally used with larger applications, as Microservices allow parts of an application to be totally offline without effecting the rest of the application or its users. Another factor would be workflow, source control process and internal company procedures.

- Performance

As the userbase increases and/or new features implemented, the application needs to have been engineered for maximum speed, no matter how large the userbase. Server processing power will also play a major role here, as well as server bandwidth and also whether the application has been deployed using CDN technology (depending if global access is required).

- Security

Any software application needs to be secure against cyber-attacks and service disruption, information theft and identity theft. Keeping application dependency package versions current and up to date helps in maintaining security vulnerabilities. Also, maintaining server operating systems and security utilities can help to prevent malware and spyware script injections into hosted software applications.