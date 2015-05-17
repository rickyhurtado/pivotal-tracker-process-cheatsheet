# Pivotal Tracker Process Cheatsheet
Project management and GIT Processes with Pivotal Tracker.

#### Epics
  Sample main epics as the main categories of the project:
  
    Website
    App
    API
    Live
    Mobile
    SEO
  
  Sample epics as sub-categories.
  
    Home Page: Banners
    Home Page: Footer
    Home Page: Google Map
    Home Page: Contact
    Home Page: Newsletter
    Registration: Form
    Registration: Banners
    Registration: Ads
    Registration: Newsletter

#### Story Types
  The story types show the expected output of the delivery when the tasks are completed.
  
    Feature - partial feature of a page (with significant value to client)
    Chore - tasks not related in releasing a feature but considered important (less or no significant value to client, example is deployment or code refactoring)
    Release - completion of the main epic or feature
    Bug - any errors or problems found in a feature for aceeptance whether from production or UAT server

#### Points
  This shall measure the difficulty of the feature or tasks. Applies only for Feature story type.
  
    0 - quick feature or task (5-15 minutes)
    1 - easy feature or task (1-2 hours)
    2 - feature or tasks that might require one or two days to complete
    3 - complex feature or tasks that might require five days maximum to complete
  
  If the feature requires more than 3 points, then the feature shall be broken into small feature or task

#### Creating a Story
  When creating a story, do not use phrases or vague words that might lead into confusion or failure of the delivey.
  
###### Story Title
  The story title shall be short and straight forward as much as possible but descriptive enough to understand the feature or task. If the story needs more detailed info, see the Description section below. The following sample story titles is for Registration epic.
  
    Sample story titles for feature story type:
    
    Visitor sees Registration link on the top bar. (top bar of the website)
    Visitor sees a registration page after clicking the Registration link/button. (create a layout view task)
    Visitor fills out the form and submit. (back end process whether the form is processesed via form action or AJAX call)
      API story: Registration form data saves via API.
    Visitor sees form field validations. (back end or JS front end validation)
    Visitor sees a processing message or spinner when the form has been submitted. (JS codes)
    Visitor sees a success message and the fields are hidden. (back end or AJAX response)
    Visitor is redirected to sign in form after successful registration. (JS)
    Visitor receives an email confirmation after successful registration.
    Admin receives an email notification after the visitor's successful email confirmation.
    Visitor sees the set password form after clicking the link from the email confirmation.
    Visitor sees a message that the link from the email confirmation is already used or not valid.
    
    Sample story title for release story type:
    Registration Module Complete
  
###### Description
  If further information about the story title is required, then use the description. This can be instructions, explanations, conditions and scenarios, links, etc. 
