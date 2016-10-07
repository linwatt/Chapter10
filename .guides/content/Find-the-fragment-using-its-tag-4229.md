To retrieve the fragment that’s currently attached to the activity, we’ll pass the tag we set as part of the fragment transaction to the `findFragmentByTag()` method:

![](.guides/img/55.png)

The `findFragmentByTag()` method starts by searching all fragments that are currently attached to the activity. If it can find no fragment with the correct tag, it then searches through all fragments on the back stack. By giving all fragments the same tag of `"visible_fragment"`, the above code will get a reference to the fragment that’s currently attached to the activity.

Here’s the full code for the `OnBackStackListener`. We’re using the `findFragmentByTag()` method to get a reference to the currently attached fragment. We’re then checking which type of fragment it’s an instance of so we can work out the value of `currentPosition`:

![](.guides/img/56.png)

Let's look at the full code before we test drive the app