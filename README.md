# Unity-Galaxy
The start of a galaxy simulation based in Unity.

# Setup
It's quite simple to install this. All you need to do is download the scripts and import them into your Unity project. After it's compiled,
make sure you create three individual particle systems (effets -> particle system), one for the stars, one for the dust, and another for the HII
regions. Then create an empty game object and attach the "GalaxyInit" script AND the "Galaxy" script TO THE SAME OBJECT. After that, put the cooresponding 
particle system into each slot in the "Galaxy" script.

Change some settings on the "GalaxyInit" script and enjoy!

I'll see about adding new features, but this math is fairly complicated for me and I don't know what I could do. I'm open to suggestions
