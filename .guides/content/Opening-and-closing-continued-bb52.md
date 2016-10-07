Next, you need to get the `ActionBarDrawerToggle` to handle being clicked. To do this, you call its `onOptionsItemSelected()` method from within the activity’s `onOptionsItemSelected()` method like this:

![](.guides/img/43.png)

The code 
```
drawerToggle.onOptionsItemSelected(item)
```
returns `true` if the `ActionBarDrawerToggle` has handled being clicked. If it returns `false`, this means that another action item in the action bar has been clicked, and the rest of the code in the activity’s `onOptionsItemSelected()` method will run.
