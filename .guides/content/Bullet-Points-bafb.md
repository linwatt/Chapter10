- Use a `DrawerLayout` to create an activity with a navigation drawer. Use the drawer to navigate to the major hubs of your app.

- If you’re using an action bar, use `ActionBarDrawerToggle` as a `DrawerListener`. This allows you to respond to the drawer opening and closing, and adds an icon to the action bar for opening and closing the drawer.

- To change action bar items at runtime, call `invalidateOptionsMenu()` and add the changes in the activity’s `onPrepareOptionsMenu()` method.

- React to changes on the back stack by implementing the `FragmentManager.OnBackStackChangedListener()`.

- The fragment manager’s `findFragmentByTag()` method searches for fragments with a given tag.
