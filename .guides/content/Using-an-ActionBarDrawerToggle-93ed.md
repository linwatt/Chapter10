The best way of setting up a `DrawerListener` is to use an **ActionBarDrawerToggle**. An `ActionBarDrawerToggle` is a special type of `DrawerListener` that works with an action bar. It allows you to listen for `DrawerLayout` events like a normal `DrawerListener`, and it also lets you open and close the drawer by clicking on an icon on the action bar.

You start by creating two String resources in *strings.xml* that describe the “open drawer” and “close drawer” actions. These are needed for accessibility:

![](.guides/img/32.png)
