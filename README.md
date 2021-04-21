# Abra A5 V15.6 Catalina
Abra A5 V15.6 Catalina EFI

Intel® Comet Lake Core™ i7-10750H 6C/12T; 12MB L3; 8GT/s; 2.6GHz > 5.0GHz; 45W; 14nm

Mobile Intel® HM470 Chipset

4GB GDDR6 nVIDIA® GeForce® GTX1650 128-Bit DX12 Refresh (2020)

15,6" FHD 1920x1080 120Hz IPS Mat LED

16GB (2x8GB) DDR4 1.2V 2933MHz SODIMM

256GB SAMSUNG PM991 M.2 SSD PCIe 3.0 x4 (2050 MB/s - 1000 MB/s)

Intel® Wi-Fi 6 AX201, 2x2 AX + Bluetooth 5.1 M.2 2230 (2,4 Gbps)

Everything works! Yeah, you read right! Even my PM991! But how, right? I manage to copy my macOS from External HDD to PM991 disk and then used NVMeFix, HackrNVMeFamily and custom SSDT. So, you make sure change SSDT before boot like guide below(Yeah, you have to boot with another compatible SSD/HDD before for editing SSDT with MaciASL):
https://github.com/tylernguyen/x1c6-hackintosh/issues/43

And please make sure you changed your Serial ID, etc. You can do that with this:
https://github.com/corpnewt/GenSMBIOS

For editing your config file:
https://github.com/corpnewt/ProperTree
