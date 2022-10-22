Here it is provided the code of each console. Just copy it to each Raspberry Pico.

The pins used in the blue console are:

bt_select = 7

bt_erase = 6

bt_right = 27

bt_left = 26

The pins used in the red console are:

bt_select = 7

bt_erase = 6

bt_up = 27

bt_down = 26


Finally, once the code is in each console, follow:

1. Connect the blue console to the computer.
2. Search for the port where it is connected.
3. Change permissions on the serial port:

sudo chmod 666 <port>

4. Run the read_console.py:

python read_console.py

5. Indicate the port where the console is connected.
6. Indicate IP and port of the Game.

Repeat these steps with the red console if playing two humans. If the robot plays, you do not need to add the red console.
