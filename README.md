# 🦾 Special Needs Communication Device
*Tactile Communication Device for Children in Special Needs*

---

## 🚀 Overview
- This project was a Final Project for the Engineering Projects class at CU Boulder, and presented at the Engineering Design Expo
- Communication Device inspired by Bop-It's tactile design was made to help kids with special needs communicate in an educational environment. 
- Project was designed with consulting from a local special needs teacher, and prototypes were field-tested in this teacher's classroom.
- Parts are designed to be modular, with emphasis on being interchangeable and accessible to those without engineering experience.
- MAIN-ASSM file in CAD Components will include all parts
- I was the CAD and Electronics Designer for this Final Project; All CAD files and images of electronics are my work (CAD images link to STL Preview)
  [![Full](images/Full.png)](STL/Full.STL)
  [![Inside](images/Inside.png)](STL/Full.STL)
- Printed Assembly with Electronics
  ![Full](images/FullPic.jpg)
---

## 🧠 Key Features
- 🔹Main Shell
  - 🔹Housing for Speaker, Arduino, Battery, and Wiring
  - 🔹Includes a magnetic Shape-Matching module on the top
  - 🔹Alignment tabs for assembly and slots for eletronics
  - 🔹Side Cut-outs and heat-inserts allow for easy assembly and interchangeable modules
  [![ShellTop](images/ShellTOP.png)](STL/ShellTOP.STL)
  [![ShellBot](images/ShellBOT.png)](STL/ShellBOT.STL)

- 🔹Each module houses button cutouts for easy button assembly
- 🔹6 Main "Bop-It" Modules:
    - 🔹Counting:
      - 🔹Buttons for numbers 1-6 are tactile and will say the numbers aloud through main speaker
      - 🔹Prototyped using numbers 1-6, but more numbers are easily implementable (0-9)
      - 🔹Field Expert reports that the tactile buttons and counting sounds help special needs children focus on counting tasks in a classroom setting
        ![Number](images/CountingPic.jpg)
        [![Number Module](images/Counting.png)](STL/Counting.STL)
    - 🔹Where? When? Why?:
      - 🔹Buttons are tactile and will say corresponding "Where?", "When?", and "Why?" aloud through main speaker
      ![Where, When, Why](images/WWWPic.jpg)
      [![WWW Module](images/WWW.png)](STL/WWW.STL)
    - 🔹Yes/No:
      - 🔹Buttons are tactile and will say corresponding "Yes" and "No" aloud through main speaker
      ![Yes/No](images/YesPic.jpg)
      ![Yes/No](images/NoPic.jpg)
      [![Y/N Module](images/YN.png)](STL/YN.STL)
    - 🔹Emotion Dial:
      - 🔹Potentiometer on the side controls a servo indicator cycles through various emotions
      - 🔹This module was emphasized by the field expert as one of the most needed communication assistance for young children
      ![Servo](images/ServoPic.png)
      [![Emotion Dial Module](images/Servo.png)](STL/Servo.STL)
    - 🔹Animal Sounds:
      - 🔹Buttons are very tactile and will make animal sounds when pressed
      - 🔹Cow, Pig, Dog, Cat sounds were implemented for our prototypes
      - 🔹After field-testing, field expert reports that the animal sounds help children relax when agitated in class 
      ![Animal](images/AnimalPic.jpg)
      [![Animal Module](images/Animal.png)](STL/Animal.STL)
    - 🔹Music:
        - 🔹Buttons will play a short musical piece when pressed
        - 🔹Music Selection: Mozart, Itsy-Bitsy Spider, Wheels-on-the-Bus, Twinkle-Twinkle Little Star
        - 🔹According to our field expert, the short pieces were effective in calming down agitated children, but could be distracting when focus is needed
          ![Music](images/MusicPic.jpg)
          [![Music Module](images/Music.png)](STL/Music.STL)
- 🔹Custom Button Plates:
  ![AnimalPig](images/AnimalPIG.png)
  ![AnimalCow](images/AnimalCOW.png)
  ![AnimalDog](images/AnimalDog.png)
  ![AnimalCat](images/AnimalCAT.png)
  ![MusicMozart](images/MusicMOZART.png)
  ![MusicSpider](images/MusicSPIDER.png)
  ![MusicWheels](images/MusicWHEELS.png)

---

## 🛠️ Technical Details

| Aspect | Description                                                     |
|:--|:----------------------------------------------------------------|
| **Tools / Languages** | SolidWorks, Arduino                                             |
| **Libraries / Frameworks** | N/A                                                             |
| **Hardware Used** | 3D printed parts, Heat Inserts, Arduino Uno, DIY Circuit Boards |
| **Fabrication** | SLS 3D printing, Soldering                                      |
| **Data I/O** | STEP/STL models, .gcode, .ino                                   |

---
