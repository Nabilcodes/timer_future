![image](https://github.com/Nabilcodes/timer_future/assets/71275597/ad9eacf3-37ba-4e9b-825e-6ffae62edc67)

The text "Nabil's Computer : hey hey" was printed right before the text "Nabil's Computer : howdy!" was printed, 
even when the text's print command was placed after other text's print command. This is because the 'hey hey' text 
print command was located outside the task-spawn block, meaning the 'hey hey' text could be printed without having
to wait for the asynchronous task execution to be completed.
