# esp32-problem
esp32 problem: MD5 of the file does not match data in flash!

[![Watch the video](https://img.youtube.com/vi/w3qaa1JVWQI/0.jpg)](https://youtu.be/w3qaa1JVWQI)

open cmd 

python
exit()

pip install esptool

python -m esptool --chip esp32 --port COM5 --baud 115200 --after hard_reset erase_flash

paython -m esptool --port COM5 write_flash_status --non-volatile 0
