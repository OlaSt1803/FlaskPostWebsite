# FlaskPostWebsite
This is a simple blogging application built using Flask and SQLite. It allows users to create, edit, delete, and view blog posts. The application demonstrates fundamental concepts of web development with Flask, including routing, templating, and database interactions.
# Features
- View Posts: Users can see a list of all blog posts on the homepage.
- Create Posts: Users can create new blog posts by filling out a title and content.
- Edit Posts: Users can edit existing blog posts.
- Delete Posts: Users can delete blog posts, with a confirmation message upon successful deletion.
- Dynamic Routing: Each post has a unique URL for direct access.
# Technologies Used
- Flask: A lightweight WSGI web application framework in Python.
- SQLite: A lightweight, disk-based database that doesn’t require a separate server process.
- HTML/CSS: For rendering the frontend of the application.
# Installation
1. Clone this repository to your local machine.
2. Ensure you have Python installed.
3. Install the required packages:
  pip install Flask
4. Create the database by executing the necessary SQL commands to set up the posts table (see SQL commands below).
5. Run the application:
    python app.py
6. Open your web browser and navigate to http://127.0.0.1:5000
