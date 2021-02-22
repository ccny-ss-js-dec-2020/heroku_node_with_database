## Heroku Node With Database
* Watch [this](https://www.youtube.com/watch?v=tmtw26OPOac) video that goes through all of the instructions below
1. Push code to Github
2. Run ```heroku create```
3. Run ```heroku addons:create jawsdb:kitefin``` (https://elements.heroku.com/addons/jawsdb)
4. Run ```git push heroku master```
5. Go to your jaws db database credentials through the Heroku UI
6. Connect to your jaws db in your Database GUI (MySQL Workbench, MySQL Developer, VS Code MySQL Plugin, Atom MySQL Plugin, etc.). You can run any database query and schema change against the jaws db once you've connected in your GUI.
7. Run the "Table Data Import Wizard" in your Database GUI using the 'sesame_street_characters.csv' file in this directory. This .csv file contains data and the import wizard can take a .csv file and pre-populate your table with that data. We are doing this before step 8 below so that when we load up our webpage, the Sesame Street Characters Table is populated with data. (You can also run sql ```INSERT INTO``` queries if you dont want to use .csv).
8. Run ```heroku open```
9. Done
