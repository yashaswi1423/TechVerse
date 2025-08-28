# TechVerse
A sleek, modern, single-file tech blog template built with vanilla JavaScript. No backend, no build steps—just write and deploy.
# TechVerse: A Modern Single-File Tech Blog

Welcome to **TechVerse**, a clean, modern, and fully self-contained tech blog built entirely within a single `index.html` file. This project is designed for developers who want a simple, maintenance-free platform to share articles and tutorials without the complexity of databases or back-end frameworks.

![TechVerse Blog Screenshot](https://i.imgur.com/7gK7W8c.png)

## ✨ Features

* **Zero Dependencies**: No frameworks, no build steps. Everything is handled with vanilla HTML, CSS, and JavaScript.
* **Content in Code**: Write and manage all your blog posts directly within the `index.html` file.
* **SPA-like Navigation**: Smooth, fast navigation between the article list and individual posts without page reloads.
* **Local Storage Subscriptions**: A functional newsletter subscription form that saves subscriber data to the browser's local storage.
* **Fully Responsive**: A sleek, modern, dark-mode design that looks great on desktops, tablets, and mobile devices.
* **Search Functionality**: Instantly search and filter articles by title, category, author, or content.
* **Easy to Deploy**: Host your entire blog by simply uploading one file to any static hosting provider.

## 🚀 Getting Started

Getting your own version of this blog up and running is incredibly simple.

### Prerequisites

* A modern web browser (like Chrome, Firefox, or Edge).
* A text editor (like VS Code, Sublime Text, or Atom) to edit your content.

### Installation & Usage

1.  **Download the Code**: Clone or download this repository to get the `index.html` file.
    ```bash
    git clone [https://github.com/your-username/techverse-blog.git](https://github.com/your-username/techverse-blog.git)
    ```
2.  **Open `index.html`**: Open the file in your web browser to see the blog in action locally.
3.  **Customize Content**: Open `index.html` in your text editor to start personalizing it.

## ✍️ How to Add a New Blog Post

All blog posts are stored in a JavaScript array called `blogPosts` inside the `<script>` tag at the bottom of the `index.html` file.

1.  Open `index.html` in your text editor.
2.  Scroll down to the `<script>` section.
3.  Find the `const blogPosts = [ ... ];` array.
4.  To add a new post, create a new object using the template below and add it inside the array. If you have multiple posts, make sure they are separated by a comma `,`.

### Post Template

```javascript
{
    slug: 'a-unique-slug-for-the-url',
    title: 'Your Awesome Post Title',
    date: 'August 28, 2025',
    author: 'Your Name',
    category: 'Technology',
    icon: '🚀', // Choose an emoji for the post header
    excerpt: 'A short, engaging summary of your article. This shows up on the main blog page.',
    body: [
        'This is the first paragraph of your blog post.',
        'This is the second paragraph. Each string in the array is a new paragraph.'
    ]
}
