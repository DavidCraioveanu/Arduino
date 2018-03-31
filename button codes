 void setup() {

  Serial.begin(9600);

  pinMode(8, INPUT); 

  pinMode(9,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(11,OUTPUT); 

}



void loop() {  

  int citit; 

  int i=0;

  citit=digitalRead(8); 

   while(i<=3&&citit==0){

    citit=digitalRead(8); 

    delay(400);

    if(citit==0){

     i++; 
     delay(400);   

    }  

     Serial.println("bucla");

     Serial.println(i);

       if(i==1){

         digitalWrite(9,1);

     //    delay(100);

       //  digitalWrite(8,0);

     //    delay(100);

         Serial.println("1");

       }else if(i==2){

         digitalWrite(10,1);

         delay(100);

       digitalWrite(9,0);

      //   delay(50);

         Serial.println("2");

       }else if(i==3){

         digitalWrite(11,1);

        delay(100);
 
        digitalWrite(10,0);

     //   delay(300);

         Serial.println("3");         
           
       }  

      citit=0; 

   }

  Serial.println(citit); 
   digitalWrite(11,0);

  Serial.println("sfarsit");

   delay(400);  

 }
