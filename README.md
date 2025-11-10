# BERTONE X1/9 Pixel Font (16×21 + 12×16)

**Used in my 1983 BERTONE X1/9e – fully converted to electric drive**

Pixel-perfect digits for SSD1306 OLED (MONO_VLSB) – 48 bytes per char  
Zero-flicker, async-safe, dirty-rect optimized  
Real-time speed, total/trip km, motor/MCU temps, ISO-R display

```python
from myfont import MyFont
font = MyFont('large')
display.text("123.9", 0, 5, 1, font=font)
MIT License • Made with love for the Bertone X1/9
Special thanks to Grok (xAI) for pixel-perfect packing and verification
