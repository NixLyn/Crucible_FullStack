#so i noticed the script tag existing in the html file "full_cal_0.html" and copied the lines of code in its JS file "full_cal_3.js" where the fuction "SetDynamicCalendar()" can be called

#from the main.html i added a script tag the the bottom of the file referencing the the file "full_cal_3.js" in the FullCalendarModal folder

#i replaced the example of

```
let disabledDates = ['2023-05-07', '2023-05-17', '2023-05-27',
'2023-06-22'];
```

with data from

```
<input type="hidden" id="boat_1_dates" value="{{ boat_1_dates }}">
<input type="hidden" id="full_dates" value="{{ full_dates }}">
```

in "./FullCalendarModal/test_0_0_3/full_cal_3.js" in Line 683

#i injected the modal component into the javascript file "full_cal_3.js" so it can be displayed on click of the input tag
#I commented out the jquery script with
