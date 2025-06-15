# To-Do-List
It is a basic todo list that is used to organize tasks
# To-Do-List Snippet
![Screenshot (33)](https://github.com/user-attachments/assets/59cc03b0-1d37-42a4-9bb9-d036401145b9)
# Testing Guidance
  -> Run the app:
    npm install
    npm run dev    # if using Vite
# Features
# ✅ Basic Functionality Tests
     1) Add Task

       . Enter a task and click Add

       . ✔️ Task appears in the list

     2)  Validation

       . Click Add without typing anything

       . ✔️ Alert appears: "Task cannot be empty."

     3)  Mark as Complete

       .  Click on a task text

       .✔️ Text gets strikethrough and turns gray

     4)  Delete Task

       . Click the Delete button next to a task

       . ✔️ Task is removed from the list

# ✅ Filter Test
    .Change filter dropdown to:

       . All → Shows all tasks

       .  Active → Shows only unchecked tasks

       .  Completed → Shows only checked tasks

# ✅ Persistence (localStorage)
   1) Add a few tasks

   2) Refresh the page

   3) ✔️ Tasks should still be visible (persisted in localStorage





