#About

Simple Prototype Learning Management System Built to Learn about Theming and Sub Theming in Drupal 7

# Instructions:

1. Download Drupal version 7.51

2. Replace the sites folder with the enclosed sites folder

3. Import the Database Dump

  a. Open phpMyAdmin and click on the "Import" tab.

  b. Leave all the default settings and make sure the character set is "utf-8"

  c. Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file we included in our sites/db-backup folder. It's okay to leave it zipped.

  d. Then click the "Go" button on the bottom left.

4. Create the Database User (not needed if using Acquia Dev Desktop)

  a. Lastly, we must recreate the database username/password that Drupal uses to store things in the database. We do this the same way we did when we created the database.

  b. After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

  c. Use the same username and password from before. (If we have forgotten what that was, we can always find that information in settings.php, or in the PDO Exception error message we saw displayed in the browser.)

  d. After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.

#User Stories

#Project Instructions
1.  Build a Zen subtheme

2. Build a Garland subtheme

3. Build a subtheme using a base theme of your choice

4. Include some jQuery in at least one of the above projects

5. Make a subtheme of a subtheme

6. Try themeing Zen Grids and Sass

#What I Learned from this Project
  A. Learned how to create custom themes from scratch in drupal
  B. Learned how to alter existing themes by creating sub themes in drupal


#To Do
 A. Add relationships between users, ie students to parents, teachers etc
 B.  Add assignments and gradebooks
