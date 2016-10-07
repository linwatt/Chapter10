We’ll use a `ListFragment` called `PastaFragment` to display the list of pasta. Create a new blank fragment with a fragment name of PastaFragment. You can untick the option to create a layout as list fragments use their own layouts.

Next, add a new string array resource called “pasta” to *strings.xml* (this contains the names of the pasta):


![](.guides/img/15.png)

Then change the code for *PastaFragment.java* so that it’s a `ListFragment`. Its list view should be populated with the pasta names. Here’s the code:

![](.guides/img/16.png)