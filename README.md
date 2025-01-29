# Marvel Rivals Hero API 

This is a simple API that retrieves hero information including the role (STRATEGIST, DUELIST, or VANGUARD), the avatar photo, and the hero ID.

To see all of this information, follow the steps below:

## Step 1

Download or clone the repository

Install express locally if you don't already have it by typing in:
> npm install express
into your command line.

## Step 2

Run the program by typing:
> node index.js
into your command line.

Here you should see "App listening on port 3000".

Take that port information and type into your web browser:

localhost:3000/v1/heroes

This will give you all the hero information from the marvel rivals website.

From here you will notice an 'id' associated with each hero.

To get specific information about a hero, copy the id, for example **Peni Parker's** id is '3929765b-c856-44c9-b97a-eb965f3fbdf6', and type that into the search bar as follows:

> localhost:3000/v1/heroes/3929765b-c856-44c9-b97a-eb965f3fbdf6

This will return **only** information about **Peni Parker**