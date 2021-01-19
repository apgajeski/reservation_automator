# reservation_automator

Usage Instructions
Copy your script of choice into a local text editor
Set top level variables
Day Selection
desiredDay (timeout script only) = set this to the day of the month you are looking to reserve. it must be in the current month.
desiredDays (async script only) = a list of month/day for the days youd like to reserve
mountains = this is a list of the numerical value of the mountains you would be willing to ski/ride on that day. there is a mapping of mountain names to numbers in each script
people = this is the list of passholders on your account you are looking to get reservations for on the given day. enter their full names.
delay (timeout based script only) = this is the number of milliseconds between actions in the script. too low and the webpage wont load fast enough and the script will break, too high and the script may not be fast enough to reserve days for you.
Navigate to the epic pass reservation site
Open up the web console. I do this by right clicking and selecting inspect element but its different by browser. You're smart, google it
Copy and paste the script with your set variables into the web console. make sure to get the whole thing (cmd+a). (when its pasted make sure to hit enter)
type start() into the console and hit enter.
