Data [![forthebadge](http://forthebadge.com/images/badges/built-with-ruby.svg)](http://forthebadge.com)
----
A terminal data-controller with dynamic auto-complete features, that is built with ruby. You may want to even store credentials such as Bank Account / Password details - however, do this is at your own risk as anyone who has your unlocked linux machine / has SSH-access to your linux machine can navigate to the `info/` directory generated by the codes, to view all the data. 

INSTALLING REQUIRED GEMS
------------------------
<br> (1) `gem install json` 
<br> (2) `gem install terminal-table`

MAKING THE SCRIPT WORK
----------------------
<br> (1) Type the following commands on a terminal : `cd ~/; git clone git@github.com:athityakumar/data.git`
<br> (2) Install the required gems, as mentioned above. Tested on ruby 2.3.1p112 (2016-04-26 revision 54768)  version.
<br> (3) Now type this in the terminal : `gedit ~/.bashrc`
<br> (4) The shell-script found in this repository as `CopyThis.sh` must be copy-pasted into the `.bashrc` file.
<br> (5) Now, open a new terminal. Have the auto-completion files of `Data` been initialised? Great!
<br> (6) Type `D` and press `Tab`. Yay, it auto-completes to `Data`!  
<br> (7) Continue further by reading through the set of supported auto-complete commands.

SET OF SUPPORTED COMMANDS
-------------------------

- [x] `Data New Tablename` : Creates a new table 'Tablename'. Auto-pushed into the auto-completion script.
- [x] `Data Existing Tablename Column_Add` : Adds more columns to the table 'Tablename'.
- [x] `Data Existing Tablename Column_Edit` : Edits existing columns of table 'Tablename'.
- [x] `Data Existing Tablename Column_Delete` : Deletes a particular column and all data values in that column of table 'Tablename'.
- [x] `Data Existing Tablename Column_Show` : Shows a list of existing columns of table 'Tablename'. Columns 'ID' & 'Date' are inbuilt & cannot be changed by user.
- [x] `Data Existing Tablename Data_Add` : Adds rows of data to the table 'Tablename'.
- [x] `Data Existing Tablename Data_Edit` : Edits existing data values into the selected row of table 'Tablename'.
- [x] `Data Existing Tablename Data_Delete` : Deletes a selected row of values of table 'Tablename'. 
- [x] `Data Existing Tablename Data_Show` : Shows the full tabular form of data stored in table 'Tablename'.
- [x] `Data Delete Tablename` : Deletes table 'Tablename' after asking for confirmation.

EFFECTIVE USE OF SUCH TERMINAL TABLES
-------------------------------------

- [x] `Bookmark` table can be used for offline local storage of favourite websites (without being tracked by browser)
- [x] `Birthday` table can be used for storing birthdays of your friends. 
- [x] `Wallet-History` table can be used for keeping track of expenses with description and in-built `DATE` column. 
- [x] `Monday` / `Tuesday` / ...  tables can be used as a Timetable list for each of the days. (Helpful for students) 
- [x] `Contact` table can be used for storing contact details like `Email ID` , `Contact No.` , etc. of your friends. 

IMPOROVEMENTS
-------------

- [ ] `Data Existing Tablename Column_Search` : Shows all matching columns from table 'Tablename'. Some fuzzy ranking search can be implemented.  
- [ ] `Data Existing Tablename Data_Search` : Shows all matching records from table 'Tablename'. Some fuzzy ranking search can be implemented.
- [ ] `Data Secure Tablename` : Secures the data available in the table 'Tablename' with a password auth.
- [ ] `Data Unsecure Tablename` : Unsecures the data available in the table 'Tablename'.
- [ ] `Data Export Tablename` : Exports the data available in the table 'Tablename' to a CSV file.
- [ ] Use `awesome_print` gem to colorify the response messages based on success / failure.
- [ ] Include the above mentioned terminal-tables as inbuilt tables.

CONTRIBUTION
------------
The work flow is the same as that of any other repository. 
<br> (1) Fork / clone the repository.
<br> (2) Create a new branch , say `my-changes` and make your changes in this branch.
<br> (3) Commit your changes and send a Pull request (PR) to this repository.
<br> Active contributors would be rewarded with the tag of "Collabrators"
<br> Bug fixes , Issues , Issue solutions , Optimizations & Enhancements are always welcome.

LICENSE
-------
The MIT License - [Athitya Kumar](http://github.com/athityakumar) - All Rights Reserved.

