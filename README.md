markdown

# Django Blog

## Description
This project is a blog created using the Django framework. It allows for posting articles, commenting on them, and searching through content. The blog also features post sharing via email and tag support for posts.

## Technologies
- Django: A high-level Python Web framework used for building the entire application.
- PostgreSQL: Recommended database for Django projects, leveraging advanced features like full-text search and trigram similarity.
- Bootstrap: A CSS framework used for styling the frontend.
- Django Taggit: A Django addon used for handling tagging for posts.

## Features
- Posting articles with the ability to add tags.
- Commenting on posts by users.
- Searching for posts based on content.
- Pagination of posts.
- Sharing posts via email.
- Generating an RSS feed with the latest posts.
- Sitemap for better SEO.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone git@github.com:Patris08/MyBlog.git

    Navigate to the project folder:

    bash

cd MyBlog

Install required dependencies:

bash

pip install -r requirements.txt

Create and configure the .env file for database settings and other configurations.
Perform database migrations:

bash

python manage.py migrate

Run the development server:

bash

    python manage.py runserver

Usage

    To add a new post, go to the Django admin panel and use the post addition form.
    Use the search form on the homepage to find posts.
    Add a comment to a post using the comment form on the post detail page.

