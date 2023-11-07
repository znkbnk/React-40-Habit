Step 1: Modify HabitForm.js Component

- In the HabitForm component, ensure you
have a state variable to store the selected date. 
- Next, in the handleFormSubmit function,
you'll need to update the habit object to 
include the selected date when a specific
date is chosen from the calendar. You can
do this using a conditional check.
If selectedFrequency is not "none,"
include the selected date.
- Make sure that the Calendar component in
your HabitForm component is correctly using
the selectedDate for its value and setting
the selected date using the onChange handler.

Step 2: Modify HabitList Component

- In the HabitList component, you can display
the selected date along with the habit details.
You can add a condition to check if the
selectedDate property is available in the 
habit object and display it.
