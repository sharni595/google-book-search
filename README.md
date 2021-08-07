# google-book-search

## User Story
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

## Description
This app was given to me fully functioning. It used RESTful API's and fetch requests to get data from the back end. I refactored it so that GraphQL is used instead, and deployed it to heroku as a live application. 

## Screenshots

<img width="1427" alt="Screen Shot 2021-08-07 at 9 05 08 am" src="https://user-images.githubusercontent.com/72106865/128604802-574a8e90-d712-4b77-b03c-e1006c053c4d.png">

<img width="1427" alt="Screen Shot 2021-08-07 at 9 05 21 am" src="https://user-images.githubusercontent.com/72106865/128604814-47be0c80-0279-481b-b925-6e18a16391f8.png">

<img width="1426" alt="Screen Shot 2021-08-07 at 9 05 32 am" src="https://user-images.githubusercontent.com/72106865/128604824-f4060629-fd46-40c1-a659-c21c601110ca.png">


## Live URL
https://google-search-v2.herokuapp.com/

#### Note
There is a small bug in this app: When you log in, the first time you go to the saved books section there appears to be nothing. Once you add another book though, all of the saved books will populate on that page. Same goes when a user is first created. The first time a new user adds a book then goes to their saved books, none will appear. But if they redirect to the book search and save another book, all books will populate. 
