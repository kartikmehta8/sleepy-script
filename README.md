## Inspiration - Why did I created this script?
Due to COVID-19, most of our day-to-day tasks are conducted online. Online working culture has impacted academics and children's lives, both positively and negatively. They are facing medical problems like headaches and weak eyesight problems. As responsible parents, it is necessary to keep track of control of their children's screen time. To refresh their senses, they play multimedia games or watch movies and cartoons, but it should be within a limit. To tackle this situation, we have created the **Sleepy Script** .

## What it does?
Parents/Users need to run this script for browsing the website. It provides a user to input the URL which he wants to surf. Parents set the timer and the operation `Lock, Restart, and Shutdown` they can execute. So they can restrict the screen time of their children effectively.

## How do I build it?
I have used the Python programming language to create this script. For accessibility of the browser, I have imported a selenium web driver. The time module is used for time management and setting up the alarm. To execute system commands, I have used the subprocess.

## Challenges I ran into:
The major challenge I ran into was that system commands like shutdown requires sudo permission and, initially, the script was not working. But we tackled this situation by performing research and thanks to this [Ubuntu Help page](https://askubuntu.com/questions/465109/where-should-i-put-my-script-so-that-i-can-run-it-by-a-direct-command).

## Accomplishments that I'm proud of!
The accomplishment that I am proud of is that it fulfills its motive fruitfully. Even when you are watching a movie at night, you want to set an automatic shutdown in case, you fall asleep, it can easily handle this. A multi-purpose script.

## What I learned?
- I learned how to set up a selenium web driver with a Firefox browser and its operations.
- I learned to execute system commands like shutdown and reboot using python and subprocess.
- Playing with errors and selenium get requests.

## What's next for Sleepy Script - Parental Control & Timer?
The next step for the Sleep Script is to enhance its capabilities by controlling the browser with CLI and more system commands that we can run.
