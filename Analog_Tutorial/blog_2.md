# Part 2: Create a Comparator/Operational Amplifier
For the first design, we are going to create a 5-transistor operational amplifier. This amplifier will be at the heart of our first analog neuron in part 3. I will also make a part 3.5, for those who want to fo more thoroughly through the equations to design this subsystem. 

This design will be based on the one done by Steffan Schnippers (The creator of xschem for this YouTube video). In an attempt to improve the overall learning process, I will be more thorough than the video. It will hopefully be more thorough for the beginners and also be a faster alternative to a video for those who just want a quick introduction to the xschem-skywater process. 

## Essential Xshcem Shortcuts

1. add new components: **cltr+i**
2. move objects: **left click,m,move_coursor",left click**
3. horizontally mirror objects:**shift+f**
4. 


## Set up the ports
We are going to be creating a comparator op-amp block and a symbol corresponding to it. Meaning that after designing ths op amp we will be able to replicate it infinitely as any other component in out library (like a resistor or a capacitor). To do this we also need to define the input, output, power and bias ports (if we grabbed a premade op-amp it would already have those).

press ctrl+i to insert a new component. 

![Uploading image.png…]()








