Author : Megan Kane <arjibsamlee@yahoo.com>
Date   : 2021-09-22
Purpose: Provide informtion on the Elder Scrolls games and their world, Tamriel, its location, races, and lore.

The purpose of this program is to be able to look up information about the races, locations and games that are part of the Elder Scrolls game franchise. The base functionality is present so that even those unfamiliar with the franchise can explore the details of the games and the rich history and lore accumulated since the release of the first game in 1994.

To run the program you should start with the command:

python3 tamriel.py

Doing so will welcome you to the program and provide the information on what type of items search for and will prompt you to use the optional command -r with one of the keywords to look up information.

For example you can search for 'race'. This search will provide a list of the known races from the Elder Scrolls Universe and a little bit of information about them.

Go on and give it a try!

My procedure for creating the project

Process:
    1.) Use new.py to make a new file 'tamriel.py'
    2.) Create csv with select information about the Elder Scrolls and Tamriel:
        -   locations: the planes of reality related to Tamriel, countries in Tamriel, provinces, and cities
        -   races: a file with the different races
        -   beings: other types of beings outside of the races e.g. dragons, daedra
        -   games: list of the elder scrolls games and info about them
    3.) Build the following functionality:
        -   read csv files
        -   take inputs: -r nothing entered after will provide a list of all options e.g. -r
        -   for provided request type return a list of all the information of that type.
    4.) Design test for the program create test.py
    5.) Copy code to a new repository.

To run test.py use:
    make test command


Possible next steps for program:
    -   make csv file more comprehensive
    -   allow searching for particular term by addind a second optional argument -s --search where every row in the CSV with the term in it is returned.
    -   add a -e --everything that prints the whole CSV

    Credit for content on Tamriel goes to The UESPWiki @ https://en.uesp.net/
