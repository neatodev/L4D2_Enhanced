[STEP 1]

1) Subscribe to this collection in the Steam Workshop:
	https://steamcommunity.com/sharedfiles/filedetails/?id=2718335624
	
2) Drag the 'left4dead2' folder in 'Step 1' into the main Left 4 Dead 2 install folder. If prompted, overwrite existing files.

3) Add the following line to the launch arguments for L4D2 (In Steam, right-click the game -> Properties -> Launch options)
	-console -heapsize 2096999 -novid -noforcemaccel -insecure +mat_motion_blur_percent_of_screen_max 0

4) Launch the game, let all of the add-ons load. Once the icon next to the 'Add-ons' text disappears everything has loaded.

5) Change the shader setting (Video -> Advanced -> Shader Detail) to 'Low/Medium/High' and save, then set it to 'Very High' and save again.

6) Close the game.


[STEP 2]

1) Drag the 'left4dead2' folder in 'Step 2' into the main Left 4 Dead 2 install folder. If prompted, overwrite existing files.

2) Start the game and let all of the add-ons load again.

3) Close the game.


[STEP 3]

1) (NVIDIA ONLY) Download NVIDIA Profile Inspector
	https://github.com/Orbmu2k/nvidiaProfileInspector/releases
	
2) (NVIDIA ONLY) Open NVIDIA Profile Inspector and import 'Left 4 Dead 2.nip' and then save.

3) Open the 'Step 3' folder, navigate into the folder that fits your screen resolution and drag 'left4dead2' into the main Left 4 Dead 2 install folder. If prompted, overwrite existing files.


IMPORTANT:
The game reporting add-on conflicts is normal. This is expected behavior. Everything works fine together.

Notes:
After completing all steps, your addonlist.txt and video.txt will be read-only. The former ensures that a certain add-on load order is preserved,
while the latter makes sure you are locked at maximum graphical settings. Install your own add-ons at your own risk and modify the addonlist.txt to either manually
add them (preferably at the bottom, but before the last entry) or remove the read-only flag and let Steam do it automatically (this will break my custom load order and is not recommended).

by Neato
https://steamcommunity.com/id/frofoo/