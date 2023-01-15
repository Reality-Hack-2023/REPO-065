
usb_port := "/dev/ttyUSB0"
firmware_file := ""

flash:
    esptool.py --before default_reset --after hard_reset --baud 115200 --port {{usb_port}} --chip esp32 write_flash -z --flash_size detect 0x10000 {{firmware_file}}

