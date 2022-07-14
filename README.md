# Zeal

Zeal was a semester-long project completed as part of the [CSE442: Software Engineering course](https://cse442.com/) at the University at Buffalo. With great emphasis on Agile practices and efficient team coordination, we were able to finish 2 weeks early and achieve the highest possible grade.

## What is Zeal? (Pitch)

Zeal is a teammate and resource finding tool.

Imagine you are joining an event that requires you to create a team, and you feel- “Oh GOD! I really hope I don’t get random bad teammates. I really want to perform well!”, or you have an amazing idea and you are so excited and full of zeal to work on it, but for that, you either need to find team members who already know the skills to execute the idea or you have to learn the skills. Either way, you would be wasting a lot of time and resources researching the technicalities. Finally, if you work for a startup, one of the major fear is to get the right and best people who can work towards the growth and success of your breakthrough ideas. Relatable?

Don’t worry anymore! We have addressed all these issues with Zeal…
We help hackathons and event participants, startups, and individuals with ideas to find worthy team members who can together execute their ideas to reality, instead of wasting precious time researching the technicalities and losing the overall focus. Hence, filling the gap between people with ideas and people who can execute.

## Links

[Live Demo](https://zeal5.herokuapp.com/) (Note: Due to Heroku's free tier, the site may take a minute to wake from sleep.)

[Figma Wireframe](https://www.figma.com/file/aR9EqyzY9YERRAejHNCRDB/Zeal?node-id=0%3A1)

## Screenshots

![zeal5 herokuapp com_(Desktop HD) (1)](https://user-images.githubusercontent.com/54859075/178938157-1316f030-e690-4466-9a1e-2cfbf1f7eaad.png)
![zeal5 herokuapp com_(Desktop HD) (3)](https://user-images.githubusercontent.com/54859075/178938181-91b3f90f-7a7a-49eb-b233-90f606435cfb.png)
![zeal5 herokuapp com_(Desktop HD) (4)](https://user-images.githubusercontent.com/54859075/178938192-e417ff75-acbc-4a3e-8475-6ac98f903735.png)
![zeal5 herokuapp com_(Desktop HD) (2)](https://user-images.githubusercontent.com/54859075/178938199-6cfa7dde-eb22-4d22-b236-2a6695573f37.png)


## Team

1. Prakshal Jain
2. Aleena Sheikh
3. Anthony Robert Feliciano
4. Dominic Sciarrino
5. Tommy Chow

## Setup

1. Backend ([Django](https://www.djangoproject.com/)):
    * Install Virtual Environment: ```pip install pipenv```
    * Start Virtual Environment: ```python3 -m pipenv shell```
    * Go to *zeal_backend* directory: ```cd zeal_backend```
    * Install project dependencies: ```pip install -r requirements.txt```
    * Create Database locally *(db.sqlite3)*: ```python manage.py makemigrations```
    * Apply all changes to Databse *(db.sqlite3)*: ```python manage.py migrate```
    * Running the server: ```python manage.py runserver```

2. Frontend ([React](https://reactjs.org/)): (no virtual environment needed)
    * Go to *zeal_frontend* directory: ```cd zeal_frontend```
    * Check if you have *npm* installed: ```npm --version```
      * If not, download and install [here](https://nodejs.org/en/download/)
    * Install all the dependencies: ```npm install```
    * Start the server: ```npm start```

* Additional notes:
  * The variable name on different systems my vary, for example: `py` or `python` or `python3`
  * If you are unable to start or install virtual install, ignore first 2 steps under *Backend* setup process (point 1 under *Setup* heading).
