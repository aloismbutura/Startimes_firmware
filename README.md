##STARTIMES-KENYA FIRMWARE

This folder contains the firmware obtained from a working startimes Kenya decoder stored as a binary file named firmware.
It also contains the output message spew of flashrom running on a raspberry pi that was used to connect to the flash chip via SPI.
It also contains text files named strings.out and full-strings.out that were obtained by running strings on the binary firmware file with the difference between them being that the full strings file shows any printable characters therefore the possibility of getting more characters that do no make sense.strings has its -n parameter set to 10 to produce string.out.
