# Model-View-Controller (MVC): Tech Blog

Welcome to the Tech Blog, a CMS-style blog site where developers can share their thoughts, insights, and expertise on various tech-related topics. Whether you're a seasoned coder or just starting your journey, this blog provides a platform for you to publish articles, blog posts, and engage with fellow developers.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## User Story

```md
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Acceptance Criteria

```md
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts
```

## Features

- User-friendly interface for reading and publishing blog posts.
- Secure user authentication with the option to sign up or sign in.
- Posting, editing, and deleting blog articles within the user dashboard.
- Commenting on blog posts to engage with other developers.
- Automatic log-out for added security.

## Technologies Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Handlebars.js](https://handlebarsjs.com/)
- [Sequelize](https://sequelize.org/)
- [MySQL](https://www.mysql.com/)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [express-session](https://www.npmjs.com/package/express-session)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Heroku](https://www.heroku.com/)

## Installation

To run this application locally, you will need to have Node.js and MySQL installed on your computer. Follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/basitmalik97/Tech-Blog
   ```

2. Navigate to the project's root directory:

   ```bash
   cd your-repo-name
   ```

3. Install the required NPM packages:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory to store your MySQL credentials. The file should have the following format:

   ```env
   DB_NAME=your_database_name
   DB_USER=your_database_user
   DB_PASSWORD=your_database_password
   ```

5

. Initialize the database:

   ```bash
   npm run db-init
   ```

6. Start the application:

   ```bash
   npm start
   ```

7. Open your web browser and visit `http://localhost:3001` to access the application.

## Usage

Visit the deployed Tech Blog application at [Heroku Tech Blog](https://your-heroku-app-url) to start writing, reading, and engaging with the developer community.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

- Fork the repository.
- Create a new branch with a descriptive name: `git checkout -b my-feature`
- Make your changes and commit them: `git commit -m 'Add my feature'`
- Push to the branch: `git push origin my-feature`
- Create a pull request, explaining your changes.

## License

This project is licensed under the terms of the [MIT License](LICENSE). Enjoy responsibly!