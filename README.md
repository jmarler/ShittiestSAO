# ShittiestSAO
A 3-D printable SAO that has a single blinking light and uses no PCB. 

Collect all of the parts in the kit, or create your own kit:

## Parts
![Parts Kit](partskit.jpeg)
* 1x Blinking LED
* 1x 2x3 pin 2.54mm headers (You can also use 2x 1x3 headers)
  * The middle pin must be removed
* 1x SAO printed part
* 1x Sticker for the front
  * Create your own sticker, or if you got a kit, use the sticker in the kit
* Non-conductive epoxy
  * Tested using Plastic Bonder 50139 from JB Weld
  * JB Weld is conductive and will not work for this project
* Soldering iron with a fine tip & leaded solder
* Needle nose pliers
* Something to mount the SAO on during assembly
  * A working badge with an SAO header
  * A male SAO header on a breadboard
  * A SAO testing device
* A multi-meter to test and troubleshoot

## Assemble the SAO

### Step 1

Insert the LED into the front of the SAO with the anode (long leg) on the left. The polarity is very important here. If you get this step wrong, the SAO will not work. 

![Step 1](step1a.jpeg)
![Step 1](step1b.jpeg)

### Step 2

Bend the legs of the LED over. The shorter leg should fold all the way down.

![Step 2](step2.jpeg)

### Step 3

Trim the longer leg so that it protrudes into the open box space by about 2mm. See picture. Leave it longer and trim it back until you are comfortable with the length. This will be more clear in step 6 when you solder the pins.

![Step 3](step3.jpeg)

### Step 4

Use the pliers to put a slight bend in the end of the shorter leg. See picture. 

![Step 4](step4.jpeg)

### Step 5

Insert the headers into the badge until only the short end of the pins is visible.

![Step 5](step5.jpeg)

### Step 6

Mount the SAO onto the pin headers. The tolerances are very tight, so you will need to press hard. When the pins are flush with the front of the face of the SAO, they are inserted correctly.

Note: Soldering will be easier if what is now the shortest pin sits to the left of the top left pin of the headers, and the now longer pin sits to the right. See picture.

![Step 6a](step6a.jpeg)
![Step 6b](step6b.jpeg)

### Step 7

Solder each pin of the LED to the closest of the left side pins of the headers. See picture. This connects 3v to the LED directly based on the SAO 1.69bis standard. 

Note: If the bent leg of the LED doesn't quite touch the pin, use a small piece of resistor leg to hold the leg closer to the pin. Remove it afterwards. 

![Step 7a](step7a.jpeg)
![Step 7b](step7b.jpeg)

### Step 8

Using your multi-meter, test to ensure that you have not shorted any of the pins. 

### Step 9 

Turn on the badge to confirm that the light blinks. If the light is not blinking, verify that 3v is present on the two pins. The top left pin should be positive and the bottom left pin should be negative. See diagram. If you didn’t test your LED before you started, use an alternative power source and test it now. Did you get the polarity correct? 

![SAO Pinout Diagram stolen from hackaday.com](saopinout.png)

### Step 10

Mix the epoxy using the manufacturers directions. 

### Step 11

Once the epoxy is ready, fill the empty space where the header pins are connected to the pins of the LED with epoxy. Try to fill it flush with the face of the SAO. 

![Step 11](step11.jpeg)

### Step 12

Let the epoxy set enough that you can continue working. For plastibond, this is about 15 minutes.

### Step 13

Peel the backing off the sticker and mount it to the face of the SAO.

![Step 13](step13.jpeg)

### Step 14 

Assembly is complete! Leave the SAO alone to allow the epoxy to fully set, according to the manufacturers directions. Once the epoxy is fully set, you are good to go!

### Notes:
* Do not use cyanoacrylate glue. This glue is far too runny, and will pour out the bottom of the SAO and cover whatever it is plugged into.
* Use an epoxy that is thick and non-conductive. If the epoxy is thick, it will be less likely to run out of the bottom and ruin whatever you are assembling the SAO on.
* Cheap bags of LEDs often contain LEDs that don’t work. I suggest testing your LED before you get started to avoid having to take it all apart.
* You don’t need a resistor. It’s a shitty add-on … the LED may eventually die … it’s shitty …
* This is simple, but requires precision soldering. If you have a large soldering iron with a large tip, you are going to have a bad time.
* The 3-D printed part can be printed face down with no supports. Tested on a Prusa Mini and Prusa MK4 using Overture PLA.
* If you are having trouble removing the backing of the sticker, try this:
  * Place the sticker face down on the table/workbench
  * Get a piece of clear tape
  * Place the tape on the edge of the backing and the table/workbench
  * Rub your finger over the tape and try to get it stuck to the table and sticker as much as possible
  * Pull the tape off and hold the end of the tape as close to the sticker as possible
  * As you pull away from the table and reach the sticker, the backing should peel away
  * If the backing tears, use a new piece of tape, and try a different spot
  * I used this method to quickly remove the backing from about 50 stickers

### Intended Use

You forgot that the con is next week, and you promised everyone you would make an SAO. You googled and found this SAO that you can print at home and assemble with random parts you have, or can get in a day from Amazon. You're welcome!

## Sticker

To create the sticker, use a round sticker that is 40mm in diameter. I used Apple Pages to create a set of stickers for the Ham Radio Village. I've included an Apple Pages template file that prints onto a standard Fedex/UPS shipping label. I've removed the Ham Radio Village logo. Use your own. 

### Apple Pages Template File

To create your own stickers open the template in Apple Pages. Edit each one of the circles and change the fill to an "Image Fill" and select your sticker image. Or add in some text. Or do whatever you want. It's your SAO now. 

The template file is setup to print on a standard FedEx/UPS shipping label that you can get for free. You could also fill the page with stickers, or have the stickers professionally printed and cut. I cut mine out with a pair of scissors, scored the paper with a very sharp hobby knife, peeled off the paper, and stuck the sticker on the front of the SAO.

Don't forget to use a standard hole punch to put a hole in the sticker for the LED to fit through. I put the stickers on after the soldering, but if you have the skills to stick the sticker on half way  or something and poke the LED through the paper, go for it. 
