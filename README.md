# i5-4590-B85M-gt730-hackintosh
 
cpu：intel i5 4590
主板：asus B85M-G
顯卡：GT730-MG-2GD3

系統版本：macOS Catalina 10.15.3
OpenCore 版本：0.5.5
HD Graphics 4600：本人電腦的壞了，沒測試。
GT730：正常。原生驅動。注意：gt730 僅支持開普勒架構的。
3.5mm聲音：正常使用，使用AppleALC驅動。 DeviceProperties -> Add -> PciRoot(0x0)/Pci(0x1B,0x0) -> layout-id注入ID 07000000。
有線網卡：正常。使用了kexts/IntelMausi.kext
睡眠喚醒：正常。
關機開機：正常。
iCloud & App Store & iMessage & FaceTime：請自行生成MLB、 ROM、SystemSerialNumber、SystemUUID，並相應的修改PlatformInfo -> Generic。
AirDrop & HandOff & Continuity：正常。
