# ChatBot
The code provided is a simple chatbot that uses the OpenAI API to generate responses to user input. The code first sets up the OpenAI API by providing your API key. It then creates a list of messages, the first of which is a message that introduces the chatbot as a coding expert. The chatbot then enters a loop where it waits for user input. When the user enters input, the chatbot adds the input to the list of messages and then uses the OpenAI API to generate a response. The chatbot then adds the response to the list of messages and displays the conversation to the user. The chatbot continues to loop until the user closes the window.

Here is a breakdown of the code:

The first line imports the ttkbootstrap module, which provides a number of widgets that can be used to create a more visually appealing user interface.
The second line imports the tkinter module, which is the standard Python module for creating graphical user interfaces.
The third line imports the openai module, which provides an interface to the OpenAI API.
The fourth line sets the OpenAI API key.
The fifth line creates a list of messages. The first message in the list introduces the chatbot as a coding expert.
The sixth line creates a Window widget, which is the main window of the chatbot. The window is given the title "Tech AI" and is sized to 600x500 pixels.
The seventh line creates a label widget that displays the title of the chatbot. The label is given the font "Helvetica" and is sized to 25 pixels.
The eighth line creates a separator widget that separates the title from the rest of the chatbot.
The ninth line creates an empty list to store the chatbot's responses.
The tenth line defines a function called CustomChatGPT. This function takes a user input as its argument and generates a response using the OpenAI API. The function first adds the user input to the list of messages. It then uses the OpenAI API to generate a response. The function then adds the response to the list of messages and returns the response.
The eleventh line defines a function called responce. This function is called when the user presses the Enter key. The function first gets the user input from the prompt widget. It then deletes the user input from the widget. The function then sets the state of the prompt and prompt_enter widgets to disabled. The function then calls the CustomChatGPT function to generate a response. The function then sets the state of the frame widget to normal. The function then inserts the user input and the chatbot's response into the frame widget. The function then sets the state of the frame widget to disabled. The function then sets the state of the prompt and prompt_enter widgets to normal. The function then clears the list of responses.
The twelfth line creates a frame widget to display the chatbot's responses. The frame is packed into the main window.
The thirteenth line creates a canvas widget to display the chatbot's responses. The canvas is packed into the frame widget.
The fourteenth line creates a text widget to display the chatbot's responses. The text widget is packed into the canvas widget.
The fifteenth line creates a scrollbar widget to scroll through the chatbot's responses. The scrollbar is packed into the frame widget.
The sixteenth line configures the text widget to scroll when the scrollbar is moved.
The seventeenth line packs the frame widget into the main window.
The eighteenth line creates a frame widget to contain the user input field. The frame is packed into the main window.
The nineteenth line creates an entry widget to get the user input. The entry widget is packed into the frame widget.
The twentieth line creates a button widget to send the user input to the chatbot. The button widget is packed into the frame widget.
The twenty-first line binds the Enter key to the responce function.
The twenty-second line enters the main loop of the chatbot. The main loop waits for the user to close the window.
The twenty-third line closes the main loop of the chatbot.
