# cautiva-virt-clone

- BUILD /root/bin/START
- BUILD /root/bin/CLEAN

- mkdir /root/bin
- echo '/root/bin/START | tee /root/bin/START.log' >> /etc/rc.local
- chmod +x /root/bin/START
- chmod +x /root/bin/CLEAN
- CLEAN
