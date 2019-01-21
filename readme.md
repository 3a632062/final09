<p align="center"><img src="https://i.imgur.com/USDHjHb.png"></p>

## 系統的作用

線上訂位、候位系統

- 讓使用者透過此系統的簡單操作就可提前訂位，不必再將時間浪費在等待位子上
- 讓使用者透過此系統的簡單操作就可進行線上候位，不必到現場就能候位，節省等待的時間
- 讓使用者隨時掌握候位的最新狀況
- 讓管理者一起管控所有顧客的訂位、候位資料


## 系統的主要功能
前台
- 線上訂位[3A532083 劉宜樺](https://github.com/3A532083)
- 查詢訂位[3A532083 劉宜樺](https://github.com/3A532083)
- 刪除訂位[3A532083 劉宜樺](https://github.com/3A532083)
- 線上候位[3A532085 江珮妤](https://github.com/3A532085)
- 查詢候位[3A532085 江珮妤](https://github.com/3A532085)
- 刪除候位[3A532085 江珮妤](https://github.com/3A532085)

後台
- 查看預約組數和候位組數[3A532085 江珮妤](https://github.com/3A532085)
- 更改訂位、候位狀態[3A532085 江珮妤](https://github.com/3A532085)
- 店家叫號[3A532085 江珮妤](https://github.com/3A532085)
- 設定等候時間[3A532085 江珮妤](https://github.com/3A532085)

## 初始專案與DB負責的同學

- 初始專案 [3A532085 江珮妤](https://github.com/3A532085)
- 資料庫及資料表建立 [3A532085 江珮妤](https://github.com/3A532085)

## 額外使用的套件或樣板 

前台樣板-[Clean Blog](https://startbootstrap.com/template-overviews/clean-blog/)
- 使畫面看起來不單調，讓使用者喜愛此系統

後台樣板-[Side Bar](https://startbootstrap.com/template-overviews/simple-sidebar/)
- 為製做簡易操作介面，讓管理者輕鬆使用

## 系統復原步驟

1. > 複製[https://github.com/WISD-2018/final09.git](https://github.com/WISD-2018/final09.git)本系統在GitHub的專案，打開Source tree，點選clone後
2. > 打開cmder，切換至專案所在資料夾，cd final09
3. > 在cmder輸入以下命令，以復原此系統：
- composer install
- composer run‐script post‐root‐package‐install
- composer run‐script post‐create‐project‐cmd
4. > 開啟UwAmp，點選PHPMyAdmin，進入MySQL，建立新資料庫，名稱為final09，將final09.sql匯入(wagon\uwamp\www\final09\database\final09.sql)
5. > 在UwAmp下，點選Apache config，選擇port 8000 ，並在Document Root 輸入{DOCUMENTPATH}/final09/public


## 系統使用帳號

前台-使用者<br>
- 帳號:123@gmail.com
- 密碼:123456

後台-管理者
- 帳號:root@gmail.com
- 密碼:123456

## 系統開發人員

- **[3A532083 劉宜樺](https://github.com/3A532083)**
- **[3A532085 江珮妤](https://github.com/3A532085)**
