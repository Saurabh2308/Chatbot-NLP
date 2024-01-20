# Chatbot-NLP

### Description:
This comprehensive end-to-end project aims to create a robust and efficient food delivery chatbot system using cutting-edge technologies. The project covers the fundamentals of Dialogflow, integrates a Python-based FastAPI backend, and establishes seamless communication with a MySQL database for effective data management.
### Key Components:

### Dialogflow Integration:

Leverages Dialogflow for natural language understanding.
Intents: Define user intentions and interactions.
Entities: Extract key information from user input.
Contexts: Manage conversation flow and context-aware responses.
NLP (Natural Language Processing): Enhance language understanding for more human-like interactions.
Utilizes Webhook fulfillment for backend communication.
### Backend Development with FastAPI:

Implements a FastAPI backend in Python for handling user requests.
Utilize FastAPI, a modern, fast, web framework for building APIs with Python.
Implement efficient communication between Dialogflow and the backend.
Handle user requests, process information, and generate appropriate responses.
Establishes communication with MySQL for efficient data storage and retrieval.
Defines functions for inserting order items, tracking orders, and calculating total order prices.
### MySQL Database Management:
Interface with MySQL to store and retrieve essential data for the food delivery system.
Ensure seamless data integration between the chatbot and the database.
Utilizes MySQL database for storing food items, orders, and order tracking information.
Implements stored procedures and functions for better data manipulation.
Ensures data integrity through foreign key constraints.
### Web Interface:

Provides a simple web interface with sections for Home, Menu, Location, and Contact Us.
Integrates a chatbot interface using Dialogflow for seamless interaction.
### Chatbot Functionality:

Implements core chatbot functionalities such as adding items to the order, removing items, completing orders, and tracking orders.
Manages order information in-memory during the conversation using a Python dictionary (inprogress_orders).
Integrates with the MySQL database for persistent storage of order details.
### Frontend:

Includes a basic HTML and CSS frontend with sections for displaying the menu, location, and contact information.
Embeds the Dialogflow chatbot for user interaction.
### NLP and Fulfillment:
Enhance user experience through advanced Natural Language Processing techniques.
Fine-tune the chatbot to understand user queries, preferences, and context for more accurate responses
Uses Webhook fulfillment to handle complex user requests and communicate with the backend.

This project not only showcases the integration of Dialogflow with a Python backend but also demonstrates the practical application of Natural Language Processing in a real-world scenario. Users can easily interact with the chatbot to place orders, track deliveries, and receive status updates.
