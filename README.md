# My Unique Blog

My Unique Blog is a simple web application that allows users to share their thoughts and stories through blog posts. Built with Express.js and Pug, the app demonstrates basic CRUD functionality (with create, read, and delete currently implemented) and features a modern, custom-designed user interface.

## Features

- **Create Posts:** Write and publish your own blog post.
- **View Posts:** Browse through all published posts.
- **Post Details:** View the full content of a selected post.
- **Delete Posts:** Remove posts you no longer wish to share.

_Note: You can extend the app by adding update functionality to edit existing posts._

## Project Structure

/my-unique-blog
├── app.js # Main application file (Express server)
├── package.json # Project configuration and dependencies
├── /public # Static assets
│
├── /data
│
│
└── data.json # JSON file to store blog posts
│
└── index.css # Custom CSS styles
├── /views # Pug templates
│
├── layout.pug # Base layout template
│
├── home.pug # Home page template
│
├── blogs.pug # Blog list template
│
├── create.pug # New post creation form
│
└── detail.pug # Post detail view
└── README.md # Project documentation (this file)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/my-unique-blog.git
   ```

2. **Navigate to the project folder:**

   ```bash
   cd my-unique-blog
   ```

3. **Install the dependencies:**
   ```bash
   npm install
   ```

4.**Start the application:**

```bash
node app.js
```

5.**Open the app in your browser:**
Navigate to http://localhost:3000 to view the application.

##Dependencies

- Express.js – A fast, unopinionated, minimalist web framework for Node.js
- Pug – A high-performance template engine for Node.js
