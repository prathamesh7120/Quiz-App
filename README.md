# Simple Quiz App

This is a simple quiz app built with HTML, CSS, and JavaScript. The app consists of a single HTML file (`index.html`) and a JavaScript file (`script.js`).

### Step 1: HTML Structure

The HTML file (`index.html`) contains the basic structure of the app, including the header, the quiz container, and the buttons.

This is a simple quiz app built with HTML, CSS, and JavaScript. The app consists of a series of multiple-choice questions, and the user can navigate through the questions using the "Next" button. The app provides feedback to the user on whether their answer is correct or incorrect.

### Step-by-Step Explanation

#### HTML

The HTML code defines the structure of the app. The `<body>` element contains the entire content of the app, and the `<div class="app">` element is the main container for the app's content.

The `<div class="quiz">` element contains the questions and answers. Each question is wrapped in an `<h2>` element, and each answer is wrapped in a `<button>` element. The `<button>` elements have the `data-correct` attribute, which is used to determine whether the answer is correct or incorrect.

The `<div id="next-btn">` element is the "Next" button. It is initially hidden, and it is displayed when the user has answered all of the questions.

#### CSS

The CSS code defines the styling of the app. The `body` element has a background color of #001e4d, and the `.app` element has a background color of #fff. The `.quiz` element has a padding of 20px 0, and the `<h2>` elements have a font-size of 18px and a color of #001e4d.

The `.btn` elements have a background color of #fff, a color of #222, a font-weight of 500, a width of 100%, a border of 1px solid #222, a padding of 10px, a margin of 10px 0, a text-align of left, a border-radius of 4px, and a cursor of pointer. The `.btn:hover:not([disabled])` elements have a background color of #222 and a color of #fff. The `.btn:disabled` elements have a cursor of no-drop.

The `#next-btn` element has a background color of #001e4d, a color of #fff, a font-weight of 500, a width of 150px, a border of 0, a padding of 10px, a margin of 

This is a simple quiz app that presents multiple-choice questions to the user and provides immediate feedback on their answers. The app keeps track of the user's score and displays it at the end of the quiz.

## Code Overview

The code is written in JavaScript and uses the DOM to create and manipulate the user interface. The main logic of the app is contained in the `startQuiz()` function, which initializes the quiz and displays the first question.

The `#question` element will display the question text, the `#answer-buttons` element will contain the answer buttons, and the `#next-btn` button will be used to navigate to the next question.


