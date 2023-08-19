# esp32-problem
esp32 problem: MD5 of the file does not match data in flash!


open cmd 

python
exit()

pip install esptool

python -m esptool --chip esp32 --port COM5 --baud 115200 --after hard_reset erase_flash

paython -m esptool --port COM5 write_flash_status --non-volatile 0
