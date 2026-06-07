# FitLife Blog

## What I Plan to Build

- A homepage listing all blog posts with titles, categories, and short descriptions
- A post detail page showing the full article and reader comments
- A comment submission form for visitors (no account required)
- An admin login page to access the dashboard
- An admin dashboard to create, edit, and delete posts and manage comments

## Technology I Will Use

- Frontend: HTML, CSS, Bootstrap, JavaScript
- Backend: PHP
- Database: MySQL

## Pages I Will Create

- index.php       → Homepage (post listing)
- post.php        → Single post + comments
- about.php       → About page
- admin/login.php → Admin login
- admin/dashboard.php → Manage posts

## Rendering Approach
Pages are rendered server-side using PHP, which queries MySQL
and returns complete HTML to the browser. No frontend framework is used.

## Content Storage
Post content is stored as plain HTML via a textarea form input.
5–8 sample posts will be pre-loaded directly into the database.
