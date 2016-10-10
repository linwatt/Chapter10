We’ll use a `ListFragment` called `PizzaFragment` to display the list of pizzas. Create a new blank fragment with a fragment name of PizzaFragment, and untick the option to create a layout. This is because list fragments don’t need a layout—they use their own.

Add a new string array resource called "pizzas" to *strings.xml* :

![](.guides/img/13.png)

### Creating files in codio
1) Navigate through the app folder in the file tree on the left until the folder called "bitsandpizzas" is visible
2) Right-click on the *bitsandpizzas* folder in the file tree on the left side of the screen. 
3) Select "New File..."
4) Enter the full title of the file name plus the extension
5) Select java as the file type, and java as the template

Then change the code for *PizzaFragment.java* so that it’s a `ListFragment`. Its list view should be populated with the pizza names. Here’s the code:

![](.guides/img/14.png)
