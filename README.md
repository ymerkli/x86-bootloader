# x86 bootloader

This is a small "bootloader" for x86 IBM-PC computers.
It doesn't do a lot - it basically only prints some predefined text to the screen.
My goal was to get more familiar with assembly.

## How to run
Check if you have Bochs installed and install it if not
```bash
sudo apt-get install bochs
```

Run Bochs
```bash
bochs -f bochsrc.txt
```