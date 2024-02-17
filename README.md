If you are learning how to navigate between different pages in Flutter, this repo could be helpful.

Start from the main.dart file. You will see that we've created a simple root widget and specified the home property as HomePage()

Then go to home.dart file. As you can see, we only have one ElevatedButton widget in the middle of the page. Also, there is a text says Home in the appBar.
Look at the onPressed property. It uses Navigator.push() method and routes to Settings Page.

Lastly, look at the setting.dart file. It's similar to the home page, but in here, the ElevatedButton closes the setting page and goes back to home page.
