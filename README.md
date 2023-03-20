# currenttime
fentch the current time 
This code block defines the _MyAppState class.

The _timeString variable is initialized as an empty string. It will hold the formatted time string that will be displayed on the screen.

The initState() method is called when the widget is first created. It calls updateTime() once to initialize the time string.

The updateTime() method gets the current time using DateTime.now() and formats it as a string using the DateFormat class from the intl package. It sets the _timeString variable using the setState() method, which updates the app's state and triggers a rebuild of the widget. Finally, it sets up a timer to call updateTime() every second using the Timer.periodic() method.

The build() method returns a MaterialApp widget that defines the app's title and home screen. The home screen is a Scaffold widget that contains a Container widget with a background gradient and a Center widget with a Text widget that displays the _timeString variable. The text style is defined with a black color, a font size of 50, and a bold font weight.

The end result is a clock that updates every second and displays the time in a large font with a changing background gradient.





