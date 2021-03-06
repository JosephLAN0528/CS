# CS
計算機概論
Linux系統的教學

1.系統的理解
* /：根目錄
* /root：該目錄為系統管理員
* /bin：存放著經常使用的命令
* /boot：系統啟動時必須讀取的檔案
* /home：家目錄
* /etc：放置與系統設定、管理相關的檔案
* /user：使用者的應用程式和檔案存放位置
* /media：為光碟、軟碟片、隨身碟與其他分割區的自動掛載點
* /tmp：全部使用者暫時放置檔案的目錄
* /var：存放變動的資料或暫存檔

2.絕對路徑與相對路徑表達法
.：代表此層目錄
..：代表上一層目錄
- ：代表前一個工作目錄
- ~  ：代表『目前使用者身分』

3.令的含義
cd 變換目錄
pwd顯示目前的目錄的所在位置
ls顯示目錄下的所有檔案
touch建立檔案
cp複製
cat查看檔案內容
vi編輯檔案
mkdir建立一個新目錄
mkdir -p同時建立多個目錄
rmdir刪除一個裡面是空的空目錄
rm刪除檔案
rm -r強制刪除
mv移動，重新命名

4.更改使用者權限
chmod＋ugo
u：檔案  擁有者g：與該檔案的  擁有者同一個群體者o：其他以  外的人a：三者皆是

5.解壓縮方法
xz、tar.gz、gzip

6.操作
Ｑ：印出new_shake.txt 第11~20行的內容？
Ａ：『head -n 20 | tail -n 10』

7.資料傳輸背景
| Port          | Service  | Explaination  |
| ----          | ----        |---- |
| 22             | ssh        |一種加密的網路傳輸協定 ，可在不 安全的網路中   及公安全  的傳輸  環境|
| 23             | telnet    |一種很傳 統的連線程式，可用來診斷各 種伺服 器與網路連線問題|
| 80             | http       |超文本傳輸  協定|
| 20/21        | ftp         |一個傳 遞客戶端與伺服器之間的 命令(21，命令通訊埠);另一個傳 遞資料(20，資料通訊埠)|
| 443          | https     |超級文字傳輸 安全協定|
| 25             | smtp     |簡單 郵件傳輸 協定，是一個在網際網路上傳輸電子郵件的 標準|
| 53             | DNS      |網域名稱系統  ，將 域名和IP位址相互對應 的一個分散式資料庫，能夠  使人更方便的  存取 網際網路22|

Tcp/ip 與Port的作業
