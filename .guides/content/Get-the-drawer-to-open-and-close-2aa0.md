So far we’ve added a navigation drawer to `MainActivity`, populated it with a list of the major hubs in the app, and got the activity to respond when an item is clicked. The next thing we’ll look at is how to open and close the drawer, and how to respond to its state.

There are a couple of reasons why you might want to respond to the state of the navigation drawer. First, you might want to change the title of the action bar when the navigation drawer opens and closes. You might, say, want to display the app name when the drawer is open, and display the selected fragment when the drawer is closed.

Another reason relates to the action items on the action bar. When the drawer is open, you may want to hide some or all of these action items so that the user can only click on them when the drawer is closed.

Over the next few pages, we’re going to show you how to set up a `DrawerListener` so that you can listen for `DrawerLayout` events. We’ll use it to hide the share action on the action bar when the navigation drawer is open, and make it visible again when the drawer closes.

![](.guides/img/31.png)