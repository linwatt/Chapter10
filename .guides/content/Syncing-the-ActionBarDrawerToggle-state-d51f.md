There are just two more things we need to do in order to get our `ActionBarDrawerToggle` working properly.

First, we need to call the `ActionBarDrawerToggle`’s `syncState()` method from within the activity’s `postCreate()` method. The `syncState()` method synchronizes the state of the drawer icon with the state of the `DrawerLayout`.

![](.guides/img/44.png)

You need to call the `syncState()` method in the activity’s `onPostCreate()` method so that the `ActionBarDrawerToggle` is in the right state after the activity is created:

![](.guides/img/45.png)

Finally, if the device configuration changes, we need to pass details of the configuration change to the `ActionBarDrawerToggle`. We do this by calling the `ActionBarDrawerToggle`’s `onConfigurationChanged()` method from within the activity’s `onConfigurationChanged()` method:

![](.guides/img/46.png)