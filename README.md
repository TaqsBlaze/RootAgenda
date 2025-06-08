# RootAgenda

**AI-Powered Meeting Agenda & Summary Generator**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![AI Powered](https://img.shields.io/badge/AI%20Powered-FF69B4?style=for-the-badge&logo=dataai&logoColor=white)](https://en.wikipedia.org/wiki/Artificial_intelligence)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

RootAgenda is an intelligent, AI-powered tool designed to streamline your meeting processes from start to finish. It helps you generate clear, structured agendas based on your meeting topics and desired outcomes, and provides concise summaries of your meeting notes, highlighting key decisions and action items. Say goodbye to messy notes and unclear meeting outcomes!


## Features ✨

* **Intelligent Agenda Generation**: Input your meeting topic and desired outcomes, and RootAgenda will generate a structured agenda with suggested time allocations.
* **Concise Meeting Summaries**: Paste your raw meeting notes, and the AI will extract key decisions, action items, and important discussion points.
* **User-Friendly Interface**: A clean, intuitive design built with Tailwind CSS for a seamless user experience.
* **Local-First MVP**: Easily runnable directly in your browser without complex server setups for the initial version.

## How It Works 💡

RootAgenda functions in two primary modes:

1.  **Agenda Generation**:
    * You provide a clear **Meeting Topic** (e.g., "Q3 Marketing Strategy").
    * You list **Desired Outcomes** (e.g., "Decide on budget, Assign tasks, Plan next steps").
    * Clicking "Generate Agenda" uses simple JavaScript logic (simulating AI for this MVP) to construct a structured agenda, including standard meeting sections and dynamic time estimates for your specified outcomes.

2.  **Meeting Summary**:
    * You paste your raw, unstructured **Meeting Notes** into the designated area.
    * Clicking "Summarize Notes" triggers a basic keyword and entity extraction process (the "AI" part in this MVP). It identifies sentences containing action verbs, decisions, and mentions of participants, then compiles them into a concise summary.

## Technologies Used 🛠️

* **HTML5**: Provides the fundamental structure and content of the web application.
* **JavaScript (ES6+)**: Powers the interactive elements, agenda generation logic, and basic "AI" summarization.
* **Tailwind CSS**: A utility-first CSS framework used for rapid and responsive styling, ensuring a modern and attractive user interface.
