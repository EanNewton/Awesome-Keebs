# Epomaker Custom Lighting Effects Guide \- a detailed Epomaker fan guide 

| Version | Author |        Date |
| ------- | :----: | ----------: |
| 2.3     | Ean Newton | 18 Nov 2021 |
| 2.2     | lofreq | 10 Jun 2021 |

*V2.2 guide by lofreq*
*updated 10 Jun 2021*

**A detailed community guide detailing how to use the Epomaker/Skyloong software to program custom lighting effects into your keyboard.** 

**The official Epomaker documentation does not do a great job of explaining what you can and cannot do with the software. This guide endeavours to explain the process in more detail for you.**

---

## <u>**TABLE OF CONTENTS:**</u>

[1 The basics of lighting effects](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.c3l9dcqwip1f)

[2 Working with existing LE profiles](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.qwbvtd9o032m)

[LE Effect compatibility](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.j49ui2fb4pc9)

[To rename an EXISTING profile](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.2hg64woculx0)

[3 Uploading an effect from the list, onto your keyboard](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.mbmpzpnzyn4f)

[4 Creating and editing your own LE profile](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.6456rm2ymeoc)

[Limitations of custom effects](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.j5ghk1e0zkq0)

[An easy way to understand how the boards handle lighting](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.mqj2l9g4mwvy)

[Creating a custom effect](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.4ynua8dka5d2)

[Working with the Frame Animation Layer panel](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.3wy94ftwnek3)

[Working with the Lighting Effects panel](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.fahhf7xgp4pw)

