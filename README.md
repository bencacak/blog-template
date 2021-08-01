# blog-template
## This is a template for a basic blog site using Boostrap and custom CSS for styling.

### To create a new post:

1. Create a `<title-of-post>` folder in your desired location in the `blog-posts` folder. 
    - I have it organized by year. So posts written in 2021 will be in the `2021` folder. You can organize this however you want.
2. Inside your new `<title-of-post>` folder, creat a post.html file. Copy and paste the mark-up in `blog-post.template.html` found in the `assets` folder of the main directory.
3. Fill in your meta-date as need in the head, and re-title the `<h1>` and `<h2>` tags.
    - **Note:** The breadcrumb at the top of the article will auto-populate from the content inside the `<h1>` tag. This is what `breadcrumbScript.js` does.
4. Fill out your article with whatever you want to write.
5. In `index.html`, copy and paste the commented out `<section>` tag and link your new post.