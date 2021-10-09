---
title: 台灣蘋果二號同學會 Apple ][ Taiwan
image: https://imgur.com/gallery/z9wh39H
description: 關於 Apple ][ 的資料整理, 參考臉書社團 "台灣 Apple II 同學會" https://www.facebook.com/groups/taiwanappleii
---

# 台灣蘋果二號同學會 Apple ][ Taiwan

- [Welcome](/@AppleIITaiwan/AppleIITaiwan/) 歡迎大家一起來豐富 Apple II 的內容, 建構更容易跨入現代電子基礎的 - 計算機結構 - 的學習地圖.

[初心](/@AppleIITaiwan/AppleIITaiwan/)
---
2021 年夏, 有幾件事情幾乎同時發生都跟 Apple ][ 相關, 激起Apple ][ 尋根之旅
1. 找到大學時翻譯的 "Apple ][ 檢修手冊" ![](https://i.imgur.com/QUPXmjM.jpg =100x)
2. 臉友 (新竹 Andes 員工) 送給我一張 FPGA 卡, 我把它來模擬 6502 CPU, 運作順利, 至於是不是能組成 Apple ][ 功能還待確認.
3. 在網路上搜尋關於 Apple ][ 的文章還持續有人更新, 不管是硬體還是軟體, 都可以找到完整的資料, 包括: 線路圖, 線路圖詳細說明, ROM listing, Apple ][ 模擬器網站, 以及 [臉書 Apple II Enthusiasts 粉絲團](https://www.facebook.com/groups/5251478676) , 甚至還有 Apple ][ 原廠機器買賣, 一度看到 ebay 上有一台只能開機, 但無法保證運行, 衝動下去搶標, [標到 250 鎂, 結標前都還是最高價](https://www.ebay.com.hk/itm/174904732324?mkevt=1&mkpid=0&emsid=e11002.m43.l2649&mkcid=7&ch=osgood&euid=114880a220ee42c79abb9233cadd1cb9&bu=45059694189&exe=0&ext=0&logid=mdbreftime%3D1630550057598%26es%3D201%26ec%3D1&osub=-1%7E1&crd=20210901194839&segname=11002&sojTags=ch%3Dch%2Cbu%3Dbu%2Cmdbreftime%3Dmdbreftime%2Ces%3Des%2Cec%3Dec%2Cexe%3Dexe%2Cext%3Dext%2Cexe%3Dexe%2Cext%3Dext%2Cosub%3Dosub%2Ccrd%3Dcrd%2Csegname%3Dsegname%2Cchnl%3Dmkcid), (運費還不便宜),  但在最後一秒, 被人劫標, 遺憾. 其他的美國賣家都不願意運到台灣, 最後, [找到愛爾蘭的賣家](https://www.ebay.ie/itm/Apple-II-Europlus-Job-Lot-/124929928796?mkcid=16&mkevt=1&_trksid=p2349624.m2548.l6249&mkrid=5282-175127-2357-0). 
4. 發現 Apple ][ 的硬體設計真的是經典, 尤其是==精簡的 video 線路==, ==Applesoft 的 BASIC 也很容易入門==. 拿來當電子學的入門, 會不會比 Arduino 來的簡單? 應該是"不會", 但是, 可以當作 Arduino 或 Micro:bit 的補充教材, 讓不懂電子的朋友, 可以從最基礎的 Apple ][ 6502 CPU 經典線路產生對 CPU architecture 的興趣, 再進階到 ARM / RISC-V CPU; 從 BASIC 進階到 C 語言, Linux OS 等.


所以, 成立這成立臉書社團["台灣蘋果二號 Apple II 同學會" 臉書粉絲團](https://www.facebook.com/groups/taiwanappleii)及此 hackmd 文章, 希望能引發大家對 Apple ][ 的興趣, 也是==對 Steve Jobs / Steve Wozniak 的致敬==, 更==適逢 2021/10/5 是 Steve Jobs 逝世十周年紀念==. 透過這經典的設計, 讓大家體會電子電路設計之美, 投入電子行業 (二度就業?), 再度創造台灣奇蹟.

[Apple II 歷史](/@AppleIITaiwan/AppleIIHistory)
---

[Apple II 技術文件](/@AppleIITaiwan/AppleIIdocuments)
---

[Apple II 模擬器](/@AppleIITaiwan/AppleIIemulator)
---
- [FPGA 模擬 Apple II](/@AppleIITaiwan/FPGA4AppleII)
- [Ben Eater 的 Youtube - 6502 的 Hello World](/@AppleIITaiwan/BenEater)


[計算機結構學習地圖](/@AppleIITaiwan/LearningMaps)
---



<a id="reference"></a>

[參考資料](/@AppleIITaiwan/AppleIITaiwan#reference)
---
**Apple II 及 6502 CPU 相關資源**
1. [Apple Documents - Programming - BASIC](https://www.apple.asimov.net/documentation/programming/basic/) : 不只是 BASIC, 裡面有完整的 Apple 相關資料, 包括 source code, 硬體線路圖, 各種 CPU 及各種語言如 PASCAL、FORTRAN 等, ==可以說是 Apple 的藏寶圖==   
2. [github - Eiroca - Awesome List of Apple II resources 豐富的 Apple II 資源列表](https://github.com/eiroca/awesome-list/blob/master/Apple2.md)   
3. [AppleLogic.org](http://www.applelogic.org/Processors.html): 提供多個模擬 6502 (及 Z80) 的 FPGA 程式碼, 不過, 似乎很久沒有維護了, 許多連結都是 404.    
4. [Applesauce project](https://applesaucefdc.com/woz/): 也介紹支援 WOZ 的 Apple II 軟體模擬器及磁碟模擬卡
5. [github - Apple II System Software Source Code](https://github.com/cmosher01/Apple-II-Source)   

**Apple II 軟體**
1. [Apple II 軟體 .DSK 下載](https://www.planetemu.net/machine/apple-ii)   
2. [Apple II 模擬器 軟體 - FTP](https://ftp.apple.asimov.net/)
3. [microM8 網站 - 內含許多應用程式](https://paleotronic.com/software/microm8/)

**Apple II 硬體模擬 - 用 SD 卡模擬軟碟或硬碟**  
1. [SD 卡模擬 Apple II / Mac / Lisa 軟碟/硬碟 - 附螢幕](https://www.bigmessowires.com/floppy-emu/): 
2. [SDISK II - DISK II emulator for APPLE II ](https://web.archive.org/web/20150201051540/http://tulip-house.ddo.jp/digital/SDISK2/english.html) : 包含磁碟格式轉換程式  
   * [eBay - 沒有庫存](https://www.ebay.com/itm/143928360065?mkevt=1&mkcid=1&mkrid=711-53200-19255-0&campid=5338722076&toolid=10001)
   * [內容說明](https://picclick.com/Floppy-disc-drive-Emulator-for-Apple-ii-iie-143928360065.html)
3. [硬體轉接卡 - 模擬磁碟噪音](https://www.hackster.io/news/this-device-makes-your-apple-ii-floppy-emulator-click-and-clack-like-the-real-thing-d8cb1bda1ed1)

**FPGA 模擬 Apple II**
1. [Apple2fpga: Reconstructing an Apple II+ on an FPGA by Stephen A. Edwards / Columbia University](http://www1.cs.columbia.edu/~sedwards/apple2fpga/)
2. [Embedding a 6502 in an FPGA - 似乎未完成](https://embeddedmicro.weebly.com/embedded-6502-on-fpga.html)

[彩蛋 2021/10/5](https://twitter.com/tim_cook/status/1445358107157221379?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Etweet)
