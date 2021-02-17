# JavaScript Drum Kit  
  
### Things that I have learned  

> Data Attributes  
Used to provide custom non-standard attributes to store information that are associated with particular elements. Data attribute names must precede with _data-_. In this project, data attributes are used to store keyboard event keycode property for the key div and also the audio div.  

> audio.currentTime
The currentTime property is set to 0 before the audio is played so that if the same keydown event is detected in succession, the audio would be played successively. This property is applicable for both audio and video elements. 

> classList
The classList property allows access of the classes of an element. In this project, it is used to add/remove a "playing" class to simulate the visual transition of the key divs.

> array.forEach()
The forEach() method calls a function for each element in an array. 