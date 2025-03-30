# Android курс. Activity
### Группа 1371
### Студентка: Писарева Ирина

#### Lifecycle Method Logging: 
Each lifecycle method was logged to confirm the order of execution.
#### Screen Rotation: 
After enabling screen rotation, the activity was recreated, and the lifecycle methods were called again.
#### Minimizing the App: 
When minimized, the appropriate lifecycle methods were triggered, confirming the expected behavior.
#### Calling `finish()`:
The call to `finish()` in `onCreate()` immediately terminated the activity, which was logged.
