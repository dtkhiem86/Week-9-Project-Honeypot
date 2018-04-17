# Week-9-Project-Honeypot
Week 9 Project: Honeypot

Which Honeypot(s) you deployed : Ubuntu - Dionaea with HTTP, Ubuntu - Snort

Any issues you encountered: 

I have to apply patched fork due compatability issues:
Command Line>
cd /opt/
git clone https://github.com/0x7fff9/mhn.git
cd mhn
git checkout 0x7fff9-encoding_patch
/>

I also have to fix "supervisorctl and hpfeeds-broker fatal reading error:
Command Line>
./opt/hpfeeds/env/bin/python -m pip install --upgrade pyopenssl
supervisorctl start hpfeeds-broker
/>

A summary of the data collected: number of attacks, number of malware samples, etc.

All attacks are included on session.json file attached below

Any unresolved questions raised by the data collected
I have 2 unresolved questions:

Where is the SSID? and Where specifically is the hash? 
