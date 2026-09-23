# AIRHOSTESS WITH AI

## AI-Powered Virtual Cabin Crew Assistant

## Abstract

AirHostess with AI is an Artificial Intelligence-based system designed to provide intelligent virtual cabin crew assistance to passengers during air travel. The system is designed to understand passenger queries, provide flight-related information, assist with common passenger requests, and deliver appropriate responses through an interactive interface.

The proposed system can use Natural Language Processing (NLP), Machine Learning, Python, and web technologies to communicate with passengers in a simple and user-friendly manner. It can provide information such as flight details, safety instructions, meal information, emergency procedures, frequently asked questions, and other cabin-service assistance.

The main objective of the project is to develop an AI-powered virtual assistant that can provide fast, consistent, and accessible passenger support while assisting human cabin crew with repetitive information requests. During emergencies and safety-critical situations, trained human cabin crew remain essential.

## Problem Statement

Passengers may have repetitive questions and requests during air travel, such as flight information, meal services, safety instructions, and general cabin assistance.

The proposed system aims to provide an AI-powered assistant that can respond to common passenger queries and provide relevant information quickly.

## Objectives

- Develop an AI-powered virtual cabin crew assistant.
- Understand passenger queries using Natural Language Processing.
- Provide relevant flight and cabin-service information.
- Provide safety instructions and frequently asked questions.
- Reduce repetitive information requests handled by cabin crew.
- Provide a simple and user-friendly interface.
- Assist human cabin crew rather than replace safety-critical human decision-making.

## Proposed Solution

The AIRHOSTESS WITH AI system provides an interactive interface where passengers can enter or speak their questions.

The system processes the passenger query using AI/NLP techniques, identifies the user's intent, retrieves relevant information, and generates an appropriate response.

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

## UML Diagrams

### Use Case Diagram

The system includes three main actors:

- Passenger
- AI Airhostess System
- Admin

Passenger interactions include asking questions, receiving flight information, requesting cabin assistance, receiving safety instructions, and asking FAQs.

Admin interactions include managing the system, updating information, and monitoring queries.

### Activity Diagram

The basic workflow is:

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
YES → New Query  
NO → END

### Sequence Diagram

Passenger → Application → NLP/AI Model → Knowledge Base → AI Response → Passenger

### Class Diagram

Main classes:

- Passenger
- AIAirHostess
- NLPProcessor
- KnowledgeBase

### Component Diagram

Main components:

- User Interface
- Web Application
- Python Backend
- NLP Processor
- AI/ML Model
- Knowledge Base

## System Architecture

```text
USER / PASSENGER
       |
       v
USER INTERFACE
HTML / CSS / JavaScript
       |
       v
PYTHON APPLICATION
       |
       v
NLP / AI ENGINE
       |
   +---+---+
   |       |
   v       v
ML MODEL  KNOWLEDGE BASE
          Flight / Safety / FAQs
   |       |
   +---+---+
       |
       v
AI RESPONSE
       |
       v
USER / PASSENGER
