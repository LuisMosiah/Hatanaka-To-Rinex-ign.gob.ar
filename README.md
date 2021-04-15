# Hatanaka-To-Rinex-ign.gob.ar
To help the conversion from Hatanaka files to Rinex files (with crx2rnx.exe) and merge them with (teqc.exe) i create this simple code.
This information comes from the public base stations from Argentina IGN, there you can download at 1 hz the information from the public base station
The problem is when you have to convert one at one each file (g.21d, i.21d, k.21d, etc) and finally use the teqc.exe (https://www.unavco.org/software/data-processing/teqc/teqc.html) to merge those rinex files.
So the tool basically convert from .21d files to .21o files (.22o the next year and so on), and get to your clipboard the text to use in teqc.exe.
