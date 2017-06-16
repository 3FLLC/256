# 256 -the one of a kind font
![GitHub Logo](https://github.com/dernyn/256/blob/master/256.png)
a (Vector-based,Unicode addressed) Windows True-Type Font(TTF)- with full Extended ASCII-8 Support where the old ASCII-7 Spectrum of 128 characters is max-out and Mapped further into the 256 character region, Utilizing Unicode C0 and C1 provisional space instead of the Windows Bitmap-base fonts of windows 95/MS-DOS which makes this font unique and one of a kind. There are changes to be made to this charset because glyphs are mapped in other unicode provisional spaces or canonical reserved Unicode addresses/regions which may conflict on a future improved ASCII+Unicode combination or merged font. 

I'm currently using the US codepage 437 character mapping standard with some customizations, which may change in the near future.
So, Think IBM OS-2/MS-DOS CP-437 or classic Atari game maps, where all 256 positions of the 8 bits are used.
In Unicode fonts, the actual keyboard character is linked to the glyph itself, which creates conflicts in the C0 and C1 control Regions, because they are already pre-provision elsewhere in unicode mapping in multiple different areas depending on standard such as; Western-Latin 1, etc., so if the unique keyboard character itself is used in the C0/C1 areas they can't be re-used elsewhere in the unicode map or in the font file itself.(basically one keyboard char per glyph)

![GitHub cp437](https://github.com/dernyn/256/blob/master/cp437.png)

