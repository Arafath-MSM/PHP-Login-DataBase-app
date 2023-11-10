# Connecting to MySQL in PHP using PDO

Create a Simple Database App: Connecting to MySQL with PHP

### [View the tutorial](https://www.taniarascia.com/create-a-simple-database-app-connecting-to-mysql-with-php/)

## Lessons

- Install database and create table
- Submit users
- Query and filter users

## License

The code is open source and available under the [MIT License](LICENSE.md).


STEP 01: Go to init.sql sheet and write down alter statement to add two new columns (primary
key Eg: songId for Spotify , createdDateTime ) in your primary table.

Instructions
I. Implement all the following steps.
II. Prepare your lab report with the screenshots of your answers.
III. Submit your project folder & lab report (Lab1_RegNo) on or before
given deadline via Teams.
ILO: apply the Query Languages for database definition and manipulation.
Execute the alter table SQL statement to modify your table.

STEP 02: Create a new page called home.php parallel to the create and read pages.

STEP 03: Create a new link for your home page in the index.php file below

STEP 04: Write down an SQL query in home.php file to retrieve and show the last 3 created
entries from your primary table.

STEP 05: Write a PHP/HTML table to display the result from your SELECT statement.
Add a link “View” to go to a new page to view one record. For this you need to create a new
view page (For Spotify it will be viewSong.php) file with URL param I, (Eg:
/yourapp/song/view?songId=123456)

STEP 06: Add an “Edit” button/link from your view page which will go to edit page.
For this add an edit php file (For Spotify its editSong.php) with URL params as in above view.

STEP 07: Make your edit php file, with inputs and “Save” button. Enable facility to modify and
save in the database

