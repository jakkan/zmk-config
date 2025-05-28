# Quickstart

- Trigger github workflow to build firmware
- Unzip firmware `unzip firmware.zip`
- For each keyboard
  - Plug it in
  - Connect GND and RSP pins with "double-tap" to put board in bootloader mode
  - Check if the keyboard is detected `ls | grep sda`
  - Mount the keyboard `sudo mount /dev/sda /mnt/keeb`
  - Copy firmware to keyboard `sudo cp cradio_right-nice_nano_v2-zmk.uf2 /mnt/keeb`
  - Wait a moment for the keyboard to flash and restart

