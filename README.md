# Unturned Bypass Hash Verification
For some mods on the Steam Workshop, you cant equip the items, say if its a gun of some sorts. You can place it in your hands, but not visually and actually use the item itself. That's because of something I'm too lazy to research but I found a fix and stuck the fix into a small little C# Windows program that will apply the fix for you without you having to deal with every file its self! Here is a [video]( https://youtu.be/djZk74td8O8) of the issue and after its been fixed. **NOTE: This is for use with Unturned Server Organiser, without it this will NOT work**
## _IT DOESNT WORK, MY MODS UPDATED AND NOW THE PROGRAM CRASHES_
If you arent using Unturned Server Organiser, go download it from [here](https://unturned-server-organiser.com/)(I recommend it a lot its a great program for hosting Unturned Servers). If a mod updates and the program crashes when attempting to patch the files, open USO, click on the server you want to fix, click on Steam Workshop, and now USO will generate some ".usoinfo" files which the program uses to get the names of the mods you have installed. Now attempt to patch the mods again and it should work with no issues
## "Bypass Hash Verification Fix.exe has stopped responding"
Depending on how many mods you have depends on how long this will take, I am making a updated version to handle all the patching in a seperate thread to the main one you visually see so it doesnt stop responding. **Please wait for this if you have a lot of mods**
## When I restart USO, i have to apply the fix again? Why
In USO, go to USO Settings, Updates and untick "Auto-update workshop content on USO-Start". This should stop USO from forcing you to reapply the fix. 
## Latest Builds
For those lazy people who don't want to or _can't_ build the given project, [Click Here](https://github.com/Like50Wizards/UnturnedBypassHashVerification/releases/latest)
