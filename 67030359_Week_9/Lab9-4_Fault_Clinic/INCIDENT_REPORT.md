# Engineering Forensic Incident Report - Lab 9.4
**ผู้รายงาน:** นายอัฐวุฒิ บัวเรียน (67030359)
**กรณีศึกษา:** Case 1: Black Screen
**สาเหตุ:** Charge Pump DC-DC step up voltage failure
**การแก้ไข:** oled_send_cmd(0x8D); oled_send_cmd(0x14); oled_send_cmd(0xAF);
