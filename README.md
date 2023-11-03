<p align="center"><img src="https://github.com/K3V1991/QuickTime-Files-for-qaac/blob/main/Audio.png" width="200"></a>
<h1 align="center"><b>QuickTime Files for qaac CLI QuickTime AAC/ALAC Encoder</b></h1>
<br />

<p align="center">
<img src="https://img.shields.io/github/v/release/K3V1991/QuickTime-Files-for-qaac?color=blueviolet&style=for-the-badge">
<img src="https://img.shields.io/github/downloads/K3V1991/QuickTime-Files-for-qaac/total?color=sucess&style=for-the-badge">
<href="https://liberapay.com/K3V1991" alt="LiberaPay"><img src="https://img.shields.io/badge/Liberapay-F6C915?style=for-the-badge&logo=liberapay&logoColor=black">
<href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white">
<href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white">
<href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white">
</p>
<hr />
<br />

## NFO:
* Apple's [Core Audio AAC Encoder](https://wiki.hydrogenaud.io/index.php?title=Apple_AAC) for [qaac](https://github.com/nu774/qaac)
* Required for qaac to encode without installing iTunes, QuickTime, or Apple Application Support
* Extracted from the iTunes Installer using the [makeportable](https://github.com/nu774/makeportable) Script from the [qaac's Site](https://sites.google.com/site/qaacpage)
<br />

## Installation:
1. Download the latest Release Zip
2. Extract and place the Files besides the qaac Executable File
3. qaac is now portable
<br />

## icudt62.dll Dummy File:
* The "icudt62.dll" aka the International Components for Unicode Data File inside the QT Zip is just a Dummy File because most of the Content in the icudt62.dll is not required and saves Disk Space
* The File icudt62.dll can't be deleted, the Encoder would refuse to work if it is not present
* Original Files under Releases
* Generated using [Dummy DLL Generator](https://github.com/ykhwong/dummy-dll-generator)
<br />

## Microsoft Visual C++ Runtime:
* If you have it installed, no need to copy msvcp140.dll and vcruntime140.dll
<br />

## More Infos:
* [Apple AAC - hydrogenaud](https://wiki.hydrogenaud.io/index.php?title=Apple_AAC)
* [EAC and QAAC - hydrogenaudio](https://wiki.hydrogenaud.io/index.php?title=EAC_and_QAAC)
