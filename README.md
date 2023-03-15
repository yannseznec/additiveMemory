# additiveMemory
experimental sound recording device for going back in time

Made in Pd (Pure Data): https://puredata.info

This code is designed to run on a Bela microcontroller: https://bela.io The main patch is _main.pd

There are two buttons - one button records 1 second of sound from input 1 on the Bela.

The other button plays back that sound, followed immediately by every previous 1 second sound that has been recorded. In the version downloadable here, that means you hear a bunch of sounds of me going backwards through my testing process, eventually ending with the first successful test.

As you add recordings the patch will get larger, and the length of time for listening back will get longer.

Let me know if you have any questions: yann@yannseznec.com
