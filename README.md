# 各種有關 docker 的基礎練習架構

## 使用說明
+ 『docker_compose_practise』資料夾：為利用 docker compose 以 YAML檔 建立容器和運行環境，可一併建立『網路』、『卷宗』  
   （以 WordPress 為主軸建立，同時學到怎麼建立 MySQL）
   
 + 『file_create_image』資料夾：為以 Dockerfile 檔案，再以 build 建立 image    
  （以 httpd 做一個 image）

 + 『kubernetes_practise』資料夾：為編寫定義檔來建立 Pod
       
   1.『pod1.yml』檔案：實際應用上很少會單獨編寫『Pod』項目，通常會內涵於 『Deployment』 裡，但學習上可以先看怎麼寫『Pod』，再來寫 『Deployment』 會比較好     
  
   2.『deployment1.yml』檔案：用來管理附加特定標籤的『Pod』，裡頭包含 並列編寫大項目 => 輸入元資料 => 輸入規格內容
     
   3.『Service1.yml』檔案：編寫完 deployment1.yml 接著是編寫 Service1.yml，他們通常是一併使用的，『 Service』用來管理『Pod』的通訊訪問
    
## 環境
為 linux/amd64，可自行更改決定環境
