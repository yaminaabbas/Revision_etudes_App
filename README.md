

### Application de " Révision des études "


**User Stories**
- When I start up the application, I am given a choice between the following options:
    - Begin a review session
    - Add a new question to the list
- If I choose to add a new question, I am asked to provide:
    - The question text
    - A list of possible responses separated by commas
    - Designation of which response is correct
    - A list of topic tags separated by commas
- If I choose to start a review session:
    - The program presents a random question from the question list
    - I am provided the question text and all response options with labels 
    - I am prompted to provide my response using the labels presented
    - The program informs me of the correct answer
    - I am prompted to choose whether to continue the session or quit

**Technical requirements**
- Store the list of created questions in a .csv file
- Load the previously created questions when the user initializes the application
