Next we change the layout of *MainActivity.java* so that it uses a `DrawerLayout`. As we said earlier, this will contain a `FrameLayout` that will display fragments, and a `ListView` for the navigation drawer.

You create the `DrawerLayout` using code like this: 

![](.guides/img/19.png)

The `DrawerLayout` is the root component of the new layout. That’s because it needs to control everything that appears on the screen. The `DrawerLayout` class comes from the v4 support library, so we use its full class path of `android.support.v4.widget.DrawerLayout`.

The first element in the `DrawerLayout` is used to display the content. In our case, this is a `FrameLayout` that we’ll use to display fragments. You want this to be as large as possible, so you set its `layout_width` and `layout_height` attributes to `"match_parent"`.

The second element in the `DrawerLayout` defines the drawer itself. If you use a `ListView`, this will display a drawer that contains a list of options. You usually want this to partially fill the screen horizontally when it slides out, so you set its `layout_height` attribute to `"match_parent"` and its `layout_width` attribute to a fixed width.

![](.guides/img/20.png)