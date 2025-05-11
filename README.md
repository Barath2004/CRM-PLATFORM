# CRM-PLATFORM
customer segmentation
🚀 Local Setup Instructions
1 Clone the repository (or extract from ZIP):
git clone <repo-url>
cd project
2 Install dependencies:
npm install
3 Start the development server:
npm run dev
4 Build for production:
npm run build
5 Architecture Diagram
[Frontend: React + TypeScript]
       |
       | (API calls using OpenAI SDK)
       |
[AI Service Layer: OpenAI GPT API]
       |
       | (Segmentation logic via prompts)
       |
[Customer Data (Static or Dynamic)]
6 Summary of AI Tools and Tech Stack Used
🧠 AI/ML Tools:
OpenAI SDK (openai npm package): Used for customer segmentation logic through prompt-based AI.

⚙️ Technologies:
Frontend:

React 18

React Router

TypeScript

Tailwind CSS

Vite (build tool)

Lucide Icons

react-beautiful-dnd (drag-and-drop UI interactions)

Dev Tools:

ESLint (linting)

PostCSS (CSS transformations)

UUID (for unique identifiers)
7 Known Limitations / Assumptions
No backend or persistent database: All segmentation logic is assumed to happen in-browser or via direct API calls.

API Key handling: OpenAI key must be provided, likely from environment variables or a local config (not secure for production if exposed to frontend).

Limited scalability: AI calls are client-side and could lead to rate limiting or exposure of usage.

Assumes structured customer data: Works best if data is pre-cleaned or statically defined in the UI layer.

