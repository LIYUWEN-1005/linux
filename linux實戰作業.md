# 完成底下linux指令的測試報告
```
1.cd 回到目錄
  cd .. 為回到上一層目錄   .. 為上一層
2.pwd 顯示目前所在位置

root@kali:/# cd /bin/
root@kali:/bin# pwd
/bin
root@kali:/bin# cd ..
root@kali:/# pwd
/
```
```
3.cat 檔案名稱
  檢視檔案內容
  
  root@kali:~# cat yersinia.log 
 # yersinia v0.8.2 started in kali on Mon Jul 22 10:08:05 2019

Network Interface eth0

 eth0 iflinkname EN10MB
 eth0 iflinkdesc Ethernet
 eth0 MAC = 0800.2789.03db
Network Interface lo
```
```
ls
```
```
top
```
```
ps
```
```
ping
```

### 目錄與路徑
```
相對路徑與絕對路徑
目錄的相關操作： cd, pwd, mkdir, rmdir
```

### 檔案與目錄管理
```
檔案與目錄的檢視： ls
複製、刪除與移動： cp, rm, mv
取得路徑的檔案名稱與目錄名稱
```
### 檔案內容查閱
```
直接檢視檔案內容： cat, tac, nl
可翻頁檢視： more, less
資料擷取： head, tail
非純文字檔： od
修改檔案時間與建置新檔： touch
```

檔案與目錄的預設權限與隱藏權限
```
檔案預設權限：umask
檔案隱藏屬性： chattr, lsattr
檔案特殊權限：SUID, SGID, SBIT, 權限設定
觀察檔案類型：file
```
### 指令與檔案的搜尋
```
指令檔名的搜尋：which
檔案檔名的搜尋：whereis, locate / updatedb, find
```
