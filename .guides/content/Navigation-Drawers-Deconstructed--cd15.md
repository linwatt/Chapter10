You implement a navigation drawer using a special type of layout called a **DrawerLayout.** The `DrawerLayout` manages two views:

**1)** A view for the main content. This is usually a `FrameLayout` so that you can display and switch fragments.

**2)** A view for the navigation drawer, usually a `ListView`.


By default, the `DrawerLayout` displays the view containing the main content. It looks just like a normal activity:


![](.guides/img/6.png)

When you click on the navigation drawer icon or swipe your finger from the edge of the screen, the view for the navigation drawer slides over the main content:

![](.guides/img/7.png)

This content can then be used to navigate the app. 

So how does this affect the structure of the pizza app?