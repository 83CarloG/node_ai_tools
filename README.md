# node_ai_tools

**node_ai_tools** is a demonstration application built with **Node.js** and **TypeScript** to showcase how to integrate **OpenAPI** calls while leveraging multiple external services. This project is ideal for testing "tools" in a Large Language Model (LLM) context.

## Features

1. **Reddit Scraping**  
   Fetch the latest posts from a specific Reddit channel.

2. **Image Generation**  
   Generate personalized images based on text prompts.

3. **Dad Joke API**  
   Retrieve “dad jokes” from an external API to add a playful element to the user experience.

---

### **Purpose**  
This project provides a test environment for exploring how an LLM’s "tools" can interact with external APIs (e.g., Reddit, image generation, Dad Joke API) within a single Node.js/TypeScript application.

---

## Installation

1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd node_ai_tools
   ```

2. Copy the `.env.example` file and rename it to `.env`.  
   Add your `OPENAI_API_KEY` to the `.env` file.

3. Install dependencies:  
   ```bash
   npm install
   ```

4. Start the application with a user prompt:  
   ```bash
   npm run start "user prompt"
   ```

---

## Credits
This project was inspired by **"Build an AI Agent from Scratch"** from [Frontend Masters](https://frontendmasters.com), created by **Scott Moss**.
