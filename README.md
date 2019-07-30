This plunker is a small exercise that we have put together in an effort to evaluate your problem solving skills.

In order to send your work to us, please click "Fork", make your edits / additions, click on "Save" then send us the plunker link
as well as a zip file containing your files which can be downloaded from plunker using the "Download your Plunk as zip file" icon in the upper right area of the screen.
 
Before you get started with this exercise, there are two bugs that we would like to have resolved before you begin adding new features.  
The header title should say "Davey Resource Group" and the grid itself should be loaded with the data contained in data.json file
 
To start, we have provided you with a base which implements Angular's UI Grid.
Some features this application should have:

    Sorting
    
    Pagination
    
    Filtering
    
    Add data to the grid
    
    Remove data from the grid
    
    Edit data shown by the grid
    
    Validation on the edit / add.  If I set the tree to be a species that is not “vacant” then DBH must be > 0 and Condition <> “N/A”.
    You can do this via a check when the user submits the form, it doesn’t need to be real time validation (bonus points if it is!).
    
    A report (HTML table is fine) that outputs trees that have a duplicate “site number”.  
    We have a tree locating mechanism where Address, Street, Side, and Site number (columns B,C,D,E in sheet) cannot be duplicated.  
    That is, those four values combined are unique to the dataset.  Create a report that alerts the user to the duplicate records. 
    (bonus points if there is a link in the report that allows me to correct the problem record by loading it into the edit form.)

Extra features this table could have:
    Column Hiding
    Exporting to csv, pdf
 
You don’t have to make the site look too fancy, we are mostly focusing on functionality. 
We would, however, like to see this application demonstrate your abilities in usability. 
Bonus points if it is mobile friendly.

We would like to see your source code as well, so please send it after you have completed the exercise (see top for instructions).