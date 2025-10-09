# AI Code Reviewer

AI Code Reviewer is an intelligent code analysis tool powered by Google Gemini AI, 
built to help developers write cleaner, more efficient, and production-ready code. 
It detects issues, recommends improvements, and returns structured feedback to enhance performance, 
readability, and maintainability.

@ Features => 

🔍 Error Detection – Finds syntax and logical issues

🌱 Best Practices – Follows industry coding standards

⚡ Performance Optimization

♻️ Scalability & Maintainability Insights

🧾 Readable & Structured AI Feedback

@ Tech Stack =>

Frontend    => React(Vite) , PrismJS , Simple Code Editor

Backend     => Node.js , Express.js

AI model    => Google Gemini API

HTTP Client => Axios

@ Output Format =>

📌 Overall Summary

💪 Strengths in Your Code

⚠️ Issues / Bugs Found

🛠 Suggested Improvements

💡 Improved Code Examples

@ Installation and Steup =>

git clone https://github.com/your-username/ai-code-reviewer.git

cd ai-code-reviewer

@ Install Dependencies => 
@ cd frontend => npm init => 

import { useState, useEffect } from 'react';

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


