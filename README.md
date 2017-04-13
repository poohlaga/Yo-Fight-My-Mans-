# Yo-Fight-My-Mans

This is code I used for an installation featured in [Yo, Fight My Mans](http://www.chillinisland.com/yfmm/), a collabarative exhibit between [Chillin Island](http://www.chillinisland.com/), Jacob Reinstein and [Babycastles](http://www.babycastles.com).

The installation featured two mannequins representing Dap's mother and father. Visitors approach, press a button then hear his 'parents' relay personal stories through a set of speakers mounted in the mannequins. 

![in queens](https://drive.google.com/file/d/0B042omrPdFKUVDB0TWJ2c1dibVU/view)

There are two versions of the code with different actions:
* [two buttons](https://github.com/poohlaga/Yo-Fight-My-Mans-/blob/master/2but3phrases) (one for mom, one for dad). they each say one story.
* [one button](https://github.com/poohlaga/Yo-Fight-My-Mans-/blob/master/1but6phrases_QueensMuseum), each says 3 things and they take turns and it cycles 
  * e.g.: m1, d1, m2, d2, m3, d3, m1...
  
Dap recorded audio of his parents talking and we converted it to MP3 files. I used the Arduino ["Music Maker" MP3 Shield](https://www.adafruit.com/product/1788) to store the MP3's and play the audio back on button press.

![Dap's parents](http://www.chillinisland.com/yfmm/yfmm-7.jpg)

### Some press:
* [Bedford and Bowery](http://bedfordandbowery.com/2016/02/ashok-kondabolu-of-das-racist-curates-a-show-inspired-by-things-that-make-him-go-whoa/)
* [Art News](http://www.artnews.com/2016/02/12/gentrifying-fishtanks-indian-television-and-dead-rappers-ashok-dapwell-kondabolu-presents-yo-fight-my-mans-at-babycastles/)
* [Mass Appeal](http://massappeal.com/yo-fight-my-mans-dapwell-chillen-island-baby-castles/)
* [New Yorker - event coverage](http://www.newyorker.com/goings-on-about-town/above-and-beyond/babycastles-gallery)
