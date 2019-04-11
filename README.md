# Minecraft TNT Airship - Front-end
#### There are room for many improvements in the code, it's on my to-do list to update several things, but feel free to improve things if you are going to use it :)

# [DEMO](https://crizzly.fi/demo-airship)

## Why this is created
We created this because we had need for it during a minecraft tournament where the players was supposed to build their own fortresses and defend them against the enemy after a period of building time. The idea was that the people watching the tournament was supposed to steer a TNT airship through the air, and at random times, this airship would drop TNT to destroy the things builded underneath. In our tournament the teams were divided in two, and the people cheering on their respective team wanted to destroy for the other team, so there's the point for the steering of the airship.

### How it works
• Two axis: X and Y that are 384x384 <br>
• RIGHT, LEFT click updates the X axis with +1 respectively -1 <br>
• UP, DOWN click updates the Y axis with +1 respectively -1 <br>
• You can only click the buttons every 3 second, this to avoid overflow<br>
• airship.php calls update.php every second to update the balloon on the map in "realtime" <br>
• Map used here is generated by a website that generates an above picture of the map on a specified server. <br>

### Known bugs 
• Gives 1 error in console, nothing that really matters. <br>
• For some kind of reason the balloon can SOMETIMES overlap the borders if there are many people updating the balloon position even though this is restricted in the code. 

### Screenshot
![This is how it looks like with our map. When we used it, we only ran it on another website with an <iframe>, worked great.](https://i.gyazo.com/65b3ac12350e291ff20d364783267047.png)
