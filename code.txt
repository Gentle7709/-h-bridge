int ena = 11 ;
int enb = 12 ;

int a1 = 3 ;
int a2 = 5 ; 
int b3 = 6 ; 
int b4 = 9 ; 

void setup() {
  // put your setup code here, to run once:
pinMode(a1 , OUTPUT) ;
pinMode(a2 , OUTPUT) ;
pinMode(b3 , OUTPUT) ;
pinMode(b4 , OUTPUT) ;
}

void loop() {
analogWrite(ena , 500 ) ;
analogWrite(enb , 500 ) ;
digitalWrite(a1 , HIGH); 
digitalWrite(a2 , LOW); 

digitalWrite(b3 , HIGH); 
digitalWrite(b4 , LOW); 
delay(2000) ; 

analogWrite(ena , 500 ) ;
analogWrite(enb , 500 ) ;
digitalWrite(a1 , LOW); 
digitalWrite(a2 , HIGH); 

digitalWrite(b3 , LOW); 
digitalWrite(b4 , HIGH); 
delay(2000) ;



 
/*
digitalWrite(a1 , HIGH); 
digitalWrite(a2 , LOW); 
digitalWrite(b3 , LOW); 
digitalWrite(b4 , HIGH); 
delay(2000) ; 

digitalWrite(a1 , HIGH); 
digitalWrite(a2 , LOW); 
digitalWrite(b3 , LOW); 
digitalWrite(b4 , HIGH); 
delay(2000) ; 

digitalWrite(a1 , LOW); 
digitalWrite(a2 , HIGH); 
digitalWrite(b3 , HIGH); 
digitalWrite(b4 , LOW); 
delay(2000) ; 

digitalWrite(a1 , LOW); 
digitalWrite(a2 , LOW); 
digitalWrite(b3 , LOW); 
digitalWrite(b4 , LOW); 
delay(2000) ; 
*/

}