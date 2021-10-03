# Griffin Hadfield
This repos is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1: Docker Installation
<img width="683" alt="Screen Shot 2021-10-03 at 10 45 19 AM" src="https://user-images.githubusercontent.com/38739044/135759668-c3c0f3be-a21a-4ef0-aace-9f2166dd5096.png">

## Activity 2: Cloning EP Repo 
<img width="1277" alt="Screen Shot 2021-10-03 at 10 51 32 AM" src="https://user-images.githubusercontent.com/38739044/135759752-052b59a4-4f49-4809-b5d4-da2317ad678b.png">

## Activity 3: Building Docker Image 
<img width="1066" alt="Screen Shot 2021-10-03 at 10 56 57 AM" src="https://user-images.githubusercontent.com/38739044/135759754-04ff0149-6518-4d1a-9258-4f92a58ff700.png">

## Activity 4: Running Docker Image
<img width="1088" alt="Screen Shot 2021-10-03 at 11 04 22 AM" src="https://user-images.githubusercontent.com/38739044/135759907-c47e6e37-8168-4524-ade3-4b45d68d89b4.png">

## Activity 5: Feedback on Education Pathways

One functional requirement that I would like to see improved in the application is the ability to save or keep track of courses. When using the tool to search for different courses, it would be useful to be able to shortlist courses that I may be interested in and return to them at a later time. If I were to use this tool, I could see myself needing to manually record the courses I want to take, so a feature to handle this for me would be a useful inclusion.

One non-functional requirement that I think could be improved is the formatting and readbility of the text and information that is displayed. Currently, all of the text is black and displayed on a plain white background with no visual elements to seperate them. I found myself confused as to what text pertains to which column or element on the page. It would be useful to add different lines or multiple colours of background shading to add visual seperation and distinction in the content.


# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
