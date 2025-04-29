# cs2261-lab-06--mode-4-solved
**TO GET THIS SOLUTION VISIT:** [CS2261 Lab 06- Mode 4 Solved](https://www.ankitcodinghub.com/product/cs-2261-lab-06-mode-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109928&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2261 Lab 06- Mode 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Provided Files

● main.c

● myLib.c

● myLib.h

● game.c

● game.h

● text.c

● text.h

● font.c

● font.h

● alien.png

● space.png

Files to Edit/Add

● main.c

● myLib.c

● alien.c

● alien.h

● space.c

● space.h

●Your Makefile

●Your tasks.json

After you download and unzip the files, add your Makefile and your tasks.json, and then take a look at the code. What you see should look familiar. It’s a completed

Lab05! It has a few new features to highlight and test some Mode 4 functionality. If you compile and run it right now, however, it will be a blank black screen. Complete the TODOs on order, paying close attention to the instructions.

TODO 1 – setPixel4

● For us to be able to set pixels in Mode 4, we need to account for the additional cases that Mode 4 requires, so we’re making a new function.

● TODO 1.0: In myLib.c, complete the setPixel4 function.

● Compile and run. If you press START, you should be able to travel to the Game state and see that the text is drawing correctly (drawChar4 and drawString4 have already been written for you). If not, fix this before going further.

TODO 2 – fillScreen4

● We want to be able to see the rest of the states, so we need to fill the screen next.

● TODO 2.0: In myLib.c, complete the fillScreen4 function.

● TODO 2.1: At this point, if you compile and run, you won’t see anything. That’s because our goto state functions are only filling the screen once (on the hidden page), then doing nothing. To fix this, we need to flip the page with flipPage() after do our drawing and after we wait for vertical blank. In main.c, in the goToStart function, wait for vertical blank, then flip the page.

● TODO 2.2: Do the same for goToPause.

● TODO 2.3: Do the same for goToWin.

● TODO 2.4: Do the same for goToLose.

● Compile and run. You should be able to travel through all the states you just edited and see their titles printed on them (except for Start, because drawFullscreenImage is still blank). If not, fix this before going further.

TODO 3 – drawFullscreenImage4

● We want to actually be able to see the start screen. Let’s make it so we can draw fullscreen images.

● TODO 3.0: In myLib.c ,complete drawFullscreenImage4.

● TODO 3.1: This isn’t worth anything if we don’t have an image to draw. Open space.png in Usenti. No need to resize this image, as it is already 240×160 pixels (the size of the screen).

● TODO 3.2: We’re in Mode 4, so the image has to be a max of 256 colors. Usenti has a tool to do this for us. Go to Palette &gt; Requantize, type 256, and hit OK.

● TODO 3.3: Export your image (go to Image &gt; Export). You’ll save it as a GBA source file in the Lab06 folder. In the export settings, select bitmap(GBA) and “8bpp” in the export settings (8 bits per pixel means a char for each pixel, like Mode 4 wants). Also make sure that Pal (in the top right) is checked. This will include the palette in the .c file as an array of 256 shorts. ● TODO 3.4: Include space.h at the top of main.c.

● UNCOMMENT 3.0: Uncomment the call to drawFullscreenImage4 in the goToStart() function.

● TODO 3.5: We need to be able to load the image’s palette (located in space.c) in the game, so that the hardware knows what colors to use. In main.c, in the goToStart() function, write a single call to DMANow() that will copy the entire space.c into the game’s PALETTE.

● Compile and run. You should be able to see all of the states now (except for the moving elements in Game). If not, fix this before going further.

TODO 4 – drawImage4

● We want to be able to draw smaller images as well.

● TODO 4.0: In myLib.c, complete drawImage4.

● TODO 4.1: Open alien.png in Usenti. This one was drawn using a small enough palette and size, so there is no need to resize or requantize.

● TODO 4.2: Export this image the same way you did the last one, making sure that Pal is checked. In initGame(), write the same DMANow() call you wrote to load in the palette last time, this time loading in alienPal.

○ Note: This time, after we load in the palette, we also put some of our own colors in there (you can view this in game.c. It looks super complicated, and you don’t have to do it this way when you are making your games). It has already been done for you.

● TODO 4.3: Include alien.h at the top of game.c.

● UNCOMMENT 4.0: Uncomment the rest of drawBall().

● Compile and run. When you reach the Game state, you should see two pumpkins bouncing around. If not, fix this before going further.

TODO 5 – drawRect4

● For our last touch, we need to be able to draw rectangles.

● TODO 5.0: In myLib.c, complete drawRect4. This will be by far the longest function you code in this lab. You need to account for all cases where you have to set pixels in front or behind each row. You also need to make sure it still works if you draw a rectangle of a small width (1 or 2).

○ Hint: draw lots of pictures. There are four col/width cases, so make sure you identify and account for all of them.

● Compile and run. When you reach the Game state, you should be able to see all of the rectangles you are familiar with, plus some mixed into the aliens. If you shoot, the bullets are now of different widths, and they don’t fly straight up when you are moving; they lean in the direction you were moving when you shot. If any of your homeworks work like this, we will assume you copied code, and penalize heavily. These additions are to help you test drawRect. The rectangles should all be correctly sized, and they should not wiggle when they move diagonally (they should move smoothly in that direction). If this all works, submit your lab.

Submission Instructions Zip up your entire project folder, including all source files, the Makefile, and everything produced during compilation (including the .gba file). Submit this zip on Canvas. Name your submission Lab05_FirstameLastname, for example: “Lab06_MilesMorales.zip”.
