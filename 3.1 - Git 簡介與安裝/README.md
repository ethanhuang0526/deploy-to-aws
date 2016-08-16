# 3.1 Git 簡介與安裝

### Git 簡介

Git 創立於 Linux 之父，Linux Torvalds，因為當時 BitKeeper 取消了對 Linux 社群的授權，再加上當時沒有好用的版本控制系統，促使了 Linux Torvalds 親自動手開發了 Git。

### 集中式版本控制系統
所有的版本控制操作，必須仰賴一台中央版本控制系統伺服器來執行，當中央伺服器崩潰或是無法正常運作，將導致成員無法進行版本控制。

### 分散式版本控制系統
每一個成員都完整的備份了版本控制的資料，不需要仰賴中央伺服器，所以處理的速度較 集中式版本控制系統快，也可以在離線的狀態下進行本地端的版本控制，也可以與其他成員之間進行版本控制，也因為本機端有完整的備份，當中央伺服器損壞時，也能夠再一次重新提交。


### Git 官方網站
 [git-scm](https://git-scm.com) 提供了不同作業系統的安裝檔案，檔案下載完成後，只需依照預設的選項，就可以完成 Git 的安裝。
 
### 為什麼要使用 Git ?
如果有想要參與、開發開源專案，大部分都會使用 Github 雲端服務當作專案的儲存，而現今也越來越多企業選擇使用 Git 當作版本控制系統，如果你學會使用了 Git，將會大大提身自己的競爭能力。

### ubuntu 安裝 Git
~~~
sudo apt-get install git
~~~


### 查看 Git 版本
~~~
git --version
~~~

### 安裝最新版本的 Git (ubuntu)
~~~
// 加入 Git 來源包
sudo add-apt-repository ppa:git-core/ppa

// 更新系統來源清單
sudo apt-get update

// 安裝最新版的 Git
sudo apt-get install git
~~~