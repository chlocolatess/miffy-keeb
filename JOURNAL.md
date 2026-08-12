## 08/09/26: planning the keyboard & starting schematics
time: 3 hours

my very first electronics project! i wanted something small and easy to do as someone new to electronics so i chose this project through hack club!

i'm aiming for a small keyboard, something easy for me to design and complete considering how busy i will be when school starts, so i decided on a number pad keyboard (~16-30 keys & ortholinear). something like the images below:

![image.png](https://epomaker.com/cdn/shop/files/EPOMAKERTH33_9.webp?v=1762136949&width=500)
![image.png](https://epomaker.com/cdn/shop/files/EPOMAKEREK21QMK_08.png?v=1751436168&width=500)

i was thinking maybe each time a key is pressed, it lights up (RGB) and it has clicky switches (since those types are my favorite). i also think i want rotary encoders for volume like the images above. i'm very inspired by geg tech's [brew-keeb](https://github.com/geg-tech/brew-keeb) regarding its aesthetics and silkscreen designs:

![image.png](https://private-user-images.githubusercontent.com/123428389/571019803-607ac801-df65-48e3-8ca3-f5d9bf03c90a.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODYzMzI5NDAsIm5iZiI6MTc4NjMzMjY0MCwicGF0aCI6Ii8xMjM0MjgzODkvNTcxMDE5ODAzLTYwN2FjODAxLWRmNjUtNDhlMy04Y2EzLWY1ZDliZjAzYzkwYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwODEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDgxMFQwMzMwNDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZWZjYTVlZmQ2NWE4NzRjNjE2YmNjZWY0MTJjZjFmODNkZDIzZGUwZWRjNWJiODE0ZDdjMGU2M2JlZWE0NTk4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.BjN7kU_OqMHjcyO85NuC3xnKekbc1Kv2t05mCHugDck)

i moved onto the schematics in ki-cad and did a 4x6 matrix (im missing some keys because some are more than 2u and there is a rotary encoder). this includes the switches, diodes, raspberry pi, and stabs. i put the mounting hole and the rotary encoder at the bottom because i still haven't figured out how to connect it all together (i also need to find an addressable rgb led for the lighting up part of the keyboard) 
<img width="1680" height="1188" alt="image" src="https://github.com/user-attachments/assets/92b4e36f-fa13-4d5b-a0b8-03e474f60da0" />

i think there will be changes as i continue this project but i just hope to finish it by august 31 so i could submit it to hack club & i hope i learn a LOT of things from this project! i actually had a lot of fun learning new things today and i hope this grind and motivation is strong enough for me to finish 

## 08/10/26: continuing schematics & started on BOM
time: 3 hours

i also forgot to say in the last journal that i added footprints to the pico, diodes, switches, and stabs (besides the mounting hole, and rotaary encoders because im still working on that today). i also think im just gonna scrap the RGB led idea because im running out of time and i think im gonna put too much time into trying to figuring out how it works. 

ive finalized the schematics (slack people helped me) and checked it with the electrical rules checker to make sure everything is connected. it took me like an HOUR to figure out what was wrong with my matrix until i fixed it!!:
<img width="1680" height="1188" alt="Screenshot 2026-08-10 at 11 22 32 PM" src="https://github.com/user-attachments/assets/66097f4f-25ac-4f2a-9aa7-a8540bd2ec05" />

i also started on the bom since i finished the footprints of the schematics

## 08/11/26: continued BOM & started PCB design

i continued working on the BOM and filled out the things that i know that i need so far since i finished the schematics (finally)
<img width="946" height="490" alt="Screenshot 2026-08-11 at 4 01 53 PM" src="https://github.com/user-attachments/assets/77013293-3cb2-4e1e-8ef2-5bb655fba60e" />

i started working on the pcb (it looks a mess but it is a work in progress and i have school tomorrow). i did 19.05 spacing between each keys (idk how im gonna space it out for the rotary encoders, stabs, and what to do with the raspberry pi and the mounting holes, but that will be figured out soon):
<img width="1680" height="1188" alt="Screenshot 2026-08-11 at 9 46 14 PM" src="https://github.com/user-attachments/assets/5d917dea-c670-4fe4-aeff-bdf3b1299bac" />
