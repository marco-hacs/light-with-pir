# Light with pir

Questo piccolo package consente di personalizzare l'accensione e lo spegnimento di una luce con pir.

**REQUISITO**:

Installare da HACS il custom <i>[auto-entities](https://github.com/thomasloven/lovelace-auto-entities)</i>.

**INSTALLAZIONE**
- Inserire il file  <i>[light_with_pir.yaml](https://github.com/marco-hacs/light-with-pir/blob/main/light_with_pir.yaml)</i> nella propria cartella packages
- Personalizzare le proprie entità 
```
# INSERIRE LE ENTITA' 
      Sensori di movimento: &pir 
        - binary_sensor.luce_studio
      Luci da accendere (supporta switch e light): &light 
        - switch.luce_studio
```
- Riavviare HomeAssistant
- Creare una card card manuale e copiare il contenuto di  <i>[card_light_whit_pir.txt](https://github.com/marco-hacs/light-with-pir/blob/main/card_light_with_pir.txt)</i>


https://user-images.githubusercontent.com/62516592/211549770-c25cc061-8fdc-435b-b60b-e5b203462646.mp4

