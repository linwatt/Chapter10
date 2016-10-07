We’ll use a `ListFragment` called `PizzaFragment` to display the list of pizzas. Create a new blank fragment with a fragment name of PizzaFragment, and untick the option to create a layout. This is because list fragments don’t need a layout—they use their own.

Add a new string array resource called "pizzas" to *strings.xml* :

![](.guides/img/13.png)

Then change the code for *PizzaFragment.java* so that it’s a `ListFragment`. Its list view should be populated with the pizza names. Here’s the code:

![](.guides/img/14.png)
