In addition to switching the fragment that’s displayed, we need to change the title of the action bar so that it reflects which fragment is displayed. By default, we want the action bar to display the name of the app, but if the user clicks on the Pizzas option, for example, we want to change the action bar title to “Pizzas”. This will help the user know where they are in the app.

To do this, we’ll use the position of the chosen item to get the title that should be displayed from the titles array. We’ll then update the action bar title using the `ActionBar setTitle()` method. We’ll put this in a separate method as we’ll need it later on. Here’s the code:

![](.guides/img/27.png)
