# Ch3-1. ESXi系統安裝

> 請先準備好一台硬體可以支援Esxi系統伺服器主機或個人主機，並準備好Esxi系統之安裝iso檔，燒成光碟或者USB開機碟預備使用。

![](/assets/esxi_installation_1.JPG)

## 安裝流程開始

### 調整開機順序（BIOS）

1.將安裝光碟放入電腦光碟機中（或者將Esxi USB開機隨身碟插入電腦）。

![](/assets/esxi_installation_2.JPG)

2.開機並點選delete鍵，進入BIOS畫面（各主機BIOS畫面不同，請按照自身狀況調整）。

![](/assets/esxi_installation_3.JPG)

3.BIOS畫面如下。

![](/assets/esxi_installation_4.JPG)

4.點選開機順序頁面。

![](/assets/esxi_installation_5.JPG)

5.將光碟機或者USB開機隨身碟調整到開機順位一。

![](/assets/esxi_installation_6.JPG)

6.離開BIOS（通常點選ESC 或者 F10）。

![](/assets/esxi_installation_7.JPG)

### 開始Esxi安裝

7.等待Esxi Installer 跑完。

![](/assets/esxi_installation_8.JPG)

8.進入Esxi常見的灰黃畫面，並且等待下方進度條跑完。

![](/assets/esxi_installation_9.JPG)

9.點選Enter繼續安裝流程。

![](/assets/esxi_installation_10.JPG)

10.點選F11同意並繼續安裝流程。

![](/assets/esxi_installation_11.JPG)

11.接下來會掃描該伺服器主機的硬體設備（若無法支援會在這邊掃描不到）。

![](/assets/esxi_installation_12.JPG)

12.選擇要安裝Esxi系統的硬碟（若這邊沒有顯示，應該就是沒有支援Esxi系統了）。

![](/assets/esxi_installation_13.JPG)

13.接下來他會掃描裝置內容。

![](/assets/esxi_installation_14.JPG)

14.如果此硬碟空間沒有清空，他會詢問是否要複寫資料，點選Enter同意複寫。

![](/assets/esxi_installation_15.JPG)

15.選擇Keyboard Layout 語言（這邊選擇US Default）。

![](/assets/esxi_installation_16.JPG)

16.輸入root的密碼（之後登入Esxi系統或者使用WEB遠端操控都要使用此密碼，請將密碼記好）。

![](/assets/esxi_installation_17.JPG)

17.會再掃描一次安裝資訊。

![](/assets/esxi_installation_18.JPG)

18.確認安裝的硬碟資訊是否正確。

![](/assets/esxi_installation_19.JPG)

19.開始安裝Esxi系統。

![](/assets/esxi_installation_20.JPG)

20.安裝完成，點選Enter來Reboot系統。

![](/assets/esxi_installation_21.JPG)

21.重新Reboot之後會進入Esxi的灰黃畫面，則為安裝成功。

![](/assets/esxi_installation_22.JPG)
