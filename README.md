# SA_Tecnologia_4_UD10
 En la carpeta scr estan los programas necesarios para el correcto programa. 
             < ARDUINO PRO MICRO >
             
                |TX0   RAW| Batteries +
                |RX1   GND| Batteries -
                |GND   RST|
                |GND   VCC| 5V
                |2     #A3| 
      L9110 BIA |3~    #A2| 
                |4#    #A1| 
      L9110 BIB |5~    #A0| 
      L9110 AIA |6~#    15|
                |7      14| 
                |8#     16| 
      L9110 AIB |9~#  #~10| 
~ PWM
# Analog
              < ARDUINO MICRO >
               
                |MOSI  SCK|
                |SS   MISO|
                |TX0   VIN| Batteries +
                |TX1   GND| Batteries -
                |RST   RST| 
                |GND    5V| 5V
                |2        | 
                |3~       | 
                |4     #A5| 
                |5~    #A4| 
                |6~    #A3| 
                |7     #A2|
                |8     #A1| 
      L9110 BIA |9~    #A0| 
      L9110 BIB |10~  AREF| 
      L9110 AIA |11~   3V3| 
      L9110 AIB |12~   ~13| 
      
 Las señales de control de los motores deben de estar conectadas a los pines de PWM
 
