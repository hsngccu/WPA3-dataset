# The-WPA3-Dataset

This work is from the paper "Empirical Evaluation of Wi-Fi Handshake Attacks: The WPA3 Dataset". The WPA3 Datset folder provides the raw packet data (pcap file). The csv files are at the WPA3 Dataset csv folder.

## Attack Scripts of Dataset Collection

We utilize open-source tools to implement and complete various attack scripts. Table below provides detailed information on each implemented attack.

|Class|Attack|Used Tool|
|--|--|--|
|1. BF|Beacon Flood|MDK3|
|2. Deauth|Deauthentication|hostapd modified by [[1]](https://github.com/neildalal/WPA3-Attacks-IDS)|
|3. SAE_CV|SAE Commit Value Out-of-range|hostapd modified by  [[1]](https://github.com/neildalal/WPA3-Attacks-IDS)||
|4. UGD|Unsupported Group Downgrade|hostapd modified by  [[1]](https://github.com/neildalal/WPA3-Attacks-IDS)||
|5. SAE_AF|SAE Authentication Flood|Dragonblood  [[2]](https://github.com/vanhoefm/dragondrain-and-time)| PoC tool|
|6. TSC|Timing Side Channel|Dragonblood  [[2]](https://github.com/vanhoefm/dragondrain-and-time)| PoC tool|
|7. DG|WPA3 Downgrade|modified KRACK [[3]](https://github.com/vanhoefm/krackattacks-poc-zerokey) PoC tool|
|8. KRACK_DG|KRACK with WPA3 Downgrade|modified KRACK [[3]](https://github.com/vanhoefm/krackattacks-poc-zerokey) PoC tool|

## Reference
[1]  N. Dalal, N. Akhtar, A. Gupta, N. Karamchandani, G. S. Kasbekar, and
J. Parekh, “A Wireless Intrusion Detection System for 802.11 WPA3 Networks,”
in 2022 14th International Conference on COMmunication Systems & NETworkS
(COMSNETS), Bangalore, India, 2022, pp. 384–392. [Online]. Available:
https://github.com/neildalal/WPA3-Attacks-IDS

[2] M. Vanhoef and E. Ronen, “Dragonblood: Analyzing the Dragonfly Handshake
of WPA3 and EAP-pwd,” in 2020 IEEE Symposium on Security and Privacy
(SP), San Francisco, CA, USA, 2020, pp. 517–533. [Online]. Available:
https://github.com/vanhoefm/dragondrain-and-time

[3] M. Vanhoef, “Key Reinstallation Attacks: Forcing Nonce Reuse in WPA2,” in
Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communi-
cations Security, Dallas, Texas, USA, 2017, p. 1313–1328. [Online]. Available:
https://github.com/vanhoefm/krackattacks-poc-zerokey

