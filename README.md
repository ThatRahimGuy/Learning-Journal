# Learning-Journal
This documents my adventure in programming

# 15/10/24
Start of the Learning Journal. 
We are on Unity version 2022.3.46f1.

# 29/10/24
Today I'm starting the prototype for Turbo, a 3D platformer where you get from point A to point B in the fastest time possible. I will start by making the third person character movement and animations that I will get from mixamo to use as a base for the prototype but I don't plan to add any enemies to the prototype as I want to focus on character movement with this prototype to get a good grasp on it unless I have extra time.
## Update One
I got stuck on making the character moving forward and backwards as I didn't know how to make a adjacent code that would do the oppoiste of the left and right movement. 
I searched up answers but nothing really helped except for a youtube tutorial by Buvesa Game Development which pushed me in the right direction by showing him replacing vector 3 right with forward.
All I had to was make a new float input and replace the normal input in the code for the forward backward movement with the new input and the vector 3 right with vector 3 forward which fixed the issue. 
Now I'm focus on making the character jump and having a camera follow the character and I think in the downtime between now and next week's lesson I will focus on the mixamo animation by doing research on how to make state machines.
## Update Two
Whilst working on the Jump function I used force to make it work and Paul suggested to change the character movement inputs from speed to force as it would be for the better. There was also an issue of the character phasing through the plane I had created and it was due to character not having a collison on it even though the plane did, so now I know to use a collider on anything that interacts with one another so they don't phase through. Another thing is that I'm currently sturggling with setting up the camera with cinemachine as it is not working due to "It's not possible to add this component to a prefab instance. Instead, you can open the Prefab in Prefab Mode or unpack the Prefab instance to remove the Prefab connection." What does this mean? No clue, but something I have to fix and research.
## Update Three
Camera issue was fixed by putting the player model under a class in the hierachy section.
# 05/11/24
Today I need to fix the cinemachine program to follow the character before moving onto character animations. Currently the camera still functions like at the start of the prototype where its stuck in place so I need to figure out how to make the camera follow the character.
## Update
Paul helped me fix the camera so that it follows the player however, it has some issues where the character & game start to shake the more I move which I believe could be due to the speed of the character messing with the camera. For now I will put this problem at a momentary pause as I focus on other things such as the character animations.
# 12/11/24
Currently working on the character animation still, making progress on it but things are moving a bit more slower than I like. I'm focus on making the prototype work first before I complete the character animation tutorial as its pointless if it doesn't work. Hopefully this will function before next week's lesson.
# 03/12/24
In the past week I've started my prototype with that decided to make the decision to remove the character animations tutorial. After trying to get it to work I decided that one, while I maybe able to do something like that in Unreal Engine I do not have the brains to pull something like that in Unity. Not to mention in would slow me down in being able to make the prototype and the tutorials. Currently I have finished the player movement script and on track to finish the first tutorial and hopefully next week I'll be able to get started on the second tutorial for the player camera.
# 10/12/2024
Today I worked on the camera control for unity and suprisingly it went well. All I did was add virtual camera, attach the capsule to it and it was working almost flawlessy beside a jitter issue which was resolve quickly(how you ask? got no clue tbh, it just randomly fixed it self but Samuel might have done something we both don't know that fixed it). So I'm gonna work on the tutorial for camera control because its pretty much straight forward to make. And I'll probably spend the rest of today working on the tutorials. 
# 17/12/2024
Today I'm going to start my third script for the prototype, the end point of the level. I feel this might be the more difficult script to complete so I wanted to get a headstart on it today. I think so far I'll have the scripts completed quickly, but the tutorials will be the more tricky part of all this.
## Update One
I've completed the first half of the end point script but to complete the rest I have to make an new level. So for the next things I need to add to the prototype is an end game screen and then a main menu to go back to. I'll most likely complete this over the winter break but I'll try to get a headstart in the last half hour I have right now.
# 07/01/2025
Today I'm working on the end point for my level and the main menu, however I'm currently struggling with finishing the end point of the level as the character keeps hitting the endpoint but it doesn't transition back to the main menu. I need to troubleshoot this issue so that I can move onto main menu so that I can have the scripts for this project finished and move onto doing the tutorials. I'm very close to having this finished and hope I'll get in done in time.
## Update One
Paul helped me fix the issue which was a player tag issue. Initially we thought it might be a collider problem but it turned out that after running a debug for it that the game was detecting the collison and after checking the tag for the player it was player and not what I wrote which was capsule. So after switching it to player, the game went to the main menu like planned. So now I'm going to move onto doing the script for the main menu. 
## Update Two
I have completed the main menu so that it when you press play it enters in the level and as soon as its finishes it circles back to the main menu. So now that I have the scripts finished I will start working on the tutorials to have them ready for the due date.
# 10/01/2025
It's the day of submission I have around two hours to do the tutorials & record the video but I believe I'll get it done in time. Overall, the experience has been great & even though my ideas for the prototype shifted such as ideas like character animation not making it into the final submission, it was nice to getting accustomed to how unity works and it will defintely help when I start to work on the game project for year 3.
## Final Update
Finished the tutorials submitting about 20 mins late but everything is finally done. Tutorials are very scuffed due to my poor time management but everything is finally done.
