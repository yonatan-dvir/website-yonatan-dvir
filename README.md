# MyWebsite Project

Welcome to the README file for the My Website project. This project is a personal website where users can learn more about me and leave reviews about the website.

## Description

The MyWebsite project consists of a static website built using HTML, CSS, and JavaScript. It showcases information about me, my portfolio, and provides a form for visitors to leave reviews about the website.

## Filenames (Q1):

- yonatan-dvir.html
- about.html
- education.html
- employment.html
- media.html
- review.html

## Server-Side Functionality (Q4)

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
