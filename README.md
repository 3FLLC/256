# 256 -The one of a kind font
This Font is a tribute to the IBM PC 5150 character set and TypeFace used in the U.S. region by IBM called CP437 with some modifications and adapted to be used with any version of the MS Windows Operating System and Linux(using OTF) by Utilizing Unicode Mappings which most similar fonts ignore in True-Type Fonts(.TTF). As the name implies all 256 characters are mapped and can be used to view NON-Printable ASCII Characters normally hidden or Ignored by default by the operating system enviroment and Text Editors.There is no other Unicode Font in the wild capable of doing this in the Windows OS in 2017, (Which is weird and may seem Magical). And Yes!, this Font allows you to see the space character, tab and carriage return(CR+LF) in text editors, plus all the other special characters most are ignorant about.
<br>
![GitHub Logo](https://github.com/dernyn/256/blob/master/256.png)
It is an ISO 10646-1(Unicode,BMP) encoded -(Vector-based,proper Unicode addressed) Windows True-Type Font(TTF)- with full Extended ASCII-8 Support(ISO/IEC 8859) where the old ASCII-7 Spectrum of 128 characters is max-out and Mapped further into the 256 character region,like the IBM-PC 8-bit CGA card.This font is utilizing Unicode C0 and C1 Controls provisional space instead of the Windows Bitmap-base .FON fonts of Windows 95/MS-DOS, which is what makes this font unique and one of a kind. There are changes to be made to this charset because glyphs are mapped in other unicode provisional spaces or canonical reserved Unicode addresses/regions which may conflict on a future improved ASCII+Unicode combination or merged font. 

<H3><b>Dedicated Regions:</b></H3>
C0 Controls Character U+0000-U+001F
<br>
</br>
C1 Controls Character U+0080-U+009F
<br>
</br>
I'm currently using the US codepage 437 character mapping standard with some customizations, which may change in the near future.
So, Think IBM OS-2/MS-DOS CP-437(DOS Code Pages) or classic Atari game maps, where all 256 positions of the 8 bits are used, like the ISO 8859-1 standard.
In Unicode fonts, the actual keyboard character is linked to the glyph itself, which creates conflicts in the C0 and C1 Controls Regions, because they are already pre-provision elsewhere in unicode mapping in multiple different areas depending on standard such as; Western-Latin 1, etc., so if the unique keyboard character itself is used in the C0/C1 Controls areas they can't be re-used elsewhere in the unicode map or in the font file itself.(basically one keyboard char per glyph)

There are some customizations on some character 0x00 for 0x32 which makes the space character now a viewable character and 0x255 is my own creation.


<H3><b>The difference:</b></H3>
This is the original bitmapped windows version of the US codepage 437 without the unicode mappings, as you can see it's very limited,and it's non-unicode and non-truetype.

![GitHub cp437](https://github.com/dernyn/256/blob/master/cp437.png)


Future release:
Monospaced version to use on the windows console (cmd.exe) with full 256 ASCII-8 support.
add a normalized version without the viewable space charcter.
