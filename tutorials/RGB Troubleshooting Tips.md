# RGB Troubleshooting Tips



## because I'm not explaining this anymore

 ![:kek:](https://cdn.discordapp.com/emojis/618959795713605645.png?size=80)

---

- RGB LEDs work in a data chain meaning #4 won't work if #3 doesn't. 

- They're quite heat sensitive so solder them at about 280° - 300 °c. Keep in mind, you're more prone to cold joints with temps like these so that could be a reason your LEDs aren't working. 

- Flux is helpful but can also cause shorts so clean that up frequently with some isopropyl alcohol. 

- Data to set the colour and change the mode flows through the DIN - DOUT pins. if your LEDs look like rainbow vomit, you likely have a cold joint on those pins. Default colour is red meaning you have no data loss. 

- If your LEDs aren't turning on at all, verify they are oriented correctly, flashed with firmware that has them enabled and configured, and double the GND & VCC solder joints. 

- Look up the pin out for your LEDs. That'll help you understand how they work. 

-  A general set of steps is: 
  - Reflow the first non-working LED 
  - Reflow the last working LED
  - Replace the first non-working LED 
  - Clean up the flux and take a break
  
---

Good Luck ![:salute:](https://cdn.discordapp.com/emojis/745762392188649534.png?size=80) 