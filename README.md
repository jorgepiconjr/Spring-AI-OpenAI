# Java Spring AI - Full Stack Project

Java Spring Boot app using Spring AI Framework (OpenAI Model), exposing a clean REST API (controller–service) for chat, image generation, and cuisine recipe creation, paired with a JavaScript/React front-end User Interface.

## Table of Contents

- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Services Details](#services-details)
- [Key Features](#key-features)
- [Screenshots](#screenshots)

---

## About the Project

Java Spring Boot application integrating Spring AI (OpenAI) with a clean controller–service REST API and a React frontend User Interface. It provides:

- Chat: Conversation Service with optional system prompts.
- Image generation: Service that accepts a prompt and returns up to 4 images.
- Recipe creation: Service that generates structured cooking recipes (title, ingredients with quantities, steps, and optional dietary tags).

Configurable model settings (model name, temperature, max tokens) via application properties and typed DTOs. The React SPA offers dedicated views for Chat, Images, and Recipes, calling the API via fetch/axios, showing loaders and errors, and rendering chat threads, image previews/downloads, and recipe cards in a responsive UI.

## Technologies Used
- Java
- Spring Boot Framework
- Spring AI (OpenAI Model)
- JavaScript & REACT

## Services Details

1. MyAI

- MyAI service contains the implementation of the Backend, that is, the use of Java with Spring Framework implementing Spring AI together with the OpenAI Model.
- MyAI implements a controller-service architecture, where the respective services are Chat, Image, and Recipe Generator, which interact through a REST API with the frontend integrated in JavaScript/React.

2. my-ai-react

- my-ai-react contains the frontend implementation communicating directly with the backend, allowing for pleasant user interaction and providing a pleasant user interface.

## Screenshots

#### Chat
![image_alt](https://github.com/jorgepiconjr/Spring-AI-OpenAI/blob/main/Resources/Chat_Service.png)

#### Image generation 
![image_alt](https://github.com/jorgepiconjr/Spring-AI-OpenAI/blob/main/Resources/Image_Generator_Service.png)

#### Recipe creation
![image_alt](https://github.com/jorgepiconjr/Spring-AI-OpenAI/blob/main/Resources/Recipe_Generator_Service.png)
