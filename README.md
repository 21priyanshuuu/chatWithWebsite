![Screenshot 2024-10-10 214615](https://github.com/user-attachments/assets/38d5b3ad-c850-4d81-9eb7-0c3b509674ef)
A complete project example with RAGChat & Next.js 14



Ask This Website

This project allows you to chat with any website using a modern AI-powered approach. Simply prepend "localhost:3000" (or your hosted domain) to any website URL, and the app fetches and interacts with the content of that site. You can ask questions about any website's content, whether it's Wikipedia or another source, using a new package, `@upstash/ragchat`, to integrate AI.

Features:
- Dynamic URL routing using Next.js App Router.
- Automatically fetch and index webpage content.
- AI-powered querying with Upstash's RAG (Retrieval-Augmented Generation) Chat.
- Free-tier with no credit card needed for setup.
- Built-in support for OpenAI-like models using Upstash hosted models.

Tech Stack:
- **Next.js**: For creating the frontend with dynamic routes and middleware.
- **Bun/NPM/Yarn**: For managing packages and running the app.
- **Tailwind CSS**: For styling (optional based on user preference).
- **Upstash RAG Chat**: To easily create AI chat interactions.

Steps to Get Started:
1. Clone the repo and install dependencies using your preferred package manager (Bun/NPM/Yarn).
2. Set up the Next.js project using `npx create-next-app@latest`.
3. Use Upstash's RAG chat package to index HTML content and ask questions.
4. The project works out-of-the-box without needing an OpenAI API key.

This project is perfect for beginners to learn dynamic routing, middleware, and AI integration using Next.js and modern libraries.
