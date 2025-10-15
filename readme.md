# Smart Task Planner

A simple AI-powered tool to break down user goals into actionable tasks with timelines.

## Overview
This project uses a Node.js backend with Express to process goals via an LLM (e.g., GEMINI FLASH-2.0). It includes a basic frontend for user interaction.

## Setup
1. Clone the repo: `git clone https://github.com/bhargav8985/smart-task-planner`
2. Install dependencies: `npm install`
3. Create a `.env` file with your GEMINI API key: `GEMINI_API_KEY=your_key_here`
4. Start the server: `node server.js`
5. Open http://localhost:3000 in your browser.

## Usage
- Enter a goal in the form and click "Generate Plan".
- View the breakdown of tasks, deadlines, and dependencies.

## API Endpoints
- **POST /api/generate-plan**: Send a JSON body like `{ "goal": "Your goal here" }` to get the task plan.


