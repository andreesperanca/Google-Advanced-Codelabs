# Google-Advanced-Codelabs

## Lesson 1: Using Android Notifications
- [x] Use the NotificationManager class to create, send, update, and cancel a notification using. 
- [x] Use a NotificationChannel object with the createNotificationChannel method to set a channel for the notification.
- [x] Use addAction() to add quick actions to a notification
- [x] Use setShowBadge() to enable or disable badges.
- [x] Style your notifications using styles which extends from Notification.Style
- [x] Set the importance level with NotificationChannel.setImportance()


## Lesson 2: Creating Custom Views
- [x] To create a custom view that inherits the look and behavior of a View subclass such as EditText, add a new class that extends that subclass, and make adjustments by overriding some of the subclass's methods.
- [x] To create a custom view of any size and shape, add a new class that extends View.
- [x] Override View methods such as onDraw() to define the view's shape and basic appearance.
- [x] Use invalidate() to force a draw or redraw of the view.
- [x] To optimize performance, allocate variables and assign any required values for drawing and painting before using them in onDraw(), such as in the initialization of member variables.
- [x] Override performClick() rather than OnClickListener() to the custom view to provide the view's interactive behavior. This enables your or other Android developers that may use your custom view class to use onClickListener() to provide further behavior.
- [x] Add the custom view to an XML layout file with attributes to define its appearance, as you would with other UI elements.
- [x] Create the attrs.xml file in the values folder to define custom attributes. You can then use the custom attributes for the custom view in the XML layout file.

## Lesson 3: Animations
- [x] What properties are and how to animate them.
- [x] How to use ObjectAnimator to animate UI elements.
- [x] How to configure ObjectAnimator for different UI animation situations.
- [x] How to use AnimatorSet to create a more complex animation of several parts.
- [x] How to use AnimatorListeners to set up the initial and final state of objects that are being animated (such as removing views after fading them out).

## Lesson 4: Testing code
- [x] How to run tests from Android Studio.
- [x] The difference between local (test) and instrumentation tests (androidTest).
- [x] How to write local unit tests using JUnit and Hamcrest.
- [x] Setting up ViewModel tests with the AndroidX Test Library.
- [x] Writing Assertions for LiveData.

## Lesson 5 - Advanced Testing Code

- [x] How to test coroutines, including view model scoped coroutines.
- [x] How to test simple error edge cases.
- [x] How to test Room.
- [x] How to test data binding with Espresso.
- [x] How to write end-to-end tests.
- [x] How to test global app navigation
- [x] A review of testing coroutines from previous lessons, including covering the usage of runBlocking versus runBlockingTest.
- [x] How to test coroutines that use viewModelScope by using TestCoroutineDispatcher
- [x] TestCoroutineDispatcher's ability to pauseDispatcher and resumeDispatcher to control coroutine execution
- [x] Testing error handling by updating a fake
- [x] Testing your data layer, including your DAO and local data source
- [x] Using IdlingResource (and the CountingIldingResource subclass) to write end to end tests that both include long running code and work with the data binding library.
- [x] Testing global app navigation in an end to end test.



