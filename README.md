# TWCC FAQs

Got a question? We're here to help!

Link to our FAQ page: 
[中文](https://man.twcc.ai/@twccdocs/faq-zh) | [English](https://man.twcc.ai/@twccdocs/faq-en)

## TOC

## [TWCC CLI](TWCC%20CLI)
### [部屬環境](TWCC%20CLI/部屬環境.md) (2) 
- Q1. 請問 TWCC-CLI 怎麼安裝？
- Q2. 請問 TWCC-CLI 支援的環境是？
### [雲端物件儲存](TWCC%20CLI/雲端物件儲存.md) (1) 
- Q1. 為何我使用 TWCC-CLI 上傳、下載大量檔案時無法成功？
## [儲存服務](儲存服務)
### [區塊儲存服務(BSS)](儲存服務/區塊儲存服務(BSS).md) (1) 
- Q1. 為何之前保留的 HDD 無法成功掛載到新的虛擬運算服務個體上？
### [雲端物件儲存服務(COS)](儲存服務/雲端物件儲存服務(COS).md) (2) 
- Q1. 請問在舊計畫的雲端物件儲存資料，可以直接沿用到新計畫內嗎？
- Q2. 為什麼我在 TWCC 網頁下載檔案失敗了？
### [高速儲存服務(HFS)](儲存服務/高速儲存服務(HFS).md) (7) 
- Q1. 高速儲存服務空間已滿，將部分資料刪除，為何容量還是一樣沒變化？
- Q2. 我使用 SFTP 的方式連入 xdata1.twcc.ai 資料傳輸節點，為何無法登入？
- Q3. 如何將檔案上傳到高速儲存服務？
- Q4. 如何增購高速儲存服務空間？
- Q5. 請問高速儲存服務的 IP 位置為何？
- Q6. 高速儲存服務畫面顯示快用滿，要如何知道是哪些檔案佔據儲存空間？
- Q7. 增購高速儲存服務空間後多久生效？
## [平台與帳號計畫](平台與帳號計畫)
### [使用者網站](平台與帳號計畫/使用者網站.md) (8) 
- Q1. TWCC 支援哪些瀏覽器？
- Q2. 為何登入後畫面空白？
- Q3. 登入密碼連續輸入錯誤會有甚麼情況？
- Q4. 租戶管理員與一般租戶使用者身分，在使用 TWCC 各服務上有什麼區別？
- Q5. 容器運算 (CCS)、虛擬運算 (VCS) 及高速運算 (HPC) 有什麼不同？
- Q6. 如何查詢計畫的 GPU 使用上限？
- Q7. 為什麼創建資源時出現錯誤訊息:[i-service] no quota to request resource.user？
- Q8. 請問SSH連線至TWCC上的資源CCS、VCS和HPC有那些可使用的的開源軟體?
## [網路與安全服務](網路與安全服務)
### [基礎虛擬防火牆](網路與安全服務/基礎虛擬防火牆.md) (1) 
- Q1. 為什麼防火牆裡面的規則沒有作用？
### [虛擬網路](網路與安全服務/虛擬網路.md) (1) 
- Q1. 我在建虛擬運算服務的時候要選填虛擬網路才能建立，但我無法去建立虛擬網路？
## [運算服務](運算服務)
### [台灣杉二號(命令列介面)(TWNIA2)](運算服務/台灣杉二號(命令列介面)(TWNIA2).md) (10) 
- Q1. 是否可以在台灣衫二號上安裝 Rclone 軟體同步工具？
- Q2. 請問台灣杉二號的登入節點 IP 位置為何？
- Q3. 使用跨節點運算，節點是系統自動選取或需手動選取？
- Q4. 排程系統 Slurm 是什麼？
- Q5. 登入後發現 /home/$USER 沒什麼檔案是正常的嗎？
- Q6. 可以協助我安裝套件嗎？
- Q7. 為什麼我執行任務要索取多個 CPU 資源會發生錯誤？
- Q8. 計畫到期後儲存在台灣杉二號的檔案會刪除嗎？
- Q9. 台灣杉二號有支援 Nvidia 的 CUDA 運算架構嗎?
- Q10. 半年前登入過台灣杉二號 (命令列介面)，而最近想使用時卻無法成功登入?
### [容器運算服務(CCS)](運算服務/容器運算服務(CCS).md) (38) 
- Q1. 容器的 Port 範圍是什麼？
- Q2. 如何從容器轉移至台灣杉二號(命令列介面)進行訓練運算？
- Q3. 如何使用 8 張 GPU 以上的資源？
- Q4. 開發型容器 SSH 連線時顯示 Permission denied？
- Q5. 執行程式時發現 I/O 緩慢？
- Q6. 程式執行時效能不如預期？
- Q7. 程式執行時顯示 insufficient shared memory？
- Q8. 程式執行時顯示 bus error？
- Q9. 容器能建立幾次複本？
- Q10. 如何建立第二次複本？
- Q11. 如何暫停容器？
- Q12. 程式執行時發現比 local 端還慢？
- Q13. 程式執行時發生有些 library 無法載入 (Could not load dynamic library...)？
- Q14. 無法連線 Jupyter notebook 時如何處理？
- Q15. 為何切換成 root 無法存取自己的 /home 與 /work？
- Q16. 要如何分享 /home 與 /work 的資料給其他同計畫使用者？
- Q17. 為何 sudo  apt  update 產生 Unable  to  change  to  /home/wistron1/ -chdir  (13:  Permission  denied)？
- Q18. 如何設定自動化將容器內資料回傳 local 端？
- Q19. 以 Matlab 映像檔建立的容器為何無法存取 /home 及 /work？
- Q20. 在程式執行時，如何知道 GPU 使用情況？
- Q21. 目前容器支援多少種計算環境？
- Q22. 如何登入容器？
- Q23. 我可以建立一個容器給其他人用嗎？
- Q24. 怎麼使用超級電腦？
- Q25. 如何確認容器映像檔中包了什麼套件及其版本？
- Q26. 如何將檔案上傳至容器，或從容器下載？
- Q27. 為何我刪除容器後再重新建立容器，新容器內仍存在舊容器上的套件？
- Q28. 我要如何將容器還原至初始狀態？
- Q29. 如何切換成容器的 root 身份？
- Q30. 為何無法使用容器內的 GPU？
- Q31. 安裝套件時發生錯誤訊息 Permission denied 如何處理？
- Q32. 為何 Jupyter notebook 無法寫入檔案？
- Q33. 為何 Jupyter notebook 儲存檔案失敗？
- Q34. 如何開始使用容器？
- Q35. 如何知道容器配置的 GPU 數量？
- Q36. 建立容器時基本設定中，為何有共享記憶體？
- Q37. 能否將共享記憶體當硬碟空間使用？
- Q38. 在容器中如何安裝cudnn？
### [虛擬運算服務(VCS)](運算服務/虛擬運算服務(VCS).md) (19) 
- Q1. 虛擬運算的浮動 IP 範圍？
- Q1. 如何使虛擬運算個體進行自動快照？
- Q2. 如何將虛擬運算中資料定期備份至雲端物件儲存 (COS)？
- Q3. 虛擬運算服務是否支援 SMTP？
- Q4. 虛擬運算服務個體是否可直接掛載雲端物件儲存 (COS)？
- Q5. 請問我要如何知道我們開的虛擬運算服務個體網路流量狀態？
- Q6. 虛擬運算個體建立後為何無法連線網路？
- Q7. 如果把超過 100GB 的映像檔輸入虛擬運算服務個體，會有什麼影響？
- Q8. 對虛擬運算個體安裝套件或進行更新，出現`E: Could not get lock /var/lib/apt/lists/lock`該如何解決？
- Q9. 如何讓 Auto scaling 擴展出的個體，符合我需求的環境？
- Q10. 欲使用虛擬運算個體架設服務，卻無法連入？
- Q11. 快照建立的時間需要多久？
- Q12. 如何節省快照製作的時間？
- Q13. 建立虛擬運算個體失敗該怎麼處理？
- Q14. 用快照所建立的虛擬運算個體無法連線進入作業該怎麼處理？
- Q15. 忘記 Windows 虛擬運算個體登入密碼該怎麼處理？
- Q16. 遺失 Linux 虛擬運算個體的金鑰該怎麼處理？
- Q17. SSH 連線個體速度有點慢該如何解決？
- Q18. 已經外掛區塊儲存到指定的虛擬運算個體，卻無法在虛擬運算個體中找到儲存空間該如何解決?
