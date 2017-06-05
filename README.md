# espre-integra

https://google.github.io/android-testing-support-library/docs/espresso/basics/index.html

onView(withId(R.id.my_view))      // withId(R.id.my_view) is a ViewMatcher
  .perform(click())               // click() is a ViewAction
  .check(matches(isDisplayed())); // matches(isDisplayed()) is a ViewAssertion
  
  
  
