![image](https://github.com/Nabilcodes/timer_future/assets/71275597/ad9eacf3-37ba-4e9b-825e-6ffae62edc67)

The text "Nabil's Computer : hey hey" was printed right before the text "Nabil's Computer : howdy!" was printed, 
even when the text's print command was placed after other text's print command. This is because the 'hey hey' text 
print command was located outside the task-spawn block, meaning the 'hey hey' text could be printed without having
to wait for the asynchronous task execution to be completed.

![image](https://github.com/Nabilcodes/timer_future/assets/71275597/2853f1aa-3192-4b1f-95c6-5330b6b5046a)

When the spawner wasn't dropped, the task keep running and so the terminal doesn't directly shows prompt for
other command. The process need to be manually stopped, for example by pressing ctrl+C.

![image](https://github.com/Nabilcodes/timer_future/assets/71275597/caf3524f-9997-4f6e-b3ee-c72326580188)

when the spawner was dropped, task was completed successfully and the terminal seeks more prompt. The difference
regarding the appearance of the done! text was due to slight difference in parallel task execution speed.
