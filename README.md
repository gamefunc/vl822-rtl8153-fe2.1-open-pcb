# vl822 rtl8153 fe2.1 open pcb project;

vl8153: usb3 1G netcard;

vl822: 4 port usb3.2(usb 3 gen2) hub;

fe2.1 usb2 7 port hub;


verify pass;

pcb online view: https://oshwhub.com/gamefunc/pcexttt

maybe this link direct view pcb: https://pro.lceda.cn/editor#id=8ae09c9b107342a8a52cace06771267e

or use jlc_eda_pro open: pc_ext_vl822+fe2.1+rtl8153.eprj_v8.2.eprj

not need: SPI FLASH CHIP AND FIRMWARE; 

ok+:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/ok%2B.jpg)

ok1+:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/ok1%2B.jpg)

ok-:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/ok-.jpg)

pcb+:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/empty%2B.jpg)

pcb-:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/empty-.jpg)


# verify test env: i5-2550k(my pc Motherboard only support usb 3.0):

usb3_vl822_verify:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/vl822_usb3_verify.png)

usb2_fe2.1_verify:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/fe2.1_usb2_verify.png)

rtl8153_verify2:
![image](https://raw.githubusercontent.com/gamefunc/pcb_vl822-fe2.1-rtl8153/main/rtl8153_verify2.png)


2022/08/31 v8.2: fix rtl8153 only 33mb/s work on usb2; because rx1 tx1 diff pair not_ed X connect, so usb3 not negotiations success, now fix it, let rtl8153 work on usb3;
