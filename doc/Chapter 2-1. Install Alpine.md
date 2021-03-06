# Chapter 2-1. Install Alpine

* * *
## 目錄

-   [登入帳號](#login)
-   [安裝系統](#setup)
-   [設定鍵盤](#keyboard)
-   [設定電腦名稱](#localhost)
-   [設定網路卡](#network)
-   [設定 root 密碼](#passwd)
-   [設定時區](#time)
-   [設定 proxy 與 ntp](#proxy)
-   [設定 alpine repository 與 ssh server ](#url)
-   [安裝 alpine 到硬碟中](#disk)
-   [重新開機](#reboot)

* * *


<h3 id="login">登入帳號</h3>

* Alpine 開機後，預設的登入帳號為 `root` ，而且沒有密碼。

![1. login](https://i.imgur.com/PNkRzxc.png)

輸入： `root` <br />

---
<h3 id="setup">安裝系統</h3>

* 使用 Alpine 預設命令來安裝系統。

![2. setup](https://i.imgur.com/s1jNk6E.png)

輸入： `setup-alpine` <br />

* 安裝過程使用問答方式，若回答想要反悔，只能透過 `Ctrl + C` 重來。
* 若問答看到 `[abc]` ，`abc` 則代表預設的答案。<br />

---
<h3 id="keyboard">設定鍵盤</h3>

![3. keyboard](https://i.imgur.com/wZwKQlk.png)

輸入1： `tw` <br />

輸入2： `tw` <br />

* `tw` 表示 `taiwan` 。

---
<h3 id="localhost">設定電腦名稱</h3>

![4. localhost](https://i.imgur.com/POFSZwC.png)

* 此為範例。

輸入： `test` <br />

---
<h3 id="network">設定網路卡</h3>

![5. network](https://i.imgur.com/t9LS2d7.png)

* 使用預設 `enter鍵` * 3 <br />

---
<h3 id="passwd">設定 root 密碼</h3>

![6. passwd](https://i.imgur.com/lNVzYm0.png)

* 此為範例。

輸入1： `root` <br />

輸入2： `root` <br />

---
<h3 id="time">設定時區</h3>

![7. time](https://i.imgur.com/Tc52Xqr.png)

* 依據所在地及其首都。開頭字母必須為大寫！ 

輸入1： `Asia` <br />

輸入2： `Taipei` <br />

---
<h3 id="proxy">設定 proxy 與 ntp </h3>

![8. proxy](https://i.imgur.com/sos8Eaz.png)

* 使用預設 `enter鍵` * 2 <br />

---
<h3 id="url">設定 alpine repository 與 ssh server</h3>

* 注意，若網路沒有通， repository 會找不到

![9. url](https://i.imgur.com/tLiL4hl.png)


輸入1： `37` <br />

輸入2： 使用預設 `enter鍵` <br />

* Alpine 3.13.0 版本後使用以下：

![9-1. url](https://i.imgur.com/4fQiDfC.png)

#### **輸入1：** **`6`** 

### **(此圖未更新以上方文字為主！)**


輸入2： 使用預設 `enter鍵` <br />

- 前面 1～8 為 Alpine 官網提供下載點

---
<h3 id="disk">安裝 alpine 到硬碟中</h3>

![a. disk](https://i.imgur.com/CopvYoC.png)

* 查看上一行 disk 有哪些？ 選擇要安裝的硬碟。

* 此為範例。

輸入1： `sda` 

輸入2： `sys`

輸入3： `y`    (此問確認安裝？)

---
<h3 id="reboot">重新開機</h3>

![b. reboot](https://i.imgur.com/EkA82St.png)

* 安裝至硬碟後須重新開機，並退出 iso .

輸入： `reboot` 

---
[返回至 - 目錄](https://github.com/xuan103/Alpine_2021)

[下一頁 - Chapter 2-2. Start Alpine](https://github.com/xuan103/Alpine_2021/blob/main/Documents/Chapter%202-2.%20Start%20Alpine.md)