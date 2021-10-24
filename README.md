```

      ______                         __                                    ________  ________   ______      
     /      \                       |  \                                  |        \|        \ /      \     
    |  $$$$$$\ __    __   _______  _| $$_     ______   ______ ____         \$$$$$$$$| $$$$$$$$|  $$$$$$\    
    | $$   \$$|  \  |  \ /       \|   $$ \   /      \ |      \    \          | $$   | $$__     \$$__| $$    
    | $$      | $$  | $$|  $$$$$$$ \$$$$$$  |  $$$$$$\| $$$$$$\$$$$\         | $$   | $$  \    /      $$    
    | $$   __ | $$  | $$ \$$    \   | $$ __ | $$  | $$| $$ | $$ | $$         | $$   | $$$$$   |  $$$$$$     
    | $$__/  \| $$__/ $$ _\$$$$$$\  | $$|  \| $$__/ $$| $$ | $$ | $$         | $$   | $$      | $$_____     
     \$$    $$ \$$    $$|       $$   \$$  $$ \$$    $$| $$ | $$ | $$         | $$   | $$      | $$     \    
      \$$$$$$   \$$$$$$  \$$$$$$$     \$$$$   \$$$$$$  \$$  \$$  \$$          \$$    \$$       \$$$$$$$$    
                                                                                                            
                                                                                                            
                                                                                                            
 _______                   ________          __   ______                   _______   __                     
|       \                 |        \        |  \ /      \                 |       \ |  \                    
| $$$$$$$\ __    __       | $$$$$$$$______  | $$|  $$$$$$\ __    __       | $$$$$$$\| $$ __    __   ______  
| $$__/ $$|  \  |  \      | $$__   /      \ | $$| $$_  \$$|  \  |  \      | $$__/ $$| $$|  \  |  \ /      \ 
| $$    $$| $$  | $$      | $$  \ |  $$$$$$\| $$| $$ \    | $$  | $$      | $$    $$| $$| $$  | $$|  $$$$$$\
| $$$$$$$\| $$  | $$      | $$$$$ | $$  | $$| $$| $$$$    | $$  | $$      | $$$$$$$\| $$| $$  | $$| $$    $$
| $$__/ $$| $$__/ $$      | $$    | $$__/ $$| $$| $$      | $$__/ $$      | $$__/ $$| $$| $$__/ $$| $$$$$$$$
| $$    $$ \$$    $$      | $$     \$$    $$| $$| $$       \$$    $$      | $$    $$| $$ \$$    $$ \$$     \
 \$$$$$$$  _\$$$$$$$       \$$      \$$$$$$  \$$ \$$       _\$$$$$$$       \$$$$$$$  \$$  \$$$$$$   \$$$$$$$
          |  \__| $$                                      |  \__| $$                                        
           \$$    $$                                       \$$    $$                                        
            \$$$$$$                                         \$$$$$$                                         
     
```

## Installation
Unzip this into your TF2's cfg folder, and add this line into your autoexec.cfg: `exec custom/main`

#### In case you don't already have an autoexec
Create a new file into your cfg folder named `autoexec` with the `cfg` extension. And paste the above line inside it.

## Features
#### Global (custom/global/main.cfg)
- `Voice toggle` *(Default bind: \*. Mutes and unmutes everyone)* Due to a bug, you may need to open your Options -> Voice at least once for it to work.
- `Anti AFK` Toggleable AntiAFK. *(Default bind: F9. At custom/global/antiafk.cfg)*
- `Adblocker` for community servers *(At custom/global/adblocker.cfg)*
- `Lag reducer` *(At custom/global/reducelag.cfg)* It may freeze your game upon launch.
- `Kill bind and Taunt kill bind` (Default PGDN and PGUP respectively)
- `Modifier` (default RCTRL, used for various toggles) 
#### Engineer (custom/engy/main.cfg)
- `Quick build in any directions` (Default bind: Arrow keys Default build: Sentry) Use the modifier key to switch to another build (Default: Dispenser)
- `Quickly teleport to spawn with the Eureka` (Default bind: HOME)
- `Quickly teleport to tele with the Eureka` (Default bind: END)
- Bonus: Press b to quickly hold a teleporter entrance, this is used in friendly servers to spam build them to give points to enemies
#### Spy (custom/spy/main.cfg)
- `Quickly disguise as another class` (Default: Modifier + 1-9) Use the modifier key to disguise as a friendly.
- `Undisguise bind` (Default: Numpad 0)

Of course, feel free to edit and customize those binds for your likings! (For this, you will need to edit the respective files! It's not very hard, I promise!)

### Editing a bind
Is a bind not to your likings? Or perhaps you want to get rid of one? No worries! It's very simple.

Navigate to the file which the bind belongs to (For this example, we will get rid of the Engineer bonus bind)

First of all, locate which folder the cfg files for that bind are located at. For Engineer, as stated above, it's `custom/engy/`

Open up the `main.cfg` file with your favorite text editor, such as `notepad` by draging the file onto it.

Find the line you are searching for, it should start like this: `bind <KEY> <command>`. In this case, it's this line: 

`bind b "build 1" // Teleporter Entrance, used to spam spawn them in friendly servers to give points`

If you want to delete the bind, simply delete the line.

If you want to change the key, simply replace `b` with another key, like `i` for example!

Save the file, and you're done!