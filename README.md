# one-minute-pitch

This  is a flask application that allows users to post one minute pitches and also allows other users who have signed up to comment and upvote or downvote
a pitch. It also allows a person to signup to be able to access the functionalities of the application

## Live Link
[View Site]()

## Screenshot

<img src="">

## User Stories

* Comment on the different pitches posted py other uses.
* See the pitches posted by other uses.
* Vote on s pitch they have viwed by giving it a upvote or a downvote.
* Register to be allowed to log in to the application
* View pitches from the different categories.
* Submit a pitch to a specific category of their choice.

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all posts, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with app pitches based on categories and commenting section|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|



### Prerequisites

* Python 3.8

## Running the Application
* To run the application, in your terminal:

        $ python3 manage.py server
      
        
## Testing the Application
* To run the tests for the class file and check if it functions well:

        $ cd tests
        $ python3 user_test.py
        


## Built With

* [Python](https://www.python.org/) for backend
* [HTML](https://html.com/) for web app structure
* [Bootstrap](https://getbootstrap.com/) and [Javascript](https://www.javascript.com/) for styling
* [Heroku](https://heroku.com)

## Authors

* **Victor  Kibocha** - *Initial work* - [Github](https://github.com/TechVictorKE/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspired by Moringa School
