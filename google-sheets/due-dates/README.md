# Canvas Due Dates

The [Course Due Dates](https://docs.google.com/spreadsheets/d/1WuDBOKE0CBZy8wus2gaZN2R1iKYBwZsxMhJYGQsKaeE/edit?usp=sharing) Google Sheet will list all the due dates for a course on a single page so that you can edit them in one spot.

You will need to be logged into your Google Account to run this.

This script adds a new menu to Google Sheets called **Canvas**

1. Open the spreadsheet
2. Go to the File menu and ***Make a Copy*** for yourself.
3. In your new copy, go to the File menu and choose ***Spreadsheet Settings*** to double check your timezone.
4. Go to the Canvas menu and choose ***Configure API Settings***. Enter your Canvas instance and access token
5. Choose ***Specify Course*** from the Canvas menu. You may enter the Canvas course ID or you may copy/paste a course URL.
6. Choose ***Load Due Dates*** from the Canvas menu.
7. Edit the spreadsheet to change the dates
8. Choose ***Save Due Dates*** from the Canvas menu.

## Notes
You should be able to delete columns from the data page or reorder them. In theory, it should work. In practice, you may want to leave them alone.

Feel free to sort the data in whatever order you want. The default is by due date and then assignment name.

Show Answers and Hide Answers are only valid for quizzes and then only if "Show Correct Answers at" is checked inside Canvas.

Do NOT delete the Due, Type, or Canvas ID columns, bad things (or perhaps nothing) will happen.
