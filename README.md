# Code Challenges

PLEASE DO NOT FORK THE REPOSITORY. WE NEED A PUBLIC REPOSITORY FOR THE REVIEW. 

## Show your work

1.  Create a Public repository ( please dont make a pull request, clone the private repository and create a new plublic one on your profile)
2.  Commit each step of your process so we can follow your thought process.

## Deliverables we expect:
* Fully complete the challenge. 
* URL where the game/app can be accessed and played/used (use any platform of your preference: heroku.com, aws.amazon.com, etc)
* Code in a public Github repo
* README file with the decisions taken and important notes

What we want to see is how well you handle yourself given the time you spend on the problem, how you think, and how you prioritize when time is sufficient to solve everything.

Please email your solution as soon as you have completed the challenge or the time is up.

# Minesweeper (Option 1)

## What to build

Develop the classic game of [Minesweeper](https://en.wikipedia.org/wiki/Minesweeper_(video_game))

The following is a list of items (prioritized from most important to least important) we wish to see:
* Design and implement  a documented RESTful API for the game (think of a mobile app for your API)
* When a cell with no adjacent mines is revealed, all adjacent squares will be revealed (and repeat)
* Ability to 'flag' a cell with a question mark or red flag
* Detect when game is over
* Persistence
* Time tracking
* Ability to start a new game and preserve/resume the old ones
* Ability to select the game parameters: number of rows, columns, and mines
* Ability to support multiple users/accounts
* Unit/Coverage Testing
 
## Time Spent
We suggest not spending more than **5 days total**.  Please make commits as often as possible so we can see the time you spent and please do not make one commit.  We will evaluate the code and time spent.
 
# Event Ticket Reservation (Option 2)

## What to build

The following is a list of items (prioritized from most important to least important) we wish to see:

* Create a simple  frontend experience to reserve an event ticket (or multiple events) using a Spring Java API secure (user needs to register/login to access the application)  [You can choose your framework]
* Each event should include the expected temperature for the event day if possible returned from the backend using an external API and should be updated every 10 minutes
* All members that reserve a ticket should be tracked in the system with the amount they are spending
* An event can belong to a single provider, and has capacity limit
* User or Admin should be able to login, reserve a ticket for several events and receive an order message via screen while all information should be traceable in the database layer
* User or Admin should be able to login, cancel reservation of one or several events and receive an confirmation message via screen.
* Administrator should be able to review all the event tickets reserved fitered by provider and date rage with the corresponding costs and totals. Also it will include a CSV file download button
* Unit/Coverage Testing

## Time Spent
We suggest not spending more than **3 days total**.  Please make commits as often as possible so we can see the time you spent and please do not make one commit.  We will evaluate the code and time spent.
 

