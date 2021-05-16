# Understand Tasks and Back Stack

## Tasks: 
- It is a collection of metadata and information around a stack of activities.
- The activities are arranged in a stack—the back stack)—in the order in which each activity is opened. 
-  "last in, first out" stack

### Example:
- facebook app might have one activity to show a list of new posts. When the user selects another user profile, a new activity opens to view that profile.
- This new activity is added to the back stack. If the user presses the Back button, that new activity is finished and popped off the stack.

### Back Stack:
![](https://miro.medium.com/max/291/1*zItbFvFydIR63z_37ya1Iw.pnghttps://www.baeldung.com/wp-content/uploads/2017/09/New.png)

- startActivity():pushing a new activity onto your task causing stop or pause the previous activity if exists.
- finish():it pops the stack,removing activity from the back stack and moving to the previous stak.

## Managing Tasks:
* It uses for:
-  begin a new task when it is started (instead of being placed within the current task).
-  start an activity, you want to bring forward an existing instance of it (instead of creating a new instance on top of the back stack)
-  you want your back stack to be cleared of all activities except for the root activity when the user leaves the task.

1.taskAffinity
2.launchMode
3.allowTaskReparenting
4.clearTaskOnLaunch
5.alwaysRetainTaskState
6.finishOnTaskLaunch
##### And the principal intent flags you can use are:
1.FLAG_ACTIVITY_NEW_TASK
2.FLAG_ACTIVITY_CLEAR_TOP
3.FLAG_ACTIVITY_SINGLE_TOP

## Save key-value data

### SharedPreferences
- It uses to save small collection of key-values.
-  It is object points to a file containing key-value pairs and provides simple methods to read and write them.

* getSharedPreferences() — Use this if you need multiple shared preference files identified by name, which you specify with the first parameter.
* getPreferences() — Use this from an Activity if you need to use only one shared preference file for the activity.


