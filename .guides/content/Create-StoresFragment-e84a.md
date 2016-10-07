We’ll use a `ListFragment` called `StoresFragment` to display the list of stores. Create a new blank fragment with a fragment name of “StoresFragment”. Untick the option to create a layout as list fragments define their own layouts.

Next, add a new string array resource called “stores” to *strings.xml* (this contains the names of the stores):

![](.guides/img/17.png)

Then change the code for *StoresFragment.java* so that it’s a `ListFragment`. Its list view should be populated with the store names. Here’s the code:

![](.guides/img/18.png)

