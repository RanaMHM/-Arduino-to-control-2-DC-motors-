# Arduino to control 2 DC motors with H-bridge l293
✪ A training assignment in Smart Methods Company for the department of Electronics and Electrical Power Engineering.
**<div>✪ The circuit was designed using <a href=https://www.tinkercad.com/dashboard>Tinkercad website. </a> &nbsp; <img width="100" src="https://user-images.githubusercontent.com/52053143/127372588-fb30e614-62b4-4f9a-bda3-eaf2061234e0.png"> </div> <br> </div>**
 ## Circuit components:
 * Arduino Uno R3.
 * 2 DC motor.
 * 9V Battery.
 * H-bridge l293.
 * Wires

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img alt="arduino" width="90"  src="https://user-images.githubusercontent.com/52053143/128624919-36387765-59f1-42aa-8810-708922a582a6.png"> &nbsp;&nbsp;<img width="90" alt="dc" src="https://user-images.githubusercontent.com/52053143/128624921-a13e9bbc-2d92-42c4-8fb0-56409430e547.png">&nbsp;&nbsp; <img width="90" alt="battery" src="https://user-images.githubusercontent.com/52053143/128624929-686e9623-274c-4915-a45e-cf9f26a439d1.png">&nbsp;&nbsp; <img width="90" alt="h-bridge" src="https://user-images.githubusercontent.com/52053143/128624931-044f34f4-0ac4-4d6e-8f1a-71ef82cf4a68.png">
<br><br>

## Connect the components together
⋆ You must take care to connect the wires from the h-bridge l293 to the corresponding part in the other components.<br>
&nbsp;&nbsp;&nbsp;The following image shows the name of the ports on the h-bridge l293 with tables showing each port with its corresponding port in the other components.
<br><br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="500" src="https://user-images.githubusercontent.com/52053143/128626023-53d7d8d9-e364-4c17-b7c4-b842eebb2130.png">


&nbsp;&nbsp;&nbsp;<img width="360" alt="table1" src="https://user-images.githubusercontent.com/52053143/128627598-bbc9b96f-ed70-48bc-949c-b83e2e3f50ba.png"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="360" alt="table2" src="https://user-images.githubusercontent.com/52053143/128627599-f0a1421a-bee1-453b-98e2-4c5361643b39.png"> <br>
&nbsp;&nbsp;&nbsp;<img width="350" alt="table3" src="https://user-images.githubusercontent.com/52053143/128627601-93e7e294-8e55-4202-bbdc-4db46e1784c5.png">




<br> <br>


# Circuit after connection
![circut](https://user-images.githubusercontent.com/52053143/128625895-215c4d46-7342-49d6-940c-9d3005b95663.jpg)
<br>

## Programming the circuit in C++ 

```
void setup()
{
  pinMode(13, OUTPUT);
   pinMode(12, OUTPUT);
   pinMode(7, OUTPUT);
   pinMode(8, OUTPUT);
 
   
}

void loop()
{
  digitalWrite(13, HIGH);
  digitalWrite(12, LOW);
  
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
}
```
***



https://user-images.githubusercontent.com/52053143/128628039-f11bc571-4a6b-414a-bcfe-59187cc3e9d0.mp4









