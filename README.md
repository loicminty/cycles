# cycles
Creation of a digital music instrument based on cyclical concepts of music using plant growth algorithms.

## Concept
This digital musical instrument explores 2 main branches of design: interaction and system conception. 

## Interaction Research
In my research on interaction, I am creating a cross-modal (engaging multiple senses) interface which joins haptic, sonic and visual feedback. This is in the goal of creating an embodied approach to computer music by physically engaging the body in a more personalized and interactive way. 
In this branch I am using both Max-MSP for data processing, wekinator for mapping and Touchdesigner for visual control of an LED array.
From a teensy board connected through Ethernet I am receiving sensor data in Max-MSP which controls musical parameters and sends back haptic feedback. In touchdesigner visual feedback is mapped to an LED strip thanks to Zachary l'Heureux's ledControl patch.


## System Design
The system conception on the other hand explores the musical concepts of cyclical music through generative Max-MSP patches. These patches attempt to musically interpret the algorithmic botany research done at the University of Calgary, while also musically inspiring itself from artists such as Steve Reich and non-western musical approaches such as Gamelan and Sufi music.
Currently, this program makes use of the flucoma library and patches, and was initially built on Frederico Foderaro's mc. granulator. By using Flucoma's concatenative synthesis and Max-MSP's mc. wrapper, I can interpret a large range of information and musical possibilities. In order to make these accessible through interaction, I am also using wekinator to consolidate the extreme dimensions in latent space. 





