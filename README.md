# AutoBrightness
Fully parameterizable and battery saver formula. 
It takes into consideration your screens brightness to compensate the ambient light as perfectly as possible.  

You can set the minimum and the maximum brightness, the sensor sensitivity and the rate of the brightness change.  
To set up the flow please check and set the variable blocks in the beginning of the flow: 
  - minBrightness: the lowest brightness percentage your screen will be at (range 0.00-1.00) 
  - maxBrightness: the highest brightness percentage your screen will be at (range 0.00-1.00) 
  - screenNits: the maximum brightness in nits your screen can light up at (check the device's specification)  

At the start you will be ask about:
  - Speed: how smoothly and slowly the new brightness will be set (1 instantaneously - 10 slowly) 
  - Sensitivity: affects the amount pf the maximum needed ambient light for 100% brightness. Default 5 is balanced, 1 will get your screen bright faster and 10 will cause a way longer spectrum and so a dimmer screen.

# Dependencies
The script uses the Automate framework for Android. Details: https://llamalab.com/automate/
Download: https://play.google.com/store/apps/details?id=com.llamalab.automate&referrer=utm_source%3Dhomepage

# The flow
![Auto Screen Brightness Pro](https://user-images.githubusercontent.com/67100159/175785190-8ece4c7d-f500-42e1-a8b9-8998f6ee8038.png)
