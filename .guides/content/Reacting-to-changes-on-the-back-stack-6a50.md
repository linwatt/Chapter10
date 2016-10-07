The final thing we need to address is how to make the action bar title reflect the fragment that’s displayed when the user clicks on the back button. We can do this by adding a **FragmentManager.OnBackStackChangedListener** to the activity’s fragment manager.

The `FragmentManager.OnBackStackChangedListener` interface listens for changes to the back stack. This includes when a fragment transaction is added to the back stack, and when the user clicks on the back button to navigate to a previous back stack entry.

You add an `OnBackStackChangedListener` to the activity’s fragment manager like this:

![](.guides/img/52.png)
