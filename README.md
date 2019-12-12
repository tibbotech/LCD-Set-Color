# TPS2L LCD Set Color Demo

This demo runs on the TPS2L device.

It demonstrates two subroutines designed to assist in setting colors - *lcd_set_color_name* and *lcd_set_color_rgb*. 

### *lcd_set_color_name(color as lcd_colors, back_fore as lcd_back_fore)*

This subroutine sets an lcd property to a basic color which has been predefined in the *lcd_colors* enum. It takes two parameters:

1. A color from the *lcd_colors* enum.
2. Property to set. Either lcd.foreground, lcd.background or both

### *lcd_set_color_rgb(red as word, green as word, blue as word, back_fore as lcd_back_fore)* 

This subroutine sets an lcd property to a color based on user input RGB values. It takes four parameters:

1. Red RGB value
2. Green RGB value
3. Blue RGB value
4. Property to set. Either lcd.foreground, lcd.background or both