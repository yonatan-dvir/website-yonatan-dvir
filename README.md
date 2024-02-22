# MyWebsite Project

Welcome to the README file for the My Website project. This project is a personal website where users can learn more about me and leave reviews about the website.

## Description

The MyWebsite project consists of a static website built using HTML, CSS, and JavaScript. It showcases information about me, my portfolio, and provides a form for visitors to leave reviews about the website.

## Filenames:

- yonatan-dvir.html
- about.html
- education.html
- employment.html
- media.html
- review.html

## Describe the functionality of my JavaScript code

**The JavaScript code in the home page(yonatan-dvir.html) implements a simple quiz game where users are presented with a series of questions and are required to select the correct answer from a set of options displayed as images. Here's a breakdown of the functionality:**

**Displaying Questions:** The displayQuestion() function is responsible for rendering the current question and its options. It updates the HTML content of elements with the IDs question and options to display the question text and options as images, respectively.

**Selecting an Option:** The selectOption(selectedIndex) function is called when a user clicks on an option image. It highlights the selected option by adding a green border around it and stores the index of the selected option in the selectedAnswerIndex variable.

**Checking the Answer:** The checkAnswer() function compares the selected answer index (selectedAnswerIndex) with the index of the correct answer for the current question. If the selected answer is correct, it displays a success message; otherwise, it displays a failure message.

**Moving to the Next Question:** The nextQuestion() function allows the user to proceed to the next question after answering the current one. However, it first checks if the user has selected the correct answer for the current question. If not, it prompts the user to select the correct option before proceeding. If there are more questions available, it updates the current question index and displays the next question; otherwise, it indicates that the game is over.

## Server-Side Functionality

The website includes a form where visitors can write reviews about the website. The form collects the following information from users:

- Name
- Email
- Rating (1 to 5 stars)
- Review content

**Here's an overview of what the server-side functionality would have done if I added server-side functionality:**

1. Receives the form data submitted by the user via HTTP POST method.
2. Validates the submitted data to ensure it meets required criteria (e.g., all fields filled, valid email format, rating within range).
3. Stores the validated data in a MySQL database dedicated to storing reviews.
4. Provides feedback to the user confirming that their review has been received or displays an error message if issues arise.
5. Optionally triggers a notification mechanism to alert website administrators about the new review.
6. Optionally provides a mechanism to display submitted reviews on the website for other visitors to see.
