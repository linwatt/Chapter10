The final thing we’ll get the `selectItem()` code to do is close the navigation drawer. This saves the user from closing it themselves.

You close the drawer by getting a reference to the `DrawerLayout` and calling its `closeDrawer()` method. The `closeDrawer()` method takes one parameter, the `View` that you’re using for the navigation drawer. In our case, it’s the `ListView` that displays the list of options:

![](.guides/img/28.png)


Now that you've seen all the components needed for the `selectItem()` code, let's look at the full code and how it's used in `MainActivity`. 