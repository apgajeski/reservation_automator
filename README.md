# reservation_automator

Usage Instructions
1. Copy your script 
2. Set top level variables
  i. Day Selection
     a. desiredDay = set this to the day of the month you are looking to reserve. it must be in the current month.
  ii. mountains = this is a list of the numerical value of the mountains you would be willing to ski/ride on that day. there is a mapping of mountain names to         numbers in script
  iii. people = this is the list of passholders on your account you are looking to get reservations for on the given day. enter their full names.
3. Navigate to the epic pass reservation site (you must be logged into your account)
4. Open up the web console. I recommend Safari, it worked more seamlessly than Chrome. You will need to select 'Show developer menu bar' in preferences (in Advanced). Once the preferene is updated, right click on the screen and select 'Inspect Element'.  
5. Copy and paste the script with your set variables into the web console (can paste it next to the '>' at the bottome of the console). Hit 'enter'
6. type start() into the console and hit enter.
