# KamerEasyTravel

Is a B2B platform I developed using Node.js now I am moving it to Spring boot 2 (with Java 17) and React.js.
The complete application is build using a micro-service Architecture! [See Architecture: file "Architekture_Overview"]

## Old Description
### Goal:
The project is to implement an e-commerce platform for booking and managing travel. The platform should enable the customer to book trips, query travel information and manage other information. 

### Brief description:
Within the project the backend was implemented based on Node.js under a MicroService architecture.
The challenge was to develop the system from smaller components and to integrate local payment methods into the system. For example, "Orange Money", "MTN Money" and "PayPal" were integrated as payment methods.

## Status: Still on Development (not done yet). But both projects (Node.js and Java Spring boot will remain private).

## Old Technology Stack:
	-> Node.js
	-> Express (for routing and etc.)
	-> Handlebars (to render UI)
	-> passport.js (handles 3rd party authentications such as "Facebook", "Google", "Paypal" and etc.)
	-> 2-Authentication process
	-> Axios.js (handle communication calls between micro-services and also REST calls in UI)
	-> SSL
	-> For deployment and load-balancing: Docker, PM2, Nginx
	-> Winston (for loggings etc.)
	
