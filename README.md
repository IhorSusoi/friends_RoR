markdown
Copy code
# Friends_RoR

This project is a simple Ruby on Rails application that allows users to manage their friends list.

## Installation

To run this application, make sure you have Ruby and Ruby on Rails installed. Clone this repository to your local machine:

```sh
git clone https://github.com/IhorSusoi/friends_RoR.git
Then, navigate to the project directory and install the required gems:

sh
Copy code
bundle install
After the installation is complete, set up the database with the necessary migrations:

sh
Copy code
rails db:migrate
You can then start the Rails server:

sh
Copy code
rails server
The application will be available at http://localhost:3000.

Usage
This application allows users to perform the following actions:

Create, read, update, and delete friends.
View a list of all friends.
Search for specific friends by name.
Documentation
Models
Friend
The Friend model represents a user's friend and includes the following attributes:

name: A string that stores the friend's name.
email: A string that stores the friend's email address.
phone: A string that stores the friend's phone number.
Controllers
FriendsController
The FriendsController manages the CRUD operations for the Friend model. It includes the following actions:

index: Lists all friends.
show: Displays a specific friend.
new: Renders the form for creating a new friend.
create: Creates a new friend.
edit: Renders the form for editing a friend.
update: Updates a friend.
destroy: Deletes a friend.
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

License
MIT

vbnet
Copy code

Feel free to modify this template to match the specifics of your project. Add or remove sections as needed, and ensure that the documentation accurately represents the structure and features of your Ruby on Rails application.