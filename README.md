# TD-W8970-NetUSB-Fix-v1-
Fix NetUSB Bug for TD-W8970 v1 - Firmware Version: 0.6.0 2.14 v000c.0 Build 150619 Rel.50856n


A serious vulnerability affecting the NetUSB kernel driver developed by Taiwan-based tech company KCodes exposes millions of routers to hack attack.
Researchers at SEC Consult discovered that the NetUSB driver is plagued by a kernel stack buffer overflow vulnerability (CVE-2015-3036) that can be exploited by an unauthenticated attacker to execute arbitrary code or cause a denial-of-service (DoS) condition. The flaw, caused by insufficient input validation, can be triggered by specifying a computer name that is longer than 64 characters when the client connects to the server.

SEC Consult has confirmed that the vulnerability affects the latest firmware versions for TP-Link TL-WDR4300 V1, TP-Link WR1043ND v2, and Netgear WNDR4500. Researchers also identified the NetUSB feature in tens of router models from D-Link, Netgear, TP-Link, TRENDnet, and ZyXEL.
https://www.sec-consult.com/fxdata/seccons/prod/temedia/advisories_txt/20150519-0_KCodes_NetUSB_Kernel_Stack_Buffer_Overflow_v10.txt


Fix for TD-W8970 (v1) is unavailable on official website but the tech support sent me a fixed firmware:

Hi Mauro,
Thank you very much for your email requesting information about our product.
This is jessie from TP-LINK technical support department.
Please check the firmware in the attachment.
If you need any further help, please feel free to let me know.
To get technical support more quickly, please go to http://www.tp-link.com/en/support/faq/
Best Regards!
---------------------------------------------
Jessie Wang
Technical Support Engineer
TP-LINK TECHNOLOGIES CO., LTD.
E-mail: jessie.wang@tp-link.com
Website:http://tp-link.com/en/Support/
