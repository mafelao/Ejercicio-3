# Ejercicio-3
Reconstrucción ejemplo del "for" anidado que usa las lineas y los cuadrados, la idea era que los cuadrados quedaran precisamente encajados en la cuadricula de las líneas.


float leon=0;
void setup(){
  size (500,500);
  }
  
  void draw(){
    
    for (int mono=100; mono < 400; mono = mono+ 10) {
      for(int mono1=100; mono1 < 400; mono1= mono1+ 10){
        for(int porfin=100; porfin < 390; porfin= porfin+ 10){
          for(int lologre=100; lologre < 390; lologre = lologre+ 10){
      
      line(mono,0,mono,500);
      line(0,mono,500,mono);
      
      rect(porfin,lologre,10,10);
   }  
   }
     }
      }
     
    }
