# EFI_Hackintosh_TAG
EFI for Asus Z390-i, 9900k, stock wifi card, iGPU, dGPU disabled with ACPI

Windows and MacOS are installed on separate SSDs, hence, require changing BIOS Boot Order to boot to respective OSes. For this reason, OpenCore's picker has been turned off for smoother boot experience.

CONFIGURATION:
    1. Motherboard: Asus ROG Z390-i mini-ITX
    2. CPU: 9900k at 5Ghz
    3. RAM: Trident Royal Z 32GB - 3300Mhz
    4. GPU: 2080 ti - unsupported dGPU - disabled by ACPI (Windows uses DisplayPort, MacOS uses HDMI coming from iGPU)
    5. Wireless card: stock Intel 9560-AC
    6. Storage 1: Samsung EVO Plus 2TB (Windows and data)
    7. Storage 2: Samsung EVO 1TB (MacOS and extra data)
    
WORKING:
    1. Pretty much everything for everyday use (wifi, shutdown, restart, etc.)
    
PARTIALLY WORKING:
    1. Sleep (fan & RGB LED still running while sleeping)
    
NOT WORKING:
    1. Bluetooth functionality
