# Scrummer

[Download Scrummer for Google Chrome](https://chrome.google.com/webstore/detail/scrummer/pmoipljemkkfadmmoenedgfepbefafnp)

I'm working with Trello. A lot. I've used the [Scrum for Trello plugin](https://github.com/Q42/TrelloScrum), but I found
it slowing down Trello when working with a lot of cards. So I wrote a new plugin
from scratch, without dependencies on external libraries to keep the footprint as
small as possible. Using native browser API's instead of jQuery makes it lightning-fast!

Big kudo's to the guys at Q42 for building Scrum for Trello. If you want more features,
use theirs. Use this plugin if you just want to keep track of storypoints and totals
for each column in your board, nothing else.

## Features

* Displays the number of points for each card in a badge
* Total points for each column
* Clickable buttons next to the title-field to quickly enter your estimate
* Ability to create a separator card that will count the points starting from the top or the previous separator card for easy planning

## Separators

Sketching out your sprints is pretty hard, just like planning in general. I found myself counting points during planning and refinement sessions to see how much work can be done in one sprint. Scrummer now has a feature to help you with this: separators.

Add a new card with the contents `#!!` anywhere in your board. It will count the points that are added to the card above it. You can add multiple separators in a single column: it will always start counting from the separator above.
