Now that we’ve added a drawer layout to *activity_main.xml*, we need to specify its behavior in *MainActivity.java*. The first thing we’ll do is populate the list view. To do this, we’ll add an array of options to *strings.xml*. We’ll then use an array adapter to populate the list.

Here’s the array of strings you need to add to *strings.xml* (each item in the array refers to which fragment you want to display when it’s clicked):

![](.guides/img/22.png)

We’ll populate the list view in *MainActivity.java*’s `onCreate()` method. We’ll use private variables for the array and list view as we’ll need these later on. Here’s the code:

![](.guides/img/23.png)

Now that we’ve populated the list view with a list of options, we’ll get the list to respond to item clicks.
