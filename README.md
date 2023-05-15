# extension-tld-abuse
A Proof-Of-Concept (POC) for the malicious use of extension-based TLDs such as ".zip" and ".mov".

This POC goes with my blog post here: https://blog.landon.pw/2023/file-hijacking-with-extension-based-tlds

1. User browses to an extension-based TLD (ie: `company-image.vhdx.zip`)
2. The website gets the User-Agent and determines the OS: Linux, Windows, Mac, iPhone, or Android
3. The website downloads the correct payload (ie: `company-image.vhdx.zip.exe`

Try it yourself (it won't actually download a malicious payload)
1. Download [company-image.vhdx.zip](https://company-image.vhdx.zip)
2. Download [kali-linux-qemu.qcow2.zip](https://kali-linux-qemu.qcow2.zip)

