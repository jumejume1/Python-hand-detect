# Python-hand-detect
Python hand detect mediapipe<br>
Python Hand Tracking | Cheap 3D ToF Depth Sensor Camera<br>

MaixSense-A010 is an extremely cost-effective 3D sensor module composed of BL702 + OPNOUS 100x100 TOF launched by Sipeed, which supports a maximum resolution of 100x100 and 8-bit precision, and comes with a 240x135 pixel LCD display to preview the depth map after colormap in real time.<Br>
![MaixSense-A010](https://wiki.sipeed.com/hardware/zh/maixsense/maixsense-a010/assets/ms_s.jpg)
<br>[Product Link](https://bit.ly/49QvL6h)
<br><br>Youtube overview <BR>
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/CPq58z2kVi8/0.jpg)](https://www.youtube.com/watch?v=CPq58z2kVi8)
<br>

Python <br>
```
from metasense import MetaSense

mp_hands = mp.solutions.hands
hands = mp_hands.Hands()
mp_draw = mp.solutions.drawing_utils

COM_PORT = "/dev/cu.usbserial-202206_1CF25B0"
BASE_BARTRATE = 115200
MAX_BARTRATE = 3000000

QUANTIZE = 2 # mm
```
