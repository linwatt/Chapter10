When the back stack changes, the `OnBackStackChangedListener’sonBackStackChanged()` method gets called. Any code you want to run when the user clicks on the back button should be added to this method.


When the `onBackStackChanged()` method gets called, we want to do three things:

**1)** Update the `currentPosition` variable so that it reflects the position in the list view of the currently displayed fragment.

**2)** Call the `setActionBarTitle()` method, passing it the value of `currentPosition`.

**3)** Make sure that the right option in the navigation drawer’s list view is highlighted by calling its `setItemChecked()` method.

Each of these depends on us knowing the position in the list view of the currently displayed fragments. So how do we work this out?
