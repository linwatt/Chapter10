We’ve added a navigation drawer to `MainActivity`, populated it with a list of options, got the activity to respond when an option is clicked, and seen how to hide action items when the drawer is open. 

The final thing we’ll do is let the user open and close the drawer by clicking on an icon in the action bar.

This functionality is one of the advantages of using an `ActionBarDrawerToggle`. To switch it on, we're going to need to add some extra code. 
##
First, you enable the icon in the action bar. You do that using these two method calls in the activity’s `onCreate()` method:

![](.guides/img/41.png)

These lines of code enable the activity’s Up button. As we’re using an `ActionBarDrawerToggle`, the Up button will be used to activate the drawer instead of navigating up the app’s hierarchy.

![](.guides/img/40.png)

