Zunge Version 0.9.3
-------------------

Zunge is a low cost current sensor that utilizes an Arduino UNO and a Raspberry Pi.


SETUP/TROUBLESHOOTING ZUNGE
---------------------------
- To get started please vist http://www.scipy.org/install.html and follow the 
  intsructions

- Also install http://pyserial.sourceforge.net/

- If an error appears & the software fails to connect to the Arduino change
  '/dev/ttyACM0' in line 9 of the CURRENTSENSOR file to read '/dev/ttyACM1'

- If the current reading are off calibrate the current sensor using a     
  screwdriver

USING THE ZUNGE
----------------------------

1. Ensure all wires are properly connected & that the button is not pushed.

2. Open the terminal & cd to the directory of the Zunge file.

3. Enter 'python ./Zunge' w/out quotations.

4. When you want to review the data simply push the button.

5. All the data will be located in this folder.

CONTACT INFO
------------

If you have any question or comment please contact me at:
flrsalejandro96@gmail.com

Thank you for using the Zunge!
