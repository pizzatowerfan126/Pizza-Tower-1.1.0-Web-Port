# Pizza Tower 1.1.0 Web Port

A Port of Pizza Tower 1.1.0 (The Noise Update) to the Web Browser

http://pt-emscriptenport.x10.mx/runner.html

Unfornately there are many bugs that can severely impact the game such as
- No sound
- Game Frame being heavily misplaced (Somewhat Fixable through ingame settings)
- Crash as Knight Peppino when slamming into a wall
- And many more I did not encounter during my time play testing (which only went up to Level 3)

Although saves do work correctly
- Note that you should immediately toggle Fullscreen while in-game, as it resolves the Game Frame issue, and it improves performace on extremely low-powered hardware
such as school chromebooks (for some reason)
- Also, the game lags alot when spawning particle effects and/or when blocks change (Walkable Cheese blocks) / are destroyed on low-end hardware

## Also fixes are not going to happen by me if at all
  
  Why? Because I'm bad at coding, and I'm not sure if this will get any attention

## No files will be listed here, instead being downloadable by a Google Drive Link
### https://drive.google.com/file/d/1Fwb4DBS9ZqnVfmSa4cKKoqZM3Cymn_gX/view?usp=sharing

- Which will include a decompiled Pizza Tower for anyone that wants to improve this shit
- Note that I used GX.GAMES and VM options to compile it, and to obtain the compiled files from GameMaker Studio for free, just go to C:/Users/(your username)/AppData/Local/GameMakerStudio2-LTS/GMS2TEMP while locally running the game
- In which you will find a folder called PizzaTower_GMS_(some numbers)_VM after you compiled the project

The said files will NOT run locally as file:// will just result in CORS errors and will not allow runner.html (the main file that runs Pizza Tower) to read the game files

The only way for them to work is if you have a web server running this, or a local server using something like python
- Which you can do by entering the directory containing runner.html and other files and typing the command python3 -m http.server in the linux terminal or py -m http.server for windows powershell given you installed python
- At which point you can enter http://localhost:8000/runner.html to play the game locally

~~I won't be hosting these files as I don't have access to a server nor will I use my own computers as a server~~

(Update: I managed to host it for free using x10hosting's free plan using a minimalized version of the compiled files which is about 280MB from the normal version which is about 680MB)

## Thanks to
- loypoll for the full decompilation of the recent Pizza Tower Update
- krzys_ and UnderminersTeam for the UnderTaleMod and the ability to decompile GameMakerStudio2 games like Undertale and Pizza Tower
- And of course Tour de Pizza for the base game

## To certain users
This project was primarily made to play Pizza Tower on locked-down school chromebooks for lazy ass students. Please do not use this project to avoid paying for the PC version of the game. By doing this you not only harming the creator of Pizza Tower, but also harming your experience with this amazing game with a version filled with bugs, crashes, and lost functionality
