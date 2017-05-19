# 256
a Windows/Console (Vector-based,Unicode addressed) True-Type(TTF) Font with full Extended ASCII-8 Support where the old ASCII-7 Spectrum of 128 characters is max-out and Mapped to 256 characters Utilizing Unicode C0 and C1 provisional space instead of the Windows Bitmap-base fonts of windows 95/MS-DOS. There are changes to be made to this charset because glyphs are mapped in other provisional or canonical reserved Unicode addresses/regions which may conflict on a future ASCII+Unicode merged font. 

I'm currently using the US codepage 437 character mapping with some customization, this may change in the future.
Think IBM OS-2/MS-DOS CP-437 or classic Atari game maps, where all 256 positions are used.
In Unicode fonts, the actual keyboard character is linked to the glyph itself, which creates conflicts in the C0 and C1 control Regions, because they are already pre-provision in unicode mapping in multiple different areas depending on Western-Latin 1, etc., so if the keyboard characters are used in the C0/C1 areas they cant be used else where in the unicode map/font or visa versa (one time used keyboard char.).
