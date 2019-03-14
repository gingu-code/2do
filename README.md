# 2do

Because a proper todo list should have a completed list as well, an easier interface for moving things around, and the ability to put something _back_ on your list. Our previous [list][bucket-list-repo] [challenges][multicalc-repo] had none of those things and were terrible. Let's make things less terrible!

#### What Does Our App Do?

We'll be working with a todo list _and_ a completed todos list. They'll be able to enter a **1-based** index (that is, the counting starts with 1, not 0) and remove that todo, or move it to the completed list, or move it back to the todo list. We'll also be able to clear either list. Two lists! What a time to be alive.

#### General Guidelines and Hints

* This is very similar in its setup to our last two projects, so that familiarity should help!
* You'll be adding the selectors again, but you do NOT have to touch the html management functions. Those selectors are all there for you.
* Speaking of the html management functions, you'll see that we got rid of the need for you to fill in the query selectors there this time around.
* Another big change to the html management functions is a more clear API. You should _not_ use the functions that start  with an underscore. That is a typical way to mark a function as "private", meaning it's for our use, not yours. Your entry points are `resetInputs`, `updateTodosOl`, and `updateCompletedOl`. _We_ use `\_clearOl` within those functions, but you know not to use it yourself because of the underscore.
* What's an API, you might ask? It's like a user interface for other coders. We give you some code you can use, and try to make it clear how you can use it. By outlining which functions you should use, we're giving you some documentation of how to use our code. (Of course, ACTUAL documentation would be ideal for a real API.)

#### Stretch Goals
* We reserve the right to add some, but for now, if you finish this project early this weekend, do some codewars problems!

[bucket-list-repo]: (https://github.com/abbreviatedman/bucket-list)
[multicalc-repo]: (https://github.com/abbreviatedman/multicalc)