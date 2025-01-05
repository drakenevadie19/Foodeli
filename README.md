# idraiske-food-restaurant-application

<h2>Technologies: </h2>
<ul>
  <li>Front-end: Angular, Bootstrap 5</li>
  <li>Connecting Front-end and Back-end: RestAPI, Postman.</li>
  <li>Back-end: Spring Boot, Microservices, Github, Docker, Kubernetes, Junit, Sonar, AWS EKS, AWS ALB, AWS EC2, AWS RDS (SQL), Mongo Atlas (No-SQL), MySQL, Jenkins, ArgoCD.</li>
</ul>

<h2>Front-end pages: </h2>
- Link: https://github.com/drakenevadie19/idraiske-food-delivery-application-FE.git
- Components: 
  - Restaurant List page: Displaying a list of restaurants available in the system. 
  - Food Catalogue page: Displaying a list of dishes for each restaurant. 
  - Order Page: Place an order for dishes from a restaurant.

<h2>Back-end microservices: </h2>
- Eureka Server: 
  - Monitoring current online servers.
  - Enabling LoadBalancer to inject a server's service into another server's back-end.
  - Link: https://github.com/drakenevadie19/idraiske-eureka-server.git
- Food Catalogue:
  - Managing dishes for restaurants in a MySQL database.
  - Respond to Food catalog endpoints.
  - Link: https://github.com/drakenevadie19/idraiske-Food-Catalogue-Microservice.git
- Restaurant Listing:
  - Managing a list of available restaurants in an area.
  - Store and extract them from a MySQL database.
  - Link: https://github.com/drakenevadie19/idraiske-Restaurant-listing-Microservice.git
- userInfo Management:
  - Storing, fetching, and updating users' information such as ID, name, password, and user delivery address for food delivery.
  - Managing massive info in a MySQL database.
  - Link: https://github.com/drakenevadie19/idraiske-userInfo-Microservice.git
- Order Microservice:
  - Save all the information of the restaurant's details, and user details from where to order pickup to where to order has to be served, into the MongoDB database
  - Respond to Endpoint to save order in the database.
  - Link: https://github.com/drakenevadie19/idraiske-Order-Microservice.git

<h2>Deployments and maintenance: </h2>
- Utilizing Manifest files to create deployments for pods/microservices
- Links: https://github.com/drakenevadie19/idraiske-deployments.git

<h2>System Architecture</h2>
<img width="100%" alt="Screenshot 2024-12-20 at 6 20 14 AM" src="https://github.com/user-attachments/assets/750e2b7e-9b3c-472d-9de7-cb9a23f15575" />

<h2>CICD Diagram</h2>
<img width="100%" alt="Screenshot 2025-01-05 at 6 06 35 AM" src="https://github.com/user-attachments/assets/d8767752-7966-4cbd-ad8e-902c5755b560" />


