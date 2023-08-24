# React homework template

This project was created with
[Create React App](https://github.com/facebook/create-react-app). To get
acquainted and configure additional features
[refer to documentation](https://facebook.github.io/create-react-app/docs/getting-started).

## Feedback Widget

Like most companies, Expresso Cafe collects reviews from its customers. Your
task is to create an application to collect statistics. There are only three
options for feedback: good, neutral, and bad.

### Step 1

The app should display the number of reviews collected for each category. The
app should not save review statistics between different sessions (page refresh).

### Step 2

Expand the app's functionality so that the interface displays more statistics
about the collected feedback. Add a display of the total number of collected
reviews from all categories and the percentage of positive reviews. To do this,
create helper methods countTotalFeedback() and countPositiveFeedbackPercentage()
methods that calculate these values based on state data (computable data).

### Step 3

Perform a refactoring of the application. The state of the application must
remain in the App root component.

Put the statistics display in a separate component - Statistics. <br> Put the
button box into a component FeedbackOptions.<br> Create a component Section that
renders a section with title and (children). Wrap each of the Statistics and
FeedbackOptions in the created section component.<br>

### Step 4

Extend the functionality of the application so that the statistics block is
rendered only after after at least one feedback has been collected. The message
about absence of statistics put in the component Notification.
