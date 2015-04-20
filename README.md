# ProgrammingAssignment4
FBapp

Reviewer 1:
When first running your code, I only saw one error in your blablaLabel where you forgot a comma at the end of your 'text' line. Besides that, your code didn’t have any other grammatical error. When launching the app, I was not able to open it. An error came up saying, " Couldn't find module: ui/handheld/ios/ApplicationWindow for architecture: x86_64. I am not familiar with that particular module, however, most times if the app says it cant find a certain module, that means it is not in the tiapp.xml code. So try adding it there. In order to run the app, I added in a // to the (main) code to take the error out and be able to run the app.

Your application has two windows with various information on each. Using a percentage base for formatting your labels, windows, and views is what allows you to retain the same formatting on various devices (I tried a iPhone 4 and iPhone 6). The info looks good, but the one area of concern is the text size. Choosing a pixel size for your text causes it to remain the same size across all devices. When using a larger device, like an iPad, the text will come across a lot smaller than when using the app on a phone. I made the same mistake. In chapter 8, there is a way around the problem using a different type of sizing, try that. 


Overall, you met the requirements for the app (minus the FB part, I couldn’t get that to work) and I was able to run the app on various devices. Good work.

