# React Blog Application

## Description

In this assignment, you will create a simple React blog application where users can add, view, and delete blog posts. The application will have a form on the left side for creating new blog posts, and on the right side, it will display all the existing blogs as individual blog cards.

## Requirements

1. The application should have a form on the left side where users can input the title, content, and author of the blog post.
2. The form should have a "Create" button to submit the blog post. Each blog object should have title, content, author, id and createdAt date.
3. After creating a new blog post, it should be displayed on the right side of the page as a blog card.
4. Each blog card should display the title, content, author, and creation date of the blog post.
5. Each blog card should have a "Delete" button to remove the corresponding blog post.
6. Clicking the "Delete" button should remove the blog post from the application and update the displayed blog cards.
7. The application should maintain a list of blog posts in its state.

## User Interface

The user interface should have 3 main components:

1. **Create Form**: This component should include input fields and corresponding states for the blog title, content, and author. Additionally, it should have a "Create" button to submit the form.
2. **All Blogs**: This component should map through all the blogs and render the Blog card component. Remember to pass down the key attribute for react.
3. **Blog Card**: This component should display each blog as individual cards. Each card should contain the title, content, author and creation date of the blog post. Additionally, each card should have a "Delete" button to remove the corresponding blog post.

## Implementation Guidelines

1. Create a React application using `create-react-app`.
2. Set up the basic structure of the application with the required components.
3. Implement the create form component and handle its submission.
4. Store the created blog posts in a state in `App.js`.
5. Display the created blog posts as individual blog cards.
6. Implement the functionality to delete blog posts when the corresponding delete button is clicked.
7. Update the displayed blog cards after deleting a blog post.

Remember to break down the implementation into smaller steps and test each component and functionality as you go. Good luck with your assignment!
