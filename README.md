# CarQuest

Full-Stack 'Used-Car Selling Website' for a car business owner built using Django and Bootstrap (HTML, CSS, JavaScipt).

## User-Side Features

- Browse through all the Featured and Latest Cars
- Search and Filter Cars by name, model, location, year, price, etc.
- Register using Email and Password or Login with Google
- Display of all the Car features, Description, Images, etc. when a User clicks on a particular car
- Services and About Us page displaying CarQuest's Services and the Executive Team respectively
- Send Queries about Cars to the Admin
- Can contact the Admin via Email on the Contact Page
- Display of all the queries sent by a user on his/her Dashboard once the user is logged in
- A logged-in user can send atmost one query about a car

## Admin-Side Features

- Customized Django Admin Panel for CarQuest from where Admin can manage the whole website
- Admin can login via superuser's Username and Password
- Admin can view, insert new, edit and delete the team members, users, cars, etc.
- Different Models have been created for User, Team, Contact and Car
- Admin can see all the queries sent by the users in the Contacts Model Tab
- Admin can manage Social Accounts Login through the Admin Panel

## Tech Stack

- **Database**: PostgreSQL
- **Client**: Django, HTML, CSS, JavaScript, Bootstrap Template

## Demo



## Screenshots

![Image 2](https://drive.google.com/uc?export=view&id=1Qu3r7LBjWcr69__xaJvbH62C0kb3Q84l)

![Image 2](https://drive.google.com/uc?export=view&id=1Qu3r7LBjWcr69__xaJvbH62C0kb3Q84l)

![Image 2](https://drive.google.com/uc?export=view&id=1Qu3r7LBjWcr69__xaJvbH62C0kb3Q84l)

![Image 2](https://drive.google.com/uc?export=view&id=1Qu3r7LBjWcr69__xaJvbH62C0kb3Q84l)

![Image 2](https://drive.google.com/uc?export=view&id=1Qu3r7LBjWcr69__xaJvbH62C0kb3Q84l)

![Image 2](https://drive.google.com/uc?export=view&id=1Qu3r7LBjWcr69__xaJvbH62C0kb3Q84l)


## Steps to Run the Website Locally

- Clone this GitHub Repository in your Local Computer
- Open the CarQuest Folder (Root of this project) in your terminal
- Create a Python Virtual Environment and start it
- Install all the python modules and packages listed in the requirements.txt file by using the following command:
 
  ```bash
  pip install -r requirements.txt
  ```
- Set-up PostgreSQl Database and make the necessary changes in the settings.py file of CarQuest Folder
- Run the following commands:
  
   ```bash
  python manage.py makemigrations
  ```
   
   ```bash
  python manage.py migrate
  ```
- Run the Server locally:
   ```bash
  python manage.py runserver
  ```
- Open the link generated in the terminal in any web browser to visit the CarQuest Website

## Feedback

If you have any suggestions or feedback, please reach out to me at rasesh220303@gmail.com
