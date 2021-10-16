# Maxim Stepanov
## This repo is a clone of the https://github.com/nelaturuk/education_pathways repository

# Activity 1

![activity1Proof](https://github.com/maxsteep/ECE444-F2021-Lab5/blob/styling-practice/activity1Proof.png?raw=true)

# Activity 2-5

![activity2Proof](https://github.com/maxsteep/ECE444-F2021-Lab5/blob/styling-practice/homePage1.png?raw=true)
![activity3Proof](https://github.com/maxsteep/ECE444-F2021-Lab5/blob/styling-practice/homePage2.png?raw=true)
![activity4Proof](https://github.com/maxsteep/ECE444-F2021-Lab5/blob/styling-practice/resultsPageForm.png?raw=true)
![activity5Proof](https://github.com/maxsteep/ECE444-F2021-Lab5/blob/styling-practice/resultsPageResultsTable.png?raw=true)

# Activity 6
The re-design features both improved and non-optimal changes to the design. The one particular comparison to be drawn is the much-improved design of the 'common-page-form' search control module.
The judicious element spacing, presentation, and the overall layout of the serach module is improved in terms of user friendliness and colour design.
The new design uses colour scheme and element highlighting to aid visual navigation of the module and improve upon the rapidity of the interaction for the end users.


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
