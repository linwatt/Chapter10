![](.guides/img/33.png)

Then create a new `ActionBarDrawerToggle` by calling its constructor and passing it four parameters: a `Context` (usually `this` for the current `Context`), the `DrawerLayout`, and the two String resources. You then override the `ActionBarDrawerToggle`’s `onDrawerClosed()` and `onDrawerOpened()` methods:



![](.guides/img/34.png)

Once you’ve created the `ActionBarDrawerToggle`, you set it to the `DrawerLayout` using the `DrawerLayout`’s `setDrawerListener()` method:

![](.guides/img/35.png)