[Explaining the effects](https://docs.google.com/document/d/15SERWHasTL0rPvghC4Gte4jC8Xo5ccL86lMgqN3AhRo/edit#heading=h.bwm899fo0dep)

---

*DISCLAIMERS:* 

- *This guide has been designed with the Epomaker GK68 as primary reference, but should also apply for other keyboards that use the GK6X software (GK64/GK73/GK96 etc).* 
- *The Epomaker software in question can be found here:* [*https://epomaker.com/pages/software-downloads*](https://epomaker.com/pages/software-downloads)
- *This guide references the WINDOWS version of the “GK & SK Keyboard Software for Windows” - the MAC version is known to be buggy and may not reflect all the features or screenshots you see in this guide*



*** Looking for technical information on charging your keyboard, or keyboard polling performance? Check out the technical guide here:**

[**https://docs.google.com/document/d/1a7DqKquIWl0NtUhdZ7Z3LnVoRP8UD8fDVJTiriEM0FM/edit?usp=sharing**](https://docs.google.com/document/d/1a7DqKquIWl0NtUhdZ7Z3LnVoRP8UD8fDVJTiriEM0FM/edit?usp=sharing)

---

## 1 The basics of lighting effects

Lighting on your Epomaker keyboard is controlled by profiles called LE (Lighting Effects) files. 

1. The Epomaker software already comes with a list of default LE effects which you can load
2. OR you can create your own custom profile, and save it as an LE file of your own 
3. OR you can upload a custom effect from the community, onto your board

You can then choose to sync this LE profile to your keyboard (in an available lighting slot), in order to display a custom lighting preset or animation sequence

## 2 Working with existing LE profiles

Switch to the LE profile section by clicking on the second tab titled “LE Files”. This will display a column list of available LE profiles which you can scroll through:

![img](https://lh5.googleusercontent.com/ULvqrD0jzXbcyycIR0L5xoIAdTjFrSMwJjisOc1Euj9RbOFecklT7uuRsF2J68ob9aYBNYkl_udph_l5AyLK2k2DCYjNuK-9YOjV9OXCP43cOIOxEw3itVPq3-aH_F5cmxlSE35n)

Clicking on a profile in this panel will ‘simulate’ the LE effect onto the keyboard model on the screen. 

At the bottom of the panel are six buttons. These buttons allow you to 

- upload or download LE profile files to and from your computer, 
- delete a profile,
- duplicate a selected profile, 
- create a new blank profile, 
- or EDIT the selected profile, to start customising the lighting effects. 

### LE Effect compatibility

**NOT ALL EFFECTS WORK PROPERLY ON ALL EPOMAKER MODELS**

One of the many known problems with the software is that the lighting effects you see in the column list of effects don’t actually tell you which keyboard model they are for, unless its listed specifically in the filename. 

Loading an incompatible effect will sometimes result in only SOME of the keys lighting up or animating. 

There is no way to tell what model that effect was made for, unless you NAME the keyboard model name into the name of the effect (if you’re making your own). 

Usually, the first few profiles at the top of the column list, are Epomaker DEFAULTS that DO work on all keyboards. You will see the following which should work on all boards:

![img](https://lh6.googleusercontent.com/7ju2hQqmfuRpbeGrZ6C7sdIvQLOZX13nAOdAFSlRNA6uTMBCyUcpQbVzwtG4_P5zH_tS7d1ZAnJeYPbeTGPFWEyDb12Z0SDbiNYMAatMNpZA3cL03AejH-M-at9GslEqz6NlIXpH)

This list of effects at the top are usually compatible with all models. You can choose any of these safely and load them into an LE preset slot on your board. 

As you scroll past these, you will see all kinds of other LE effects, sometimes with other model names. Of course, these will be specific to other models, and wont work properly on your board if you have a different model

**Note, as of version 6.0.0.39, you are unable to RENAME an existing profile. Duplicating a profile will cause the software to auto-generate a new name for the profile and add a weird random number to the end, which you will not be able to change. You can only set a profile name within the software if you create a NEW blank profile by clicking the + button*


### To rename an EXISTING profile

1. Highlight the effect you wish to rename

2. Click the DOWNLOAD button on the column menu (bottom right)

3. Choose a location for the file on your computer

4. Once saved, click on that effect you want to rename, and DELETE it

5. 1. NOTE: if you dont delete it, and try to re-import it with the below steps, it will simply keep the existing incorrect name. So make sure you remember to delete it after its been saved to your computer

6. Now go to your save location, and RENAME the filename of the .le file to what you want it to be

7. Go back to the software, click on the UPLOAD button (bottom right again)

8. Re-upload the renamed effect. This will bring it back in, with the new name


## 3 Uploading an effect from the list, onto your keyboard

Once you have chosen an LE effect you want to upload to your board, follow these steps to get the effect onto your board.


Epomaker boards usually have 10 slots for lighting effects

- **Slots 1 to 5** are user modifiable, and once you save these effects to the board, they stay on the board (you dont need the software to persist the effect, and the effect will follow the board even if you unplug it and connect to a different computer)

- **Slots 6 to 9** are PRESET effects by Epomaker, and cannot be changed. These effects include:

- - Type-reactive effects (react to you typing by animating based on the key you pressed)
  - Sound-reactive effects (react to actual sound by using a microphone soldered to the PCB)


**NOTE: Effects you upload to slots 1-5 are available in ANY LAYER MODE on the board** 

- You can only upload five custom effects on the STANDARD layer in the software
- But those same five effect slots are also available if you switch to LAYER 1, LAYER 2 and LAYER 3

1. From the STANDARD layer screen, click on Layer 1 (or any other layer), then click back onto STANDARD layer
2. This will pop up the “layer effect” lighting effect slots showing you what is currently loaded in all five custom effects slots ![img](https://lh4.googleusercontent.com/fbly1ard9yesTNGZMD2Z-DcQSyzjeAaAltO4p07XDAqwK-4Apv642OYkp4fWst2W0ObkqZ67UbUfM3WEsTrHRnsGIMSmKVQEdGpgSJWCY39tYk858sI2qfCS5_fqRkamNIT7vmn6)
3. Click the red TRASH icon for the slot you want to replace. The name of the slot will change from whatever was there, to “No Config” 

![img](https://lh6.googleusercontent.com/tkYNO4kU8yvdBPL0vBgE-hUOWcqWRaJtGBAgHiS7KUHbY9ydt4pVUYf3pLgDMHANV-qbkrGlTqsImxzOESy0HMjiqiB1btAN6NMtWvGzf3gU3gsvRrWjCC9w1yXLTb-XobT3RBiU)

4. Now click the three yellow dots, to bring up the effects picker window. Scroll through here to pick the effect you want to load, then click “Confirm”:

![img](https://lh6.googleusercontent.com/EP6ePaAAZZUjiPoyrxq-DY2tg30TuTfjaiD4USWCJnmFS7NrFFoCQm_XBYUDnnE4NMBxxLi7PG9lQ8nEf49-mcf3jI2q-9Er0MvHAkIk1mDhjPJxCQJVDwlJaaw-dUrzxAQaC0CG)

5. Now, you will see the name of the effect loaded into that slot:

![img](https://lh4.googleusercontent.com/uOHVYhdbLSFbQkxZpCFl05MSiR4ix8YgvORxGMDO9t28FwcYaHfi5-0OSACNVt6RrIWvt-F16EGlXoioGlqutQkbJdhLWrZVCU8EPPKYzxR2cMT6Of_xN5b9dF65H_ShjcZyQNf6)

6. You can continue to do this and configure all the rest of the slots to the effects you want
7. Click on SAVE, then APPLY

![img](https://lh6.googleusercontent.com/pKQ_oeWXmMkiIcOxWChs8oh5hlXqUcsvxgeN--DenLc8VE0xiZfuKVgpkMDRX6JKBpeXDBMUhpFDYHfqi8-vvvMPxirIf1UD1OUc9vYIG5kptSUZAATe0Fcei3QNS-FQH19YETGk)

8. Once you see the “Apply Success” message, the effect has been safely loaded onto your keyboard

![img](https://lh6.googleusercontent.com/opmMyBk_p2CqvMDeT5qO3HukiRxo_P5pcsSlkg_gRAzuWwn1MSdVDXr84Wq0sGPWUdoyEfxOux54wATxi8GaehoETHiFvbcuDC14L3XFQRqFovLyXf1EvAmAGxAw6DIdkHmujECZ)

9. Now, just press your keyboard’s lighting effects shortcut, to scroll through the custom presets (EG on the GK68 this is Fn - “]”, or on the GK96 this is Fn - ”-”)
10. The keyboard should now display the new effect(s) you just loaded

**NOTE: If you left any of the slots empty (“No Config”), the keyboard will just skip that slot, and only cycle through slots that actually had something loaded**

## 4 Creating and editing your own LE profile

### Limitations of custom effects

Creating custom lighting effects are pretty limited in this software. Before you start, please note the following limitations:

1. The only kind of lighting you can have on each key are

2. 1. A static single colour (called “Monochrome”)
   2. A breathing single colour that only goes from that fixed colour, to black, and back again (called “breathing”)
   3. An RGB cycle, that can only cycle the FULL spectrum (called “RGB”)

3. Each key can only have ONE type of effect. IE a single key cannot be BOTH “breathing” and “RGB” at different times. The software will only pick the first effect, and ignore all others

4. You cannot “breathe” to a partial brightness. IE you cannot breathe BLUE from 100% brightness to 50% brightness, then back to 100%. The software will force the key to go 100% -> 0% -> 100% etc

5. You cannot “breathe” between specific colours. IE you cannot have a key go from only Pink to Blue and back to Pink again. Breathing can only go from the fixed colour, to completely OFF, then back to the fixed colour

6. You cannot RGB between certain colours. RGB will always cycle through the full colour spectrum

7. “FRAMES” turn selected key switch LEDs ON or OFF. They cannot change what that LED is preset to do

### An easy way to understand how the boards handle lighting

**Think of each key as being a light socket, which you can screw in one type of lightbulb at a time. And you only have 3 kinds of lightbulbs you can use (Monochrome, Breathing and RGB)**

In that case

- The “BULB” you screw in dictates how that key will light up
- You can only ever have one bulb per socket at a time. So you cannot layer effects on the same key
- FRAMES control the power to the socket. It will just turn the power ON or OFF. Whatever happens when the power is on depends on what “bulb” you configured

If you still want to go ahead and create a basic effect despite all this, please see the next section.

### 

### Creating a custom effect

By clicking the EDIT button (the little pencil icon) on the bottom of the right side panel of the LE Files mode, you will enable the lower lighting editing section of the screen (highlighted in GREEN in the screenshot below), which is usually disabled. In this example, we have created a new profile called “NewProfile1”, and clicked the edit button, which has enabled the edit section. 

This section is split into 3 parts:

- Frame Animation Layer panel
- Lighting Effects panel
- RGB Color Picker

![img](https://lh4.googleusercontent.com/j9xYAHBnhTJKo0Q6i_bppGLq3vRev_4E_mFDFAKZuocDqkOMRmXI3VYhOB4vvwg6e7QrTtKfFKg9i8m8HLiOg9k3_HffvX30f25RxZeqpI2DTrUEzwxszDACFHr__ZnQ1BYaM_XK)

Custom lighting effects on your Epomaker board are created by 

1. Choosing different lighting effects (Monochrome, RGB or Breathing) for specific selected keys or underglow LEDs

2. Creating a “layer”, where some (or all) keys on the keyboard OR underglow LEDs can be 

3. 1. “selected” (to display the effects chosen in 1) 
   2. or “deselected” (LEDs are turned OFF, no effect will be shown)

**By default, there will always be at least ONE default layer available for use.** 

It is important to note that even if a lighting effect is applied to ALL keys on the keyboard, the effect will only be shown on the keys or LEDs that have been SELECTED on the frame animation layer. 

- EG, if you apply an RGB effect to ALL keys, but the frame animation layer only has the top row selected - the effect will only ever appear on the top row. 
- You can see which rows are selected by clicking on the layer in the frame animation panel, and seeing which keys/LEDs turn WHITE. All keys/LEDs in WHITE will display an effect. Everything else will not show an effect

In this screenshot, we have the default frame (named ”frame0”) selected, and we can see that only the TOP keyboard row, and three top LEDs, are in WHITE. These are the only areas where the current effects will be displayed. All other keys/LEDs will be off - even if you select them in the Lighting Effects panel.

**The selected keys/LEDs in the Frame Animation Layer OVERRIDE the selected keys/LEDs in the Lighting Effects panel.**

![img](https://lh6.googleusercontent.com/rPEYEikJHx2Ml25R_-3Np2anX2NVFv8JJWytckpcm5CbaHSO35efgabSM6R4qYv5lw1C1q3cSnltBs3bmKOooldQgGLqHS0Q5ZlA9x3zkH9t35_qasUY9YaohUn1TSzPElGkcLpH)

### Working with the Frame Animation Layer panel

![img](https://lh5.googleusercontent.com/_L3cpG6qKK7sEdjfR3MmVzEw3-9F3HRta1EGzXAoZglDxbsAacBvhhZ8uFBHgn_H7zsyMaZ3J7tozMwUyg5GUeyJVY5uH6DbVZz-OcszEs5i378mzMPu2tM7MzbH-st2MSXOL2Q2)

There will always be at least one default layer to work with, in the frame animation layer panel. This is usually called “frame0”.

You can also choose to give each frame a meaningful name, to help in planning your animation.

If you do not intend to have an “animation”, you can just work with one frame layer here, and simply enable/select the keys/LEDs you want the lighting effects active for (this could be just specific keys or rows, or the entire board).

In the screenshot example above, we have three frames added, named “frame0”, “frame1” and frame2”. 

- When the lighting effect is activated, the board will run though every frame in this panel, in sequential order, using the “count” parameter to determine HOW LONG (in deci-seconds, ie 100 milliseconds) that frame is enabled, before moving to the next frame. 

- In this case, 

- - The board will play back frame0 for 100ms
  - Then play back frame1 for 500ms
  - Then play back frame2 for 2000ms
  - Then loop back around to frame0 and start again

![img](https://lh5.googleusercontent.com/GwYvIuhpuu7DMr79NKAgEzqyR9ZmlJwltZQ3MIxNmGLkgpe72C_h9F04TDSU9QV71-pqD4QHxGYRMFh_uQ4Q869XA5lXiMjqJmyZYRNUH0F-eOdByQNG_0xPiBPIDg-dajMvSsid)![img](https://lh6.googleusercontent.com/IM5wExqkIxjcgOEb00jdjgkeJi0iR4UqVMb7DhD9a3VU3tjqNMJbiGccOjTyi5BIbLeQCWgt_7FIwUw9QaMpDXG8XF7iWufnDXCSPPTNHRWL9CMO_V0bdpSbPoQdngPmjrzmAGY1)![img](https://lh6.googleusercontent.com/RiY-mavhr3JSgMag6VDFScATStAaiNzFNEptTvRoo3RStUp1BTGJ9uvZz9sQisVNjtxHIWKCMbCjpmiByrAKZiMZncm2pAqwIZxQxDugW2Dby34kup7eh9KSeWySbZZZHUfEYAJ3)

In the above sequence of screenshots you can also see that

- frame0 only has the top row + 3 top LEDs selected in white
- frame1 only has the second and third row selected in white
- frame2 has the fourth and fifth rows selected in white

This means that any lighting effects configured in the Lighting Effects panels, will only display on each of those selected rows, for the amount of time specified in the ‘count’ for each frame. All other keys/LEDs not selected will remain OFF for the duration of that frame. 

The buttons at the bottom of the panel allow you to:

- Create a new layer
- Duplicate the selected layer
- Delete the selected layer
- Move the selected layer up
- Move the selected layer down

### Working with the Lighting Effects panel

![img](https://lh6.googleusercontent.com/3DMXujDurDxOJ9Tz0KK00XgLnumHyBPZlFP6-MvpzXtBDw6omO7GmgP82S5Xsq65bQaw0EGkSCAtD8ap72JpASrzvPhwv72xEm8FVtRbfBydQVkOYUnKHN-xA60T1do1oNbpLwJF)

In this example we have added the three available lighting effects - Monochrome, RGB and Breathing, to the Lighting Effects panel. For each effect you add to this panel, you also need to select the keys/LEDs which you want this effect displayed on the virtual keyboard. 

**If no keys/LEDs are highlighted for that effect, then that effect will not light any keys/LEDs.** 

### Explaining the effects

- **Monochrome**

- Effect:

  - Displays a static color on the selected key/LED. 

  - Color:

  - The color displayed is represented by the color hex code column. 

    - Click on this value and start typing to enter a hex code directly, 
      - or click on this value then click on the color picker, to visually choose your intended color. 

    - In this example, the color displayed will be a static #ff0000 red.

  - Parameter:

  - The default value is 1. 

**Note: As of software version 6.0.0.35, this parameter has NO EFFECT, regardless what number is entered here. Please leave this value as “1”*


- **RGB**

- Effect:

  - Displays a smooth transition looping across the entire RGB spectrum (all colours). 

  - Color:

  - The color displayed is the STARTING color for the transition - the animation will start from this color and then cycle through the rest of the spectrum from here

    - Click on this value and start typing to enter a hex code directly, 
      - or click on this value then click on the color picker, to visually choose your intended color. 

  - Parameter:

  - How long (in deci-seconds) the transition will take to complete one full loop
    - EG in this example with a value of 20, the keyboard will take 2000ms to loop through the entire spectrum, starting from #002EFF blue. 


- **Breathing**:

- Effect:

  - Displays a smooth transition loop from the selected color to black (off) and back on again.

  - Color:

  - The color displayed is the TARGET color for the breathe effect. The animation will smoothly fade from black, to this color, and back to black again

    - Click on this value and start typing to enter a hex code directly, 
      - or click on this value then click on the color picker, to visually choose your intended color. 

  - Parameter1:

  - How long (in deci-seconds) the animation will linger at the target color, AND how long it will linger in the OFF state
    - EG: in this example with a value of 30, the keyboard will spend 3000ms displaying the target color of #65FF00 green, and it will also equally spend 3000ms in the OFF state. 

  - Parameter2:

  - How long (in deci-seconds) the animation will take to fade from the target color, to black, AND back again
    - EG: in this example with a value of 50, the keyboard will spend 5000ms fading from the target green to black, and it will also equally take 5000ms to fade from black back to green again.

So in this example with #65FF00 and values 30 and 50, the selected keys will

- Start at #65FF00 green, and display this green for 3000ms
- Take 5000ms to fade to black
- Spend 3000ms in black
- Take 5000ms to fade back to green
- repeat 

**TAKE THE MILLISECONDS timing here as a GUIDE - all timing inputs you configure are still subject to the OVERALL ANIMATION SPEED MODIFIER of the board (usually adjusted via FN-leftarrow or FN-rightarrow) - For example, if you set a fade effect to 5000ms (5 seconds) but speed up the board to its fastest setting, that fade effect will run in 1000ms (or so). So just be aware that what you’re seeing is affected by your board’s current overall animation speed.** 

**You can add as many effects to this panel as you like. But if you have multiple effects selected against the SAME keys/LEDs, only the LAST EFFECT in this list will be shown on the key. All previous effects will be overridden.** 

**NOTE: As of software version 6.0.0.39, it is NOT POSSIBLE to fade between two selected colors (eg RED to BLUE) using “Breathing”. You can only fade from the selected color, to black (off), and back to the same selected color again.*

**TIP: If you are making changes to an effect further up in your effect list, but you are not seeing this change reflected when you play back the animation to test it, check to ensure you have not accidentally selected that same key on another effect further down on the list.** 

The buttons at the bottom of the panel allow you to:

- Add a new effect
- Duplicate the selected effect
- Delete the selected effect
- Start an animation playback* of the current profile, so you can see it in action
- CANCEL all changes on this profile and return to the profile selection panel
- SAVE all changes against the current profile


**NOTE: The animation playback function will not always 100% reflect the final animation behaviour of your keyboard. This is because different keyboard PCBs will execute the animation instructions slightly differently - so this animation preview is indicative only. To see the actual effect on your keyboard, it is recommended to follow section 3 above and save and apply this profile to your keyboard, and test it in person, to see the final effect.* 

\-----------------------------------------------------------------------------------------------------------------------
