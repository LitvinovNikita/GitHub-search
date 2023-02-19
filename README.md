# Github-search
The project aims to create an app that allows users to search for GitHub users by their username and view relevant information based on their search. Users should be able to view the app's layout based on their device's screen size and switch between light and dark themes. The app should display error messages and show appropriate text with transparency added if certain fields are empty or not available. Links to website, Twitter, and company information should be included, and the company link should remove the "@" symbol and link to the company page on GitHub.

## Table of contents

- [Challenge](#challenge)
- [Screenshots](#screenshots)
- [Links](#links)
- [Technologies](#technologies)



## Challenge
The app should meet the following requirements:

- Display an optimal layout depending on the user's device screen size
- Show hover states for all interactive elements
- Allow users to search for GitHub users by username
- Show relevant user information based on the search
- Allow users to switch between light and dark themes
- Choose the correct color scheme based on the user's computer preferences
- Persist theme using localStorage
- Use the GitHub users API endpoint, which is https://api.github.com/users/:username , to retrieve user information
- Display an error message if no user is found during a new search
- Show the user's username if their name is not available, with and without the "@" symbol
- Show the text "This profile has no bio" with transparency added if the user's bio is empty
- Show the text "Not Available" with transparency added if the location, website, Twitter, or company properties are empty
- Make website, Twitter, and company information links, and remove the "@" symbol for the company link, leading to the company page on GitHub.

## Screenshots
![image](https://user-images.githubusercontent.com/91351927/219975875-7c44094c-f779-4cc1-8c49-c7486890d045.png)

![image](https://user-images.githubusercontent.com/91351927/219975902-d323e9d9-8ce3-4519-8213-e5226fb813e8.png)

![image](https://user-images.githubusercontent.com/91351927/219975950-9cb54975-5dd9-4e63-80f6-37c09dee349e.png)


## Links
- Live Site URL: (https://litvinovnikita.github.io/Github-search/)
- Solution URL: (https://www.frontendmentor.io/solutions/responsive-github-api-user-search-api-with-darklight-theme-switch-rqG2i-9TT)


## Technologies
- Semantic HTML5 markup: Using HTML elements to give meaning to content and structure web pages in a more accessible and SEO-friendly way.
- CSS custom properties/vars: Declaring reusable variables in CSS to make it easier to maintain and change the look and feel of a website.
- Desktop-first workflow: Designing and developing a website with a focus on the desktop version first, then adapting it for smaller screen sizes using responsive design techniques.
- Javascript: Using a programming language to add interactivity and dynamic behavior to web pages.
- Fetch API: A built-in web API in modern browsers that allows fetching resources and making HTTP requests to servers from a web page.
- GitHub API: An API provided by GitHub that allows developers to access and retrieve data related to GitHub repositories, users, and organizations.
