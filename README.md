# 7inch-Screen-SSD1963-ESP32-support-Tools
This is repo is to help people who may have purchased one of these cheap screens and as usual the manufactures provide no support what so ever.

The products I have used to create this are and ESP and the 7 inch screen.
_ screen https://www.aliexpress.com/item/1005003943276599.html?spm=a2g0o.productlist.main.9.e1c4bf3aNLFraw&algo_pvid=4ff2ac16-910b-467c-a956-92a439f93879&algo_exp_id=4ff2ac16-910b-467c-a956-92a439f93879-4&pdp_npi=4%40dis%21AUD%2151.19%2151.19%21%21%21240.89%21240.89%21%402101ef6817289643095366115e7525%2112000027524407523%21sea%21AU%21822052238%21X&curPageLogUid=ELqunpVQyEjM&utparam-url=scene%3Asearch%7Cquery_from%3A

_ https://www.aliexpress.com/item/1005006220389074.html?spm=a2g0o.productlist.main.27.476d4350346I7n&algo_pvid=108d8f32-d26b-4248-b2b8-c75c629a11ea&algo_exp_id=108d8f32-d26b-4248-b2b8-c75c629a11ea-13&pdp_npi=4%40dis%21AUD%2119.33%215.61%21%21%2189.51%2125.96%21%402101c59517315906743975794e6af7%2112000036337209453%21sea%21AU%21822052238%21X&curPageLogUid=01N1aVGsafHH&utparam-url=scene%3Asearch%7Cquery_from%3A

The libraries you will need for this setup are:

#include <TFT_eSPI.h>
#include <XPT2046_Touchscreen.h>
#include <SPI.h>
#include <Wire.h>

!!!This has not yet been tested with the SD card!!!! 

If anyone wants to contribute please add examples and whatever you have to help others

- Pin mappings are attached
- front and back photos of the screen to make sure you have the right one
- and a picture of the ESP32 that was used for this.

![SSD1963_front](https://github.com/user-attachments/assets/656f4d39-a131-4115-9fe8-646593f540e2)
![SSD1963_Back](https://github.com/user-attachments/assets/c7ba7b42-039b-4949-9f20-2074bb510e62)
![PinMappings](https://github.com/user-attachments/assets/63997a77-5ae2-4ad8-8fe0-d9b696b22ec0)
![ESP32](https://github.com/user-attachments/assets/81d2004e-27f8-441d-bcbb-c0ee8289c0c7)
