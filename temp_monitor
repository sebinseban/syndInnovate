#include <dht.h>


#define dht_apin A0 // defining anolog pin sensor
 
dht DHT;
 
void setup(){
 
  Serial.begin(9600);
  delay(500);//system boot delay time
  Serial.println("DHT11 Humidity & temperature Sensor\n\n");
  delay(1000);// delay before accessing sensor
 
}//end "setup()"
 
void loop(){
  //Start of Program 
 
    DHT.read11(dht_apin);
    
    Serial.print("Current humidity = ");
    Serial.print(DHT.humidity);
    Serial.print("%  ");
    Serial.print("temperature = ");
    Serial.print(DHT.temperature); 
    Serial.println("C  ");
    
    delay(5000);//wait for 5 seconds before accessing again
 
  //Fastest should be once every two seconds.
 
}// end loop(
