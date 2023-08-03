# Book-Search-Engine
## Description
 
Transform an operational Google Books API search engine, which was implemented using a RESTful API, into a GraphQL API utilizing Apollo Server. The original application was developed using the MERN stack, featuring a React front end, MongoDB database, and Node.js/Express.js server and API.

## Usage 

The search engine displays a menu with options for searching books and logging in or signing up. When users search for books without logging in, they receive search results with book details and links. Clicking navigation titles reveals corresponding sections without page reloads. In the Login/Signup option, a modal appears, allowing users to log in or sign up. Signing up requires a username, email, and password, while logging in requires an email and password. Successful signup or login leads to account access. Logged-in users see options to search books, view saved books, and logout. When searching while logged in, users see save buttons for each book, allowing them to store book information in their account. Accessing the saved books section displays all saved books with options to remove individual books. The Logout button logs users out and brings them back to the initial menu.
