# Programming-Assignment-3

Reviewer 1:
First, there are several grammatical errors.
On line 65 you need to add in a ";" between the first ")" and "}"
On line 106 you need to add in a ";" between the first ")" and "}"
On lines 114 - 118 there were numerous characters that you forgot to add, with the corrections it should look like the following:

clamp = function (val) {
	if (val > 1) return  '1';
	if (val < 0) return '0';
	return 'val';
};
	
On line 126 you need a comma at the end of the line 
On line 131 you need to add a ";" at the end of the line 
On line 2 you need to capitalize the "W" in window 
On line 81 you need to spell "Label" correctly 
On line 113 you need to spell "function" correctly 

On line 90 and 91, there is no need for the layout additions since there is no other mention of layout in the code
You have also named the window for the tea selection as win1 in addtion to the slider portion of the app, win1. Go back and change the win1 to win2 for the slider portion of the app. You also need to create navigation from the tea selection portion to the slider portion. This can be done with a simple nav button like this: var NavButton1 = Ti.UI.createButton({ from here you would want to then add an event listener to make the button travel to win2 where your sliders are. 

For assignment purposes, you are trying to make the accelerometer response from chapter 7. 

Once these changes are made, I tried running the code but an error message saying win1.add(theColours); is undefined. I had a similar issue with my code and resolved it by taking out the first function in line one and moving the win.open(); to the very bottom of the code.
