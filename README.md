# 🧠 AI Code Reviewer (Powered by Google Gemini AI)

AI Code Reviewer is an intelligent code analysis tool built to help developers write cleaner, optimized, and production-ready code.

It analyzes source code using Google Gemini AI, detects issues, suggests improvements, and returns structured feedback to enhance performance, readability, and maintainability.

# 🚀 Key Features

🔍 Error Detection – Identifies syntax, logical, and anti-pattern issues

🌱 Best Practices Compliance – Follows industry coding standards

⚡ Performance Optimization – Suggests faster and efficient solutions

♻️ Scalability & Maintainability – Improves long-term code health

🧾 Structured AI Feedback – Clear sections with summary, issues, and fixes

#  Tech Stack =>

| Layer           | Technology                                |
| --------------- | ----------------------------------------- |
| **Frontend**    | React (Vite), PrismJS, Simple Code Editor |
| **Backend**     | Node.js, Express.js                       |
| **AI Model**    | Google Gemini API                         |
| **HTTP Client** | Axios                                     |


# 📤 Output Format (AI Response)

✅ Overall Summary

💪 Code Strengths

⚠️ Issues / Bugs Found

🛠 Suggested Improvements

💡 Refactored / Improved Code Examples

# Installation and Setup =>

Clone the repository

git clone https://github.com/your-username/ai-code-reviewer.git

Navigate to project

cd ai-code-reviewer

# Install Dependencies => 

@ cd frontend => npm init => 

import Editor from "react-simple-code-editor";

import Prism from "prismjs";

import "prismjs/themes/prism-tomorrow.css";

import axios from "axios";

import Markdown from 'react-markdown';

import rehypeHighlight from "rehype-highlight";

import "highlight.js/styles/github-dark.css";

@ cd backend => npm init => 

const express = require("express");

const cors = require("cors");

@ Create .env File in your backend and put these informations init

PORT = 5000

GEMINI_API_KEY=your_google_gemini_key


