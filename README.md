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

- [Demo Video 1](https://drive.google.com/file/d/1esX12Z4CGZdIlHL4P8K0QWHhmg_yObQN/view?usp=sharing)
- [Demo Video 2](https://drive.google.com/file/d/1gWI4OzfA7n9BXmwoJf3TBS_mVgUycfl_/view?usp=sharing)
- [Demo Video 3](https://drive.google.com/file/d/1AbqJ2D2jHL0cB0ZCkxV-yaMNIQohJcLG/view?usp=sharing)
- [Demo Video 4](https://drive.google.com/file/d/1_o0BD-JLbP4Nv81ZnPzxD3aodjaMZ8Oi/view?usp=sharing)
- [Demo Video 5](https://drive.google.com/file/d/1JoyEZ265mUz3Ulx4KlTXaGC3dMTjJvWz/view?usp=sharing)
- [Demo Video 6](https://drive.google.com/file/d/1xZoI7qk-_ZJ8Chd2mlTh2Q3CGnGU6MIN/view?usp=sharing)

## Screenshots

- [All Screenshots](https://drive.google.com/drive/folders/1r6BWLZf7pcqhgBeGX2-Yi6_h_AJT1m21?usp=sharing)

![Home](https://drive.google.com/uc?export=view&id=1kovt-z3PebJUuuUzL7Uv_uWKkvKxPG8Y)

![Featured Cars](https://drive.google.com/uc?export=view&id=15d814sDVSdNQiR-prsXd8E9vZ6Uy7vhu)

![Latest Cars](https://drive.google.com/uc?export=view&id=1Yw6NvHaVk7rjzNE8UKv5PqRq_Iuk2nL9)

![Cars](https://drive.google.com/uc?export=view&id=1injsGlloBJ13R6sWyGRl3rXq03yDpGXo)

![admin 1](https://drive.google.com/uc?export=view&id=1sj9rGZnBIENPVh2jKsT4xX_kfkzjI5ke)

![admin 2](https://drive.google.com/uc?export=view&id=1xF6__cSbq-yiXzyxHBOQk08RWSoMBoh9)

![Car Detail](https://drive.google.com/uc?export=view&id=19WEITaL5aixPUGyOr25NWbf9jQnQPYPv)

![Query Form](https://drive.google.com/uc?export=view&id=1w_GMWU3TjaO1-i8qShouGrq_3GcB_lwq)

![Contact Us](https://drive.google.com/uc?export=view&id=1PekIZrLkKXBqkx8J7U4eLFELZl-1zmD2)

![Register](https://drive.google.com/uc?export=view&id=1E8thTV4qZizRyuOd-2y4xJ8OLpB0okqm)

![Email](https://drive.google.com/uc?export=view&id=1S0wHy-8LeNTQC9mWzNTUR_CwOpMIEmk2)

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
