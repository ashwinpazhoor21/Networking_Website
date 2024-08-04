# Networking Website (Similar to Twitter and Facebook)

## Description
This project is a social media website with functionalities similar to Twitter and Facebook. It was created as a personal project to explore web development concepts.

## Folder Structure

- **idea**: Contains configuration files such as `*.gitignore`, `misc.xml`, `modules.xml`, and `vcs.xml`. These files support the development environment and project configuration.

- **inspectionProfiles**: Includes network settings files for real-time page rendering.

- **network.xml**: Integrates Django aspects into the project.

- **misc.xml**: Contains JavaScript settings to enable automatic page refresh for likes and other interactions.

- **modules.xml**: Imports settings to run the project with `python3 manage.py runserver`.

- **vcs.xml**: Manages project mapping for Django components.

- **.vscode**: Configuration files for Visual Studio Code.

- **network**: Stores `_pycache_` files generated during local project runs.

- **migrations**: Contains migration files and additional `_pycache_` files.

- **static/network**: Includes all images and the `network.js` file, which handles JavaScript elements like automatic content updates.

- **templates/network**: Holds all HTML files and associated Python files for displaying content and handling user authentication.
  - **following.html**: Displays posts from followed users.
  - **index.html**: The main HTML file linking all components.
  - **layout.html**: Defines the overall layout and design of the application.
  - **login.html**: Manages user login functionality.
  - **profile.html**: Displays user profile information.
  - **register.html**: Handles user registration.

- **project4**: Contains additional Django-related files and configurations.

- **manage.py**: The primary file for running the project and managing commands.

- **db.sqlite3**: The database file storing all posts and user data.

## Reflection
Working on this project taught me valuable skills in web development, including setting up a Django environment, handling front-end and back-end interactions, and managing data storage. I learned the importance of a well-structured codebase and the nuances of creating a responsive user interface. This experience also deepened my understanding of JavaScript and Python, particularly in the context of real-time web applications. Overall, this project was a practical exercise in integrating various technologies to build a functional social media platform.