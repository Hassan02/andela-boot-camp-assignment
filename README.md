# andela-boot-camp-assignments
This is an assignment given to us at the Andela bootcamp two-weeks training.

Instructions

Endeavour to do this assignment yourself to gain the full benefit of learning how to use Ruby to solve real life problems.
Note that content surrounded by [ and ] represent placeholder content and should be replaced by the actual content. e.g [NOTE_CONTENT] will represent the actual note content.

Assignment 1
For this assignment you will be creating OOP code required for implementing a note taking application.
Follow the steps listed to complete the assignment.
1. Create a class classed NotesApplication . Use modules for namespacing.
2. Create a constructor that does the following
a. Takes in a parameter author as the author of the note and saves this as an instance
variable.
b. Create a notes list to store all the notes as an instance property.
3. Create the following functionality for the NotesApplication class
a. create(note_content) - This function takes the note content as the parameter and
adds it to the notes list of the object.
b. list() - This function lists out each of the notes in the notes list in the following format.
The note_id parameter below represents the respective index of each of the items in the
list, the NOTE_CONTENT represent the note content and the author represents the note
author.
Note ID: [note_id]
[NOTE_CONTENT]
By Author [author]
c. get(note_id) - This function takes a note_id which refers to the index of the note in
the notes list and returns the content of that note as a string.
d. search(search_text) - This function takes a search string, search_text and returns all
the notes with that text within it in the following format
0
Showing results for search ‘[<search_text>]’
Note ID: [note_id]
[NOTE_CONTENT]
By Author [author]
e. delete(note_id) - This function deletes the note at the index note_id of the notes list.
f. edit(note_id, new_content) - This function replaces the content in the note at
note_id with new_content .
Ensure to put in the necessary validation every step of the way.

Assignment 2 - Test Driven Development
For this assignment you are required to write tests for the class you just created. Ensure to create at least
20 test cases that tests as much of the functionality as you can. Remember to test edge cases as well as
abnormal input. You can make use of either MiniTest or Rspec.

Assignment 3 - Version Control
For this assignment you are required to make use of version control to version your application. Make
use of Github to host your code.

Optional: Make use of Branches
Assignment 4 (Optional)
For this assignment, you will be required to create a command line interface that makes use of the class
you just created to build an interactive experience for users using the application.
