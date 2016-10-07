Here's the full code for *activity_main.xml*:

![](.guides/img/21.png)


Take a careful note of the settings we’re using with the `<ListView>` element, as any navigation drawer you create is likely styled in a similar way.

To set the size of the drawer, you use the `layout_width` and `layout_height` attributes. We’ve set `layout_width` to “240dp” so that the drawer is 240dp wide when it’s open.

Setting the `layout_gravity` attribute to `"start"` places the drawer on the left in languages where text runs from left to right, and places it on the right in countries where text runs from right to left.

The `divider`, `dividerHeight`, and `background` attributes are used to switch off divider lines between the options and set the background color.

Finally, setting the `choiceMode` attribute to `"singleChoice"` means only one item can be selected at a time.
