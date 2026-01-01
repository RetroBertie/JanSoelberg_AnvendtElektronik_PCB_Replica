#Jan Soelberg: Anvendt Elektronik (1970) - PCB Replica
by RobertK a.k.a. Retro Bertie (2026)
RetroBertie@outlook.com
Version 1.0 (2026-01-01)

This is a replica of the PCB that came with the book "Anvendt Elektronik" by Jan Soelberg, initially published in Danish language in 1970. It was later translated to Swedish ("Tillämpad Elektronik"), German ("Amateur Elektronik") and English ("Amateur Electronics"). The book can be downloaded in different languages from this website:
https://www.ae80.dk/index.php/jostykit-filer/ae-boeger/ae-boeger/

As a teenager in the 1980s, I made my first steps into electronics with this book (our public library had a copy), but due to my lack of talent I didn't get very far. A few years ago, I acquired a copy of that book for nostalgic reasons, but it came without the board. I felt that the book was incomplete without the PCB, so I decided to create this replica.

I did the following changes and improvements to the new PCB:
- Modern symbols
- Part names are printed beside the parts and not underneath, so you can still read the writing when the part is installed
- Thick ground lines instead of large ground planes
- On the back side, the lines and numbers are printed instead of being made of copper
- An additional 2.54 mm pin header pair for voltage supply on each circuit
- The voltage supply connection between the circuits can be controlled with solder bridges
- AE4 (flasher): optional LED instead of a bulb

Bug fixes:
- AE1: the part names T1 and T3 had been swapped. Their types are identical, so that bug had no effect.
- AE3: the part names C2 and C4 had been swapped. Their values are identical, so that bug had no effect.

I did not fix the following bug:
- AE7: Compared to the schematic, C1 is connected to the wrong pin of T1. This however only results in an inverted signal, which does not matter on such an RC generator.

I have also created a bill of materials (BOM) file. The parts differ among the various editions of the book, I would recommend using the values from the Swedish edition, because they obviously fixed errors in the AE7 circuit which have not been fixed in the German edition, despite the latter one having been published a year later.

The Gerber files can be used for ordering boards at PCB manufacturers like JLCPCB.
I have used Sprint Layout for creating this board, and I have also published the .lay6 file. I was using the files JanSoelberg_AnvendtElektronik_1971_Front.jpg and JanSoelberg_AnvendtElektronik_1971_Back_Mirrored.jpg as backdrops (150 DPI, X-Offset -18 for the back side).

Contact me if you should find any bugs in the layout, or if you can tell me that everything is working as it should.

Thanks to Forum64 users Unseen, Zaphod and Retro-Rentner for their support. The images of the book and the board are from an internet auction which is no longer online, so I can't give credit to the photographer.
