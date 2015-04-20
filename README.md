Peer Review Comment #1

In general:
I did not include FB2 app.js (main code).
I also did not include app.js FB, because it is the same code for Facebook part of the app that's in MasterView.js.
In many methods, the last property doesn't need the comma at the end. While the code ran with it, it's better not to have them. 
win1.open was added twice. One in the facebook code, one towards the end of the code. Duplication of code can sometimes cause problems.

Landing Page:
Missing a comma in blablaLabel.
The "company" image on landing page was not pushed to github. But it was also not shoing up on the landing page either.
From the code, it looks like there's buttons for navigation, however, it did not show up when the code runs. The returnButton was created, but not added on biography page. Only the button "Bio" showed up, no other labels were displayed.
After tweeking, the reason that nothing was showing up is because, all the views and labels were all the same color: black. After changing all the colors of the labels and views, all labels were visible.


Child Page (Biography):
The "return" button on biography page is too large and covering some text. Can be fixed by changing some properties in the method. 
The return button did not work. Add "scheduleWindow.close();" then it works well.

Facebook:
I could not get the facebook component to work. 
Facebook ID needs to be in ''.
After removing facebook part of code, the app ran successfully. 
module.exports = MasterView; <-- was added twice. Removed one. 




