## Chapter 2. Web architecture

# Lesson 1. Browsers

https://academy.zerotomastery.io/courses/system-design/lectures/44070483

- Check <request> diagram

# Lesson 2. DNS

https://academy.zerotomastery.io/courses/system-design/lectures/44070486

DNS => Domain Name System

For a computer a DNS does not mean anything, this is just to make it redable to human, what the computer see is the IP address. A website, especially the large ones, could be more than one IP address

# Lesson 3. Web Servers

https://academy.zerotomastery.io/courses/system-design/lectures/44070485

- Check <webserver resources> Diagram

# Lesson 4. Load Balancer (Part 1)

https://academy.zerotomastery.io/courses/system-design/lectures/44070484

- check <horizontal scaling> diagram
- check <load balancer> diagram

# Lesson 5. Load Balancer (Part 2)

https://academy.zerotomastery.io/courses/system-design/lectures/44070768

- check <session persistance> diagram

# Lesson 6. Databases

https://academy.zerotomastery.io/courses/system-design/lectures/44070766

# Lesson 7. Caching

https://academy.zerotomastery.io/courses/system-design/lectures/44070769

- check <catching> diagram

Catching is used to store data that is retrieved from the database for a short period of time. This method save time since databases could be very expensive in term of time (large latency)

# Lesson 8. Jobs - Servers

https://academy.zerotomastery.io/courses/system-design/lectures/44070767

# Lesson 9. Jobs - Queues

https://academy.zerotomastery.io/courses/system-design/lectures/44070858

# Lesson 10. Services (Part 1)

https://academy.zerotomastery.io/courses/system-design/lectures/44070857

# Lesson 11. Services (Part 2)

https://academy.zerotomastery.io/courses/system-design/lectures/44070855

- service is a single project, self contain deliverable system, for example authentication.

- check <service> diagram. This is applied to facebook as an example

# Lesson 12. Data

https://academy.zerotomastery.io/courses/system-design/lectures/44070856

- Check <data> diagram

- The data could be sent directly to the <Data Hose> fron the frontend using tools like <Google analytics> without using the <webserver>.

- this data is "massaged" into a format that could be used to analys it and store in adatabase warehouse in order to understand clinet behaviour and improve the product.

# Lesson 13. Cloud Storage CDN

https://academy.zerotomastery.io/courses/system-design/lectures/44070961

- Check <cloud storage> diagram

CDN => Content Delivery Network

- Check <edge server> diagram. This server has a copy of the info in the origin server and are located all around the world. This way decreacy latency significantly.

- CDN is just used when is a global business.

- Check <Web Architecture> contains all the part of the web that has been explain in this chapter.
