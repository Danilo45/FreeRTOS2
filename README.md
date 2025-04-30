1.  TaskDeleteNotify is folder with exercise for practicing task notification and deletion:
    3 tasks that toggle 3 different LEDs of the STM32F407 DISC.
    Button task that polls for button press for every 10ms and on press sends notification to LED tasks,
    when task receives notification, it delete itself;

2. ButtonFromISR is folder with same exercise, but we are sending notifications from button's ISR.
3. PriorSwap folder: Excanging priority of task1 and task2 on button press.

