# 🤖 AI Todo Agent

An AI-powered Todo List Assistant that allows users to manage their tasks using natural language.

Instead of interacting with a traditional Todo UI, users can simply tell the assistant what they want to do. The AI understands the user's request, selects the appropriate tool, performs the required database operation, and returns a natural-language response.

For example:

> "Add a task to revise Python today."

> "Do I have any tasks related to Python?"

> "Show me all my tasks."

> "Delete task with ID 3."

---

## ✨ Features

- 📝 Create new todos using natural language
- 📋 Retrieve all todos from the database
- 🔍 Search todos using keywords or phrases
- 🗑️ Delete todos by ID
- 🤖 AI-powered tool selection
- 💬 Interactive command-line interface
- 🗄️ PostgreSQL database integration
- ⚡ Drizzle ORM for database operations
- 🔐 Environment variables for sensitive configuration

---

## 🧠 How It Works

The project follows a simple AI Agent workflow:

```text
User
  ↓
Natural Language Request
  ↓
OpenAI Model
  ↓
Understand the Request
  ↓
Select Appropriate Tool
  ↓
JavaScript Function
  ↓
Drizzle ORM
  ↓
PostgreSQL
  ↓
Observation
  ↓
AI Generates Final Response
  ↓
User