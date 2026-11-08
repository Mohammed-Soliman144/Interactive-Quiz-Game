# Interactive Quiz Game

An interactive quiz application built with **HTML5, CSS3, and Vanilla JavaScript**, integrating the [Open Trivia Database (Open Trivia DB)](https://opentdb.com/) REST API to retrieve trivia questions and provide an interactive quiz experience.

The project focuses on applying core JavaScript concepts to a practical browser-based application, including asynchronous API communication, modular code organization, data caching, browser storage, and UI state management.

## Features

- **Dynamic Quiz Questions:** Retrieve trivia questions from the Open Trivia DB REST API.
- **Interactive Quiz Experience:** Display questions and allow users to interact with available answers.
- **API Integration:** Communicate with an external REST API to retrieve quiz data.
- **Data Caching:** Use JavaScript `Map` to cache retrieved data and reduce unnecessary repeated requests.
- **Browser Storage:** Use `localStorage` to maintain relevant application data between sessions.
- **Quiz Status Management:** Manage quiz-related application states.
- **Tab Synchronization:** Handle browser storage events to synchronize relevant state changes between tabs.
- **Modular Architecture:** Organize JavaScript functionality into separate modules for better maintainability.

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure and semantic markup |
| CSS3 | Styling and responsive interface |
| JavaScript (ES6+) | Application logic and interactivity |
| Fetch API | Asynchronous HTTP requests |
| Open Trivia DB | External trivia question source |
| Map | In-memory data caching |
| localStorage | Browser-based data persistence |
| JavaScript Modules | Code organization and separation of concerns |

## Technical Concepts

This project provides practical experience with:

### JavaScript Fundamentals
- Variables, functions, arrays, and objects.
- Array methods and data manipulation.
- ES6+ syntax and modern JavaScript features.
- Modular JavaScript using `import` and `export`.
- Separation of responsibilities across modules.

### Asynchronous JavaScript and API Integration
- Fetch API and HTTP requests.
- Promises and `async/await`.
- Handling asynchronous application workflows.
- Working with JSON responses.
- Integrating a third-party REST API.

### Data Management and Browser APIs
- Using `Map` for in-memory caching.
- Browser `localStorage` for persistent data.
- Handling the `storage` event.
- Managing quiz-related application state.
- Synchronizing relevant changes across browser tabs.

### DOM and Event Handling
- DOM manipulation and dynamic rendering.
- Event listeners and user interactions.
- Updating the interface according to application state.

## Getting Started

### Prerequisites

- A modern web browser.
- Visual Studio Code or another code editor.
- A local development server, such as the Live Server extension for Visual Studio Code.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Mohammed-Soliman144/Interactive-Quiz-Game-Native.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Interactive-Quiz-Game-Native
   ```

3. Open the project using Visual Studio Code.

4. Run the application using Live Server or another local development server.

## External API

This application uses the **Open Trivia Database API** to retrieve trivia questions.

API documentation:

https://opentdb.com/api_config.php

The API provides trivia question data in JSON format, which the application processes and uses to populate the quiz.

## Project Structure

```text
Interactive-Quiz-Game-Native/
│
├── src/
│   ├── styles/
│   ├── scripts/
│   └── ...
│
├── index.html
└── README.md
```

*The structure above is illustrative. Update it to match the actual repository folders and filenames.*


## Future Improvements

- Add more quiz configuration options.
- Expand error handling and user feedback for API failures.
- Improve accessibility and keyboard navigation.
- Add automated tests for application logic.
- Enhance the user experience with additional quiz features.

## Author

**Mohammed Soliman**

- GitHub: [Mohammed-Soliman144](https://github.com/Mohammed-Soliman144)
- LinkedIn: [Muhammad Soliman](https://www.linkedin.com/in/muhammad-soliman144/)
- Portfolio: [Personal Portfolio](https://muhammed-soliman-portfolio.vercel.app)

---