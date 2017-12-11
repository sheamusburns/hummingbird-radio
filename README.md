#Hummingbird Radio

In the robotics class I teach, our students have been building some rolling robots from scratch using Leonardo's. We needed a way to send the cars commands, so we decided to use the RFM69HCW radio chips. The boards we used are Adafruit's feather with Joy Wing, and Adafruits RFM69HCW breakout board. 

It was tough to find an example of wiring up the board using the Leonardo instead of the Uno. We had the Leonardo wired up the same as the Uno diagrams, but it the radio wouldn't initialize. I think ** this is because the SPI pins we were using on the Uno aren't the same with the Leonardo, so I switched the up those pins, and got it running. These Fritzing images show you how. 

<img width=350px src="/images/Leonardo-RFM69HCW-Breadboard.png" />
<img width=350px src="/images/Leonardo-RFM69HCW-wiring-close-up.png" />