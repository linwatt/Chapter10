To work out what the value of `currentPosition` should be, we’ll check what type of fragment is currently attached to the activity. As an example, if the attached fragment is an instance of `PizzaFragment`, we’ll set `currentPosition` to 1.

We’ll get a reference to the currently attached fragment by adding a `String` tag to each fragment. We’ll then use the fragment manager’s `findFragmentByTag()` method to retrieve the fragment.

You add a tag to a fragment as part of a fragment transaction. Here's the current fragment transaction we're using in our `selectItem()` method to replace the fragment that's currently displayed: 

![](.guides/img/53.png)

To add a tag to the fragment, you add an extra `String` parameter to the `replace()` method in the transaction: 

![](.guides/img/54.png)

In the above code, we’re adding a tag of `"visible_fragment"` to the `replace()` method. Every fragment that’s displayed in `MainActivity` will be tagged with this value.

Next, we’ll use the fragment manager’s `findFragmentByTag()` method to get a reference to the currently attached fragment.
