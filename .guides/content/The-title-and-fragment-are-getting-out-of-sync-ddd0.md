When we click on one of the options in the navigation drawer, the title in the action bar reflects the fragment that’s displayed. As an example, if you click on the Pizzas option, the action bar title gets set to “Pizzas”:


![](.guides/img/49.png)

If you click on the Back button, the title isn’t updated to reflect the fragment that’s displayed. As an example, suppose you click on the Stores option, followed by the Pizzas option. A list of pizzas is displayed and the title reflects this. If you then click on the Back button, `StoresFragment` is displayed but the title is “Pizzas”:

![](.guides/img/59.png)

If you rotate the device, the title reverts to “Bits and Pizzas” irrespective of what fragment is displayed:

![](.guides/img/50.png)

Let’s fix these problems, starting with keeping the action bar title in sync when the device is rotated.
