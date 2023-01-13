# Light with pir

This small package allows you to customize the switching on and off of a light with pir.
You can decide whether to turn the light on when pur switches to on:
- Never
- Always
- After sunset
- Or in a specific time slot

You can decide whether to turn off the when the pir switches to off:
- Never
- Always
- After sunset
- Or in a specific time slot
- Delay in hours/minutes/seconds for turning off.

The card will be displayed according to the selections chosen. 

**REQUIREMENT**:

Install from HACS the custom <i>[auto-entities](https://github.com/thomasloven/lovelace-auto-entities)</i>.

**INSTALLATION**
- Insert the file  <i>[light_with_pir.yaml](https://github.com/marco-hacs/light-with-pir/blob/main/light_with_pir.yaml)</i> in your packages folder
- Customize your own entities 
```
# INSERIRE LE ENTITA' 
      Sensori di movimento: &pir 
        - binary_sensor.luce_studio
      Luci da accendere (supporta switch e light): &light 
        - switch.luce_studio
```
- Restart HomeAssistant
- Create a manual card and copy the contents of  <i>[card_light_whit_pir.txt](https://github.com/marco-hacs/light-with-pir/blob/main/card_light_with_pir.txt)</i>


https://user-images.githubusercontent.com/62516592/211549770-c25cc061-8fdc-435b-b60b-e5b203462646.mp4

https://community.home-assistant.io/t/light-with-pir/518043
