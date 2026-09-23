# AIRHOSTESS WITH AI

## AI-Powered Virtual Cabin Crew Assistant

### Project Abstract

AIRHOSTESS WITH AI is an Artificial Intelligence-based system designed to provide intelligent virtual cabin crew assistance to passengers during air travel. The system is designed to understand passenger queries, provide flight-related information, assist with common passenger requests, and deliver appropriate responses through an interactive interface.

The proposed system can use Natural Language Processing (NLP), Machine Learning, Python, and web technologies to communicate with passengers in a simple and user-friendly manner. It can provide information such as flight details, safety instructions, meal information, emergency procedures, frequently asked questions, and other cabin-service assistance.

The main objective of the project is to develop an AI-powered virtual assistant that can provide fast, consistent, and accessible passenger support while assisting human cabin crew with repetitive information requests. During emergencies and safety-critical situations, trained human cabin crew remain essential.

---

## Problem Statement

Passengers may have repetitive questions and requests during air travel, such as flight information, meal services, safety instructions, and general cabin assistance.

Handling repetitive queries can increase the workload of cabin crew.

The proposed system aims to provide an AI-powered assistant that can respond to common passenger queries and provide relevant information quickly.

---

## Objectives

- Develop an AI-powered virtual cabin crew assistant.
- Understand passenger queries using Natural Language Processing.
- Provide relevant flight and cabin-service information.
- Provide safety instructions and frequently asked questions.
- Reduce repetitive information requests handled by cabin crew.
- Provide a simple and user-friendly interface.
- Assist human cabin crew rather than replace safety-critical human decision-making.

---

## Proposed Solution

The AIRHOSTESS WITH AI system provides an interactive interface where passengers can enter or speak their questions.

The system processes the passenger query using AI/NLP techniques, identifies the user's intent, retrieves relevant information, and generates an appropriate response.

### Basic Workflow

Passenger Query  
↓  
User Interface  
↓  
Python Application  
↓  
NLP / AI Processing  
↓  
Intent Detection  
↓  
Knowledge Base / AI Model  
↓  
Generate Response  
↓  
Display Response to Passenger

---

## Key Features

- AI-powered passenger assistance
- Natural Language Processing
- Flight information assistance
- Safety information
- Meal and cabin-service information
- Frequently Asked Questions
- Interactive user interface
- AI-generated responses
- Human cabin crew assistance

---

## Technologies Used

- Python
- Artificial Intelligence
- Machine Learning
- Natural Language Processing (NLP)
- Keras / TensorFlow
- Pandas
- NumPy
- Matplotlib
- HTML
- CSS
- JavaScript

---

# UML DIAGRAMS

## 1. Use Case Diagram

### Actors

- Passenger
- AI Airhostess System
- Admin

### Passenger Use Cases

- Start Interaction
- Ask Questions
- Get Flight Information
- Request Cabin Assistance
- Get Safety Instructions
- Ask FAQs
- Receive AI Response

### Admin Use Cases

- Manage System
- Update Information
- Monitor Queries

### System Interaction

Passenger → AIRHOSTESS WITH AI → AI/NLP Engine

Admin → Manage System  
Admin → Update Information  
Admin → Monitor Queries

---

## 2. Activity Diagram

The activity flow of the system is:

START

↓

Open AI Assistant

↓

Enter / Speak Passenger Query

↓

Process Query Using NLP / AI

↓

Understand User Intent

↓

Find Relevant Information

↓

Generate AI Response

↓

Display / Speak Response

↓

More Queries?

↓

YES → Enter / Speak New Query

NO → END

---

## 3. Sequence Diagram

The system interaction can be represented as:

Passenger → Application  
Application → NLP / AI Model  
NLP / AI Model → Database / Knowledge Base  
Database / Knowledge Base → NLP / AI Model  
NLP / AI Model → Application  
Application → Passenger

### Process

1. Passenger asks a question.
2. Application receives the query.
3. Application sends the query to the NLP/AI model.
4. AI processes the query.
5. Relevant information is retrieved from the knowledge base.
6. AI generates a response.
7. Application displays the response to the passenger.

---

## 4. Class Diagram

### Passenger

**Attributes:**

- passengerId
- name
- flightNumber

**Methods:**

- login()
- askQuestion()
- requestAssistance()

### AIAirHostess

**Attributes:**

- model
- response

**Methods:**

- processQuery()
- generateResponse()
- provideInformation()

### NLPProcessor

**Attributes:**

- inputText
- intent

**Methods:**

- preprocessText()
- detectIntent()
- extractEntities()

### KnowledgeBase

**Attributes:**

- flightDetails
- safetyInformation
- serviceInformation
- FAQs

**Methods:**

- searchInformation()
- updateInformation()

### Relationship

Passenger  
↓  
AIAirHostess  
↓  
NLPProcessor  
↓  
KnowledgeBase

---

## 5. Component Diagram

### Main Components

Passenger / User

↓

Web Application  
HTML / CSS / JavaScript

↓

Python Backend

↓

NLP Processor + AI/ML Model

↓

Knowledge Base

↓

Flight Information / Safety Information / FAQs

↓

AI Response

↓

Passenger

---

# System Architecture

```text
                 USER / PASSENGER
                        |
                        v
              +---------------------+
              |    User Interface   |
              | HTML/CSS/JavaScript |
              +----------+----------+
                         |
                         v
              +---------------------+
              |  Python Application |
              +----------+----------+
                         |
                         v
              +---------------------+
              |    NLP / AI Engine  |
              +----------+----------+
                         |
                 +-------+-------+
                 |               |
                 v               v
        +---------------+ +---------------+
        |   ML Model    | | Knowledge Base|
        |Keras/TensorFlow| | Flight / FAQs|
        +-------+-------+ +-------+-------+
                 |               |
                 +-------+-------+
                         |
                         v
              +---------------------+
              |   AI Generated     |
              |      Response      |
              +----------+----------+
                         |
                         v
                 USER / PASSENGER
