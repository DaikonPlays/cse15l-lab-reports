I couldn't get the screenshots or update my Github for the labs because I got an error trying to pull and push my code. So, none of my changes and the file with the debugging and the failure-inducing input can be shown. I will go to office hours this week to try and resolve this issue.

 ![Image](LabError.png) 
 The bug is that the while loop is checking the test-file.md (failure-inducing input) even after the text ran out. So it will continuously check empty spaces until it returns an OutofMemory error (the symptom).

Another bug is that the file does not differentiate between a link and an image in test-file.md. Therefore, it will add the image to the array when it shoudln't include it.

Another bug is that when checking the test-file.md when there is no link, it will return an IndexOutofBoundsException (the symptom). This is because the program does not receive any elements for the array.