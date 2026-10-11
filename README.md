# ESP32-S3-Speaker
Project task is to build Home Assistant Media player from ESP32-S3+Amplifier and Speaker

I had the idea to automatically start my favorite radio when I enter the bathroom. The Home Assistant Voice Preview solution seemed unnecessary and expensive to me. I implemented the whole solution very cheaply.  

First trial was executed based on <https://github.com/rgnyldz/rgnlabs-mediaplayer> description with 5102 I2S DAC but his modul have only link output and it is neccessary to use Speaker with AUX input.  

Next trial was with modul MAX98357A  
### This solution Run 
<https://allegro.sk/ponuka/dac-dekoder-i2s-audio-modul-zosilnovac-max98357-17603273331>  



Source model for Speaker Laser Cut file
<https://cad.onshape.com/documents/bd921101e99388c22b57ea89/w/8affbd9cf3b59af87c41d7c9/e/1ebdb2714b9f8e9c8cca2bf6?renderMode=0&uiState=6aca5dd47bc6fb7797328f41>  
<img align="left" alt="image" width="200px" src="/Assets/Drawing 2.svg" />  


  



Nakoniec som esp32 zabudoval do starého reproduktora od domáceho kina takze som neriešil zabudovanie do krabice. každopádne som si krabicu s reproduktorom urobil z elektroinštalačnej krabice scame. otvor pre repro som vyrezal laserom Vid priložený súbor pre LaserGrbl.  
<img align="left" alt="image" width="200px" src="/Assets/Drawing 2.svg" />  
<Assets/Drawing 2.svg>  
