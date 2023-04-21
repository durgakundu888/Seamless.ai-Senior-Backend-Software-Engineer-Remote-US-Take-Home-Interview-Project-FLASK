Seamless.ai-Senior-Backend-Software-Engineer-Remote-US-Take-Home-Interview-Project

Take-Home Project from https://seamless.ai for the Senior Backend Software Engineer - Remote US position. I developed an E-commerce Microservices Web App using React, Django, and Flask microservices with MySQL Database sending messages to RabbitMQ (and AWS technically) running on Docker containers. The admin (Django) and main (Flask) services communicate with each other using events sent to/received from RabbitMQ. The main service also internally sends API requests to the admin app. Both services have their own MySQL databases. 

The admin service allows the seller to create, update, and delete her products. The main service allows the customer to view and like products for sale. 

This project is not hosted on any domain. You can download and run localhost on the react-crud app and play with it in your browser.

Full Stack: 
- React
- Typescript, NodeJS, and JavaScript
- Python, Django, and Flask
- RabbitMQ Message Queue Service (uses AWS internally)
- MySQL 
- Docker
- HTML
- CSS, Bootstrap
