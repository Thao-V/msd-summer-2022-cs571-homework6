# CS571-Homework-06
## Updates to Meditation App
### Add Logo
Add your logo image to be displayed in the top middle section of your home screen. (Bare in mind platform compatibility)
  
### Add Inputs
Previously, we created a Meditation application that has 10 mins meditation + 2 mins of rest by default
Update your application to accept the following inputs:
* Number of minutes for meditation
* Number of minutes for rest
  
All inputs should be displayed in a single row, above your **Start Workout** button.
  
### Workouts List
Use Context to save all of the user's completed workouts in the form of:
```javascript
[ {year: '2020' , month: '04', day: '28', hour: '22', minute:'30'} ]
```
Use `FlatList` component to display all of the workouts When users click a button: **Previous Workouts** from your home screen.

Use AsyncStorage to save all meditation in the phone for next loading app

### Application Sketch
```
      <LOGO>
      00:00

Meditation   Rest
[10]         [2]

 <START> || <STOP> || <PAUSE/RESUME>
 
<Previous Mediation>
```
