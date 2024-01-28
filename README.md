# Project 2: Drill & Practice

This application offers a topic list and enables the creation of multiple-choice questions within these topics. These questions are answered by both users themselves and others. Moreover, the application displays fundamental statistics, including the total count of available questions and answered questions. Additionally, it provides an API for retrieving and answering random questions.

## Features
- Display Main Page: Showcase an overview of the application, including statistics on Topics, Questions, and Answers. Provide links for login and register functionalities along with a navigation bar.
- Topic Creation: Implement the ability to create new topics and showcase a list of existing topics.
- Question Management: Enable users to add questions related to specific topics and display a list of questions associated with each topic.
- Answer Options: Allow the addition of multiple-choice answer options for each question and display detailed information about these options.
- Quiz Functionality: Offer a quiz feature with a list of available topics for selection.
- Question and Answer Display: Present questions and answer options with a selection button for user interaction.
- Feedback on Answers: Provide users with feedback indicating whether their chosen answer is correct or incorrect.

## Requirements

- [Deno](https://deno.land/) (v1.35.0 or higher)

## Getting Started

1. **Downlaod Starter code from project submission:**
```https://fitech101.aalto.fi/web-software-development/35-course-project-ii/2-project-submission-and-reviews/
```

2. **Navigate to the project directory:**

```Implement the functionality to the folder drill-and-practice, 
create all controllers,services,views and app.js inside drill-and-practice folder
```

3. **Run the application:**

    ```
    docker-compose up
    ```
## File Structure

- `app.js`: Main application file.
- `database/`: contain databse connection.
- `database/`: contain databse connection.
- `views/`: contain all the eta layout and files.
- `services/`: contain service functionality.
- `controllers/`: contain controller functionality.
- `deps.js/`: contain all the deno dependency.
- `apis/`: contain all the api files.
- `routes.js/`: contain all the routes.
- `static/`: contain all the css files.


## Dependencies

This project uses Deno standard modules and does not require additional dependencies.


### For New Users
If you have never cloned this repository before, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/dasbiplob/Project-2.git
   Navigate to the cloned directory:
   cd Project-1
   Ensure that Docker is installed on your system and running.
   Run the following command:
   docker compose up
   Access your app at http://localhost:7777/.

Deployment
This project is deployed on Render and can be accessed at https://drill-and-practice-webservice.onrender.com/.
