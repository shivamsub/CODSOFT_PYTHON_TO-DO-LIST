# CODSOFT_PYTHON_TO-DO-LIST
Python project for a user-friendly To-Do List.

1. Importing Modules
   - We import the Tkinter module which is used to create a user-friendly GUI.
   - We also import the messagebox from Tkinter which is used to display messages and warnings.

2. Initializing Window
   - We then create the user interface window as well as set an empty list.
   - The empty list is used to store the to-do list values.

3. Function to Add Task
   - We create a function named 'add_task' to add tasks to the list.
   - The function gets the value entered by the user in the entry box.
   - This value is then inserted into the list.
   - If no value was entered a warning message is displayed.
  
4. Function to Delete Task
   - We create a function named 'delete_task' to delete tasks from the list.
   - We use a cursor to select the item from the list and deletes the item.
   - If no items are selected a warning message is displayed.
  
5. Function to Edit Task
   - We create a function named 'edit_task' to edit task from the list.
   - The cursor selects the item to be edited. If no item is selected a message box is displayed.
   - When a task is selected and the new value is entered and edit task button is clicked the new value gets added to the list.
   - If no value is entered after selecting the task, a messagebox is displayed.
  
6. Function to Exit
   - This button destroys the window completely once the exit button is clicked.

7. Setting up the window.
   - We set up the window title, size, and background.
   - We then add headings,, scrollbar, and listbox to the frame.
   - We then create buttons for each of the functions that have been created.
   - At the end, we loop the window so that it doesnt close until destroyed.
