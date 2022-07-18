# Experinment

<ins>Monitoring Sensors</ins>

In the next three graphs you can see an example to the values in each sensor

<img src="https://github.com/yuvalchemke/-Hydroponics---Monitoring-and-Balance-by-detection/blob/The-thingspeak-graphs/PPM%20value1705.png" width="500" height="287">
<img src="https://github.com/yuvalchemke/-Hydrophonics---Monitoring-and-Balance-by-detection/blob/The-thingspeak-graphs/pH%20value.png" width="500" height="287">
<img src="https://github.com/yuvalchemke/-Hydrophonics---Monitoring-and-Balance-by-detection/blob/The-thingspeak-graphs/Temprature%20value.png" width="500" height="287">

<ins>Monitoring pumps</ins>

The next three graphs represents the current status of every pump and you can also see if it worked recently.

The number 0 represent that the pump is not in active, and the number 1 represent that the pump is in active or worked (according to the time that you looking at).
In our case we decided that when a pump is turned on it will work for 8 seconds (you can change the time for each pump in the code according to your needs) and then turn off until the next need in balance. 

 <img src="https://github.com/yuvalchemke/-Hydrophonics---Monitoring-and-Balance-by-detection/blob/The-thingspeak-graphs/pH-%20pump.png" width="500" height="287"><img src="https://github.com/yuvalchemke/-Hydrophonics---Monitoring-and-Balance-by-detection/blob/The-thingspeak-graphs/pH%2B%20pump.png" width="500" height="287">
 <img src="https://github.com/yuvalchemke/-Hydroponics---Monitoring-and-Balance-by-detection/blob/The-thingspeak-graphs/EC%20pump1705.png" width="500" height="287">

For example you can see in the PPM value graph that represend the EC at 17:05 the measurement was 1973 PPM . and there for, you can also see on the EC pump gragh that he work in 17:05 for 8 seconds in order to balance the solutain in the water tank. You can see that the pump kept working every 10 minutes until the solutain was above our minimum value.
