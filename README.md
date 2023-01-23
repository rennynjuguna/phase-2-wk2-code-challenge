# Bot Battlr

## Setup

After unbundling the project:

1. Run `npm install` in your terminal.
2. Run `npm run server`. This will run your backend on port `8002`.
3. In a new terminal, run `npm start`. This will run your React app on port `8000`.

Make sure to open [http://localhost:8002/bots](http://localhost:8002/bots) in
the browser to verify that your backend is working before you proceed!

## Components

`BotPage` is the highest component below App, and serves as the main container
for all of the pieces of the page.

`BotCollection` and `YourBotArmy` are container components, which are children
of `BotPage`. `BotCollection` is where all the bots will be displayed, while
`YourBotArmy` (the green portion on the top of the screen) will only display the
bots that have been selected by the user.

`BotCard` and `BotSpecs` are presentational components that have been provided
for you that will render out information about an individual bot formatted for a
list view and for a full view, respectively. They are pre-styled, and it is your
responsibility to get the data into them.

All of the code to style the page has been written for you, meaning that you
should be adding to the code rather than editing it; however, if your finished
product has some styling issues, don't worry too much about it.


