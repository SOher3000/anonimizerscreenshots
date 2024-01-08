Random Time Screenshot Script
Overview:

This script is designed to temporarily change the system time to a random value, execute a screenshot program (or any program of your choice), and then restore the original system time. It's particularly useful for tasks where screenshots with different system times are needed.
Requirements

    Bash
    Screenshot program (e.g., Flameshot)
    sudo privileges for changing system time

Installation:

Clone this repository to your local machine using:

bash

git clone https://github.com/SOher3000/anonimizerscreenshots/

Usage:

To run the script, use the following command:

bash anonimazer.bash
(make sure its runable)

Customizing the Screenshot Program

By default, the script uses flameshot gui for taking screenshots. If you wish to use a different program, edit the line flameshot gui in the script with your preferred command.
How It Works:

    Generate Random Time: The script generates a random time.
    Set System Time Temporarily: The system time is temporarily changed to this random time.
    Run Screenshot Program: The script then runs the screenshot program (or your specified program).
    Restore Original Time: Finally, it restores the system time to its original state.

Note:

This script requires sudo privileges as it changes the system time. Ensure that you have the necessary permissions before running it.
