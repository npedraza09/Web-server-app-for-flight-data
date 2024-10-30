# Index
* [Abstract](#abstract)
* [Process](#process)
  * [Creation of Collection Types](#creation)
  * [Data Insertion Test](#insertion)
  * [Postman HTTP messages](#HTTP-messages)
* [Conclusion](#conclusion)   

<a class="anchor" id="abstract"></a>
## Abstract
In this project, through Strapi I designed a web server application for managing flight data using a content management system. I created structured collections for Airlines, Airports, and Flights, populated each with sample data, and used Postman to interact with the server. Through GET, POST, PUT, and DELETE requests, I demonstrated the ability to retrieve, create, update, and delete flight records. Additionally, I implemented a Python application to make GET requests to the server, verifying data retrieval through Visual Studio Code. This project highlights my skills in web server management, API requests, and practical application development using CMS and Postman.

<a class="anchor" id="process"></a>
## Process

<a class="anchor" id="creation"></a>
### 1. Creation of Collection Types
For my flight data app I created three collection types: Airline, Airport, and Flights.

1.1. Airline collection

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/1d3a371e-7102-4e51-bbe2-005ce08a4a1d">


1.2. Airport collection

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/6eee59e7-d230-4048-b75d-5936b51133c7">


1.3. Flights collection

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/7b206402-80a5-4940-a2a7-9aeee571fa67">

<a class="anchor" id="insertion"></a>
### 2. Data Insertion Test
I entered three rows for each table in my collection. Here is the evidence that I entered the data by pointing my browser to each collection:

2.1. Airlines

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/910e04aa-73ae-41be-9365-55bdc9a578e7">

2.2. Airports

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/0c389542-1715-44d4-a9c7-7aa4577897e6">

2.3. Flights

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/43bd6f12-1dcd-4dcb-afe8-5e9f522b8f28">

<a class="anchor" id="HTTP-messages"></a>
### 3. Postman HTTP messages
Using Postman, I sent a couple of HTTP messages to interact with my application and modify it.

3.1. I sent a GET request to retrieve all of the data from my Flights application.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/311baab5-26df-450a-801b-ef5084f2c8c3">

3.2. I sent a GET request to get the flight with a specific id.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/fd893eef-6493-4944-a65b-912f8179142e">

3.3. I created a POST request to create a new flight.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/e89a3fb1-3b04-426a-8e63-9213c4287e0b">

3.4. This is my browser in the flights collection. Here is the evidence of the new flight that was created.

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/d00d88b6-e5df-44f0-a6d2-43fd1511e71e">

3.5. I sent a POST request to update a flight from my Flights application.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/b0adbfa4-4967-4a35-a10a-404240ec83da">

3.6. Evidence of the flight updated in my browser.

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/f1ff5f2f-77e9-4f81-a1ee-8fff624ef3e8">

3.7. I sent a DELETE request to delete a flight from my Flights application.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/37c3dff9-3d27-43ab-877c-6580a0da912f">

3.8. Evidence of the flight deleted in my browser.

<img width="800" height="200" alt="image" src="https://github.com/user-attachments/assets/4ead4cb9-d2a1-491b-8e20-621b7c17d3ed">

3.9. I obtained the code to create a Python application to make a GET request for my airline application. I then ran the code in Visual Studio Code and to see the results and compare the interaction with the interface of Postman.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/ed8b41d0-9e78-4c5b-adee-4c8875892947">

<a class="anchor" id="conclusion"></a>
## Conclusion

In conclusion, this project successfully demonstrated the creation and management of a web server application for flight data using Strapi as a content management system. By designing structured collections for Airlines, Airports, and Flights, and employing Postman to execute CRUD operations, I showcased a robust approach to handling data interactions. Additionally, implementing a Python application to retrieve data highlighted my ability to integrate external applications with the server, ensuring a smooth data retrieval process. This project reflects my proficiency in API management, data handling, and practical application of CMS technologies to build scalable and efficient solutions for data-driven environments.












