# E_commerce-system
E-commerce system with high-availability and high-coccurency
Built a scale web service and deployed to Google Cloud (GAE flex); Utilized distributed session to allow responds from multiple servers; Exploited Redis as a cache to improve access speed and concurrency as well as to reduce the database pressure.
Utilized the tech stack of page statics, caching pages to the browser, separation of frontend and backend to reduce the server stress and improve user experience.
Integrated message queues (RabbitMQ) to complete asynchronous order to for the peak reduction and flow reduction; Enabled the system to be capable of handling 10000 queries per second tested by Apache JMeter.
Optimized the system security by hiding the interface address with two-factor md5 password verification; Used mathematical formula verification code for the rate-limiting and anti-rushing.
