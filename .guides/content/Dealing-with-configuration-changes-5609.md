As you already know, when you rotate your device, the current activity gets destroyed and re-created. This means that any user interface changes you have made are lost, including changes to the action bar title.

Just as we did in earlier chapters, we’ll use the activity’s `onSaveInstanceState()` method to save the position of the currently selected item in the navigation drawer. We can then use this in the `onCreate()` method to update the title in the action bar.

Here's the changes to our code: 

![](.guides/img/51.png)