
#define trigPin_1 3 
#define echoPin_1 4

#define trigPin_2 2
#define echoPin_2 5

#define trigPin_3 7
#define echoPin_3 8

void setup(){

pinMode(trigPin_1, OUTPUT); 
        pinMode(echoPin_1, INPUT);
        
        pinMode(trigPin_2, OUTPUT);
        pinMode(echoPin_2, INPUT);    
        
        pinMode(trigPin_3, OUTPUT);
        pinMode(echoPin_3, INPUT);
}

void loop(){

 long duration_1, duration_2, duration_3, right, left, front; 
          
     digitalWrite(trigPin_1, LOW);  
     delayMicroseconds(2);              
     digitalWrite(trigPin_1, HIGH); 
     delayMicroseconds(5);              
     digitalWrite(trigPin_1, LOW);  
     duration_1 = pulseIn(echoPin_1, HIGH); 
     front = duration_1/29/2;
        
         digitalWrite(trigPin_2, LOW);
     delayMicroseconds(2);
     digitalWrite(trigPin_2, HIGH);
     delayMicroseconds(5);
     digitalWrite(trigPin_2, LOW); 
     duration_2 = pulseIn(echoPin_2, HIGH);
     left = duration_2/29/2;
         
         digitalWrite(trigPin_3, LOW);
     delayMicroseconds(2);
     digitalWrite(trigPin_3, HIGH);
     delayMicroseconds(5);
     digitalWrite(trigPin_3, LOW); 
     duration_3 = pulseIn(echoPin_3, HIGH);
     right = duration_3/29/2;
   Serial.println(right);
                                        }
