
A keyboard made by me
I decided to build a 75% mechanical keyboard because I've wanted one for a long time. Right now, I am stuck using a basic office membrane keyboard which absolutely sucks for a coder and gamer like me. Buying a pre-built mechanical keyboard can be incredibly expensive, so I figured—why not learn how to make one myself through Hack Club?

I started by planning the layout of my keyboard. I hand-drew it first, and then formatted a clean layout map. I am specifically taking my design and layout inspiration from the aula f75  making it compact—not too small, nor too big. Perfect for gaming and coding


┌─────────────────────────────────────────────────────────────────────────┐
│ [Esc] [F1] [F2] [F3] [F4] [F5] [F6] [F7] [F8] [F9] [F10] [F11] [F12]    │
│ [◉] │                                                       │
├─────────────────────────────────────────────────────────────────────────┤
│ [`~] [1!] [2@] [3#] [4\$] [5%] [6^] [7&] [8*] [9(] [0)] [-_] [=+] [⌫]    │
│ [Tab] [ Q] [ W] [ E] [ R] [ T] [ Y] [ U] [ I] [ O] [ P] [[] []] [\]     │
│ [Caps] [ A] [ S] [ D] [ F] [ G] [ H] [ J] [ K] [ L] [;:] [ '"] [Enter]  │
│ [Shift] [ Z] [ X] [ C] [ V] [ B] [ N] [ M] [,<] [.>] [/?] [Shift] [↑]   │
│ [Ctrl] [Win] [Alt]        [       SPACE       ] [Fn] [←] [↓] [→]        │
└─────────────────────────────────────────────────────────────────────────┘
  <img width="1536" height="1024" alt="ChatGPT Image Sep 3, 2026, 05_08_34 PM" src="https://github.com/user-attachments/assets/96ec96c0-1729-4df8-8921-a81e7a69d798" />
yup this is what i am tring to make and yeah i used gpt to make it except the led display i canceled it
The OLED display and the volume knob will sit right beside the F12 key, exactly like the Aula F75.


I am using the official Hack Club KEEB guides along with an ai cuz i am a complete beginner and yeah i freaking want that keyboard
6 Rows x 16 Columns (to perfectly route all 87 keys + the encoder click switch).
Raspberry Pi Pico / RP2040 chip.
<img width="340" height="502" alt="Screenshot 2026-09-03 172219" src="https://github.com/user-attachments/assets/5aee4c01-fe10-4435-a01e-97926f208a7f" />
phew first step done successfullyy
<img width="537" height="937" alt="Screenshot 2026-09-03 180454" src="https://github.com/user-attachments/assets/865768ab-ba65-4a89-ac4b-ca69760700f1" />
damn i did this in day 1.<img width="480" height="270" alt="thumbnail" src="https://github.com/user-attachments/assets/fa6a10b0-e1bb-46b8-9cae-08659c40867d" />
you can watch my 1hr timelapse of day 1 here (https://lapse.hackclub.com/timelapse/bA46f2fJlDjw)
the biggest strrugglee i faced in day 1 was connecting wire as it wont connect i was very annoyed.
Today i will be doiin the rgb yeahhhh progresss
<img width="1332" height="483" alt="image" src="https://github.com/user-attachments/assets/9cda7a57-c446-46bf-af57-e4048ebdf59a" />
damn first half done 
Hell yeahh i finnally feeel some progess my 2nd day's hardest challenge was connecting the wires as some were misaligned .
My part2 timrlapse : https://lapse.hackclub.com/timelapse/8E3A1pW5wHUZ
<img width="1401" height="867" alt="image" src="https://github.com/user-attachments/assets/9d8afeea-14ab-410c-87c8-31a09d268b7b" />
day 3 did the connections , annoted the parts now for the pcbb
<img width="1392" height="935" alt="image" src="https://github.com/user-attachments/assets/eead183b-c759-4564-836d-dc4dcd4c4614" />
finallly ALLL DONEE NOW PCBBB



Ummmm i had to redo the pcb and sch thrice and yeahh it was a successs 0 warnings and 0 errors idk how i did it damn
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/a9f3f691-67b7-4120-a4c0-ad4550dce847" />
This has been the biggest challege in my life and the routing of wires was the most frustrating thing ever i am glad it ended now i will move onto the 3d model
alr heres the necessary docs
[Keyboard v3.csv](https://github.com/user-attachments/files/32464854/Keyboard.v3.csv)
"Id";"Designator";"Footprint";"Quantity";"Designation";"Supplier and ref";
1;"A1";"RaspberryPi_Pico_Common_THT";1;"RaspberryPi_Pico";;;
2;"D1, D2, D3, D4, D5, D6, D7, D8, D9, D10, D11, D12, D13, D14, D15, D16, D17, D18, D19, D20, D21, D22, D23, D24, D25, D26, D27, D28, D29, D30, D31, D32, D33, D34, D35, D36, D37, D38, D39, D40, D41, D42, D43, D44, D45, D46, D47, D48, D49, D50, D51, D52, D53, D54, D55, D56, D57, D58, D59, D60, D61, D62, D63, D64, D65, D66, D67, D68, D69, D70, D71, D72, D73, D74, D75, D76, D77, D78, D79, D80, D81, D82, D83, D84";"D_DO-35_SOD27_P7.62mm_Horizontal";84;"1N4148";;;
3;"S1, S2, S3, S5";"STAB_MX_2u";4;"MX_stab";;;
4;"S6";"STAB_MX_P_6.25u";1;"MX_stab";;;
5;"SW1";"RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm";1;"RotaryEncoder_Switch";;;
6;"SW2, SW3, SW4, SW5, SW6, SW7, SW8, SW9, SW10, SW11, SW12, SW13, SW14, SW15, SW16, SW17, SW18, SW19, SW20, SW21, SW22, SW23, SW24, SW25, SW26, SW27, SW28, SW29, SW30, SW31, SW32, SW33, SW34, SW35, SW36, SW37, SW38, SW39, SW40, SW41, SW42, SW43, SW44, SW45, SW46, SW47, SW48, SW49, SW50, SW51, SW52, SW53, SW54, SW55, SW56, SW57, SW58, SW59, SW60, SW61, SW62, SW63, SW64, SW65, SW66, SW67, SW68, SW69, SW70, SW71, SW72, SW73, SW74, SW75, SW76, SW77, SW78, SW79, SW80, SW81, SW82, SW83, SW84";"SW_MX_1u";83;"SW_Push";;;
heres the entire bill of materials
and the zip folder including um many thingas
[keyboardv3.zip](https://github.com/user-attachments/files/32464870/keyboardv3.zip)
and noww i am heading towards this 3d modelling
