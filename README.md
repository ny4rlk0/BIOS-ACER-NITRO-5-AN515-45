<br>Added RTX 3070 firmware for this Laptop straightly dumped from chip with CH341A.
<br>If i fix my BIOS i will add dump of that too. (Unfortunely chip is dead for some reason. I cant even read it with CH341A. Tried every version.)
<br>Ordered a new one Winbond W25Q128JVSIQ 128M-BIT as replacement. (Couldn't find the Winbond W25Q128FVSQ but this should do the trick if CH341A will be able to detect new BIOS chip because old one does not getting detected.) Gonna flash the bios that i extracted from orginal BIOS Firmware first then solder it. If it's works, i will upload the contents of the chip here too.
<bold><b>BIOS FOR ACER NITRO 5 AN515-45</b></bold>
<br>Suggested Version: 1.06 (For Low Temps)
<br>Suggested Version: 1.10 (For extended support to Windows 11 Sun Valley 2 Update)
<br><a href="https://github.com/ny4rlk0/BIOS-ACER-NITRO-5-AN515-45/releases/download/BIOS_1.03_1.06_1.08_1.10/All_BIOS_ACER_NITRO_5_AN515-45-R0SE_10.12.2022_13.44.zip"><b>İndir / Download</b></a>
<br>
<br>Downloaded version is only for indirect installs. (Installing from running laptop, Installing with flash drive via BIOS Recovery Crisis Mode etc.)
<br>
<br>If you gonna use ch341a use the version in code section in upper. That is a extracted firmware exactly sized for flashing with CH341A.
<br>
<br>How did i get this? Opened .EXE file with 7ZIP extracted. Found a abobios.bin.
<br>Opened a Windows CMD same folder.
<br>extractor.exe abobios.bin extracted_abobios.bin
<br>Then before i use with Neo Programmmer 2.2.0.10 renamed file to abobios.bin
<br>You don't need to trust me. You can just do the same thing with any spare computer.
<br>I don't freaking know that why this is not mentioned anywhere...
<br>
<br>Included Versions: 1.03, 1.06, 1.08, 1.10
<br>
<br>You can switch any version of your wish as i patched them.
<br>You can downgrade BIOS with this.
<br>I'm not accepting any responsibility but i tested them in <b>AN515-45-R4SE</b>
<br>So they should work on any Nitro 5 AN515-45
<br>Pick a version then stick with it.
<br>Don't constantly change BIOS version since you are asking for bricking your computer.
<br>First version of BIOS is always superior for me because it will went in more testing during development.
<br>
<b><br> ---------- <!> Warning <!> ----------</b>
<br>Make sure laptop is connected to power supply and battery is charged fully.
<br>
<b><br> ---------- ~~ Update Logs ~~ ----------</b>
<br><b>BIOS v1.03</b> 1.Update LCD setting and brightness table.
<br><b>BIOS v1.06</b> 1.Update NV QBoost Setting. 2.Update AMD PI code. 3.Update new Panel ID.
<br><b>BIOS v1.08</b> 1.Improve for GPU protection 2.Enable fTPM support for china.
<br><b>BIOS v1.10</b> 1.Enable Win11 SV2 Support. Installs compatibility for the released
<br>Windows 11 version 22H2 called Sun Valley 2 update and also includes a previous bios update 
<br>called “1.Update NV QBoost Setting. 2.Update AMD PI code. 3.Update new Panel ID."
<br>Which the Combo PI is a kind of main container that includes 
<br>aspects such as VBIOS for the APU, SMU, PSP or ABL and where some data from AGESA itself is also included.
<br>And should be installed to make your laptop function properly.
<br>
<br>While turned off. Keep Press FN+ESC for BIOS Crisis Recovery Mode same time press and release power button. 
<br>This laptop looks for BIOS file named BIOS.fd or ME.fd in USB drive formatted as fat32.
<br>
<br>How to find BIOS file name for similiar laptops?
<br>Extract the BIOS file from EXE form with 7ZIP and open the abobios.BIN file with the HxD editor. 
<br>Press CTRL + F and search for .fd. In this way, you can find out which BIOS file name the laptop is looking for in BIOS restore mode.

