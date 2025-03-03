<h1> Ventilation Pylone Controller </h1>

<h4>THE PROBLEM:</h4>
LED screen turn on at 6:00 morning and turn off at 0:00 midnight. </br>
Outside was around +32’C and inside was around 60-70’C. </br>
When inside the pylon is too hot all LEDs decrease their brightness about 30%. </br>
Also it’s impossible to provide any kind of technical service when inside is 50’C. </br>

</br>

<p align="center">
<img src="https://github.com/user-attachments/assets/07428086-2c6f-4c68-a97b-362211ed5997" width="350">
</p>

<h4>THE SOLUTION:</h4>
Ventilating the building using two 750W bottom fans and 6 side fans to decrease inside temperature to acceptable. </br>
Temperature sensor must be mounted inside building at height approximately 6 meters.</br>

<h4>HOW DOES IT WORKS:</h4>
I've made 2 SETs of fans: SET1 and SET2:

<p align="center">
<img src="https://github.com/user-attachments/assets/be27852d-3f1b-4152-9c08-206e593e0a55" width="300">
</p>

SET1 = M1, M3, M5, M7; </br>
SET2 = M2, M4, M6, M8.</br>
</br>
So those sets could be handled according to logic algorythm. The time and temperature are the key: </br>

<p align="center">
<img src="https://github.com/user-attachments/assets/102f6b19-156a-46d6-9146-da6d2a48c8d0" width="450">
</p>

It gives us 4 Cases. </br>

[//]: # (Case 1)

<p align="center">
  <kbd>
    <img src="https://github.com/user-attachments/assets/bec3e249-8e12-4fbf-8b91-c968693d057d" width="450">
  </kbd>
</p>

[//]: # (Case 2)
<p align="center">
  <kbd>
    <img src="https://github.com/user-attachments/assets/9e4664d0-6945-4c4e-9e81-b943f0172ca1" width="450">
  </kbd>
</p>

[//]: # (Case 3)
<p align="center">
	<kbd>
    <img src="https://github.com/user-attachments/assets/916c3157-20dc-47cd-8302-92b9f7aa802b" width="450">
	</kbd>
</p>

[//]: # (Case 4)
<p align="center">
	<kbd>
		<img src="https://github.com/user-attachments/assets/d711fb9f-3727-401a-94e9-60d6c579e47a" width="450">
	</kbd>
</p>







