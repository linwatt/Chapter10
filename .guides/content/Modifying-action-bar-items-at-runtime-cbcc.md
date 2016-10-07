If you have items on your action bar that are specific to the contents of a particular fragment, you may want to hide them when the drawer is open, and display them again when the drawer is open. When you need to modify the contents of the action bar in this way, you have to do two things.

First, you need to call the activity’s `invalidateOptionsMenu()` method. This tells Android that the menu items that need to be on the action bar have changed and should be re-created.

When you call the `invalidateOptionsMenu()` method, the activity’s `onPrepareOptionsMenu()` method gets called. You can override this method to specify how the menu items need to change

We’re going to change the visibility of the share action on our action bar depending on whether the drawer is open or closed. We therefore need to call the `invalidateOptionsMenu()` method in the `onDrawerClosed()` and `onDrawerOpened()` methods of the `ActionBarDrawerToggle`:

![](.guides/img/37.png)

We then use the activity’s `onPrepareOptionsMenu()` method to set the visibility of the share action:

![](.guides/img/38.png)