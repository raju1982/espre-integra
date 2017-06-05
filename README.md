# espre-integra

https://google.github.io/android-testing-support-library/docs/espresso/basics/index.html
```
onView(withId(R.id.my_view))      // withId(R.id.my_view) is a ViewMatcher
.perform(click())               // click() is a ViewAction
.check(matches(isDisplayed())); // matches(isDisplayed()) is a ViewAssertion

ViewMatchers – A collection of objects that implement Matcher<? super View> interface. You can pass one or more of these to the onView method to locate a view within the current view hierarchy.
ViewActions – A collection of ViewActions that can be passed to the ViewInteraction.perform() method (for example, click()).
ViewAssertions – A collection of ViewAssertions that can be passed the ViewInteraction.check() method. Most of the time, you will use the matches assertion, which uses a View matcher to assert the state of the currently selected view.
```
  
