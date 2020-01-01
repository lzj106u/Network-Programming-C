Execute on ubuntu 16.04. 

To execute the HW:
    1. key "make"
    2. key "sudo ./serfork"
    3. open your browser and go to url "0.0.0.0"
    4. select a file
    5. recieve the file in folder "upload".


HW Request:
請實作一個小型的web server，具有底下功能：
1. 可從一般的瀏覽器，例如Chrome，取得所設計之web server上的網頁。
2. 網頁中需至少有一張圖片，並正確在瀏覽器上顯示。
3. 可以從瀏覽器上上傳檔案，並正確儲存至web server上。

技術細節：
1. 此web server必須為concurrent server。
2. 必須不可留下zombie process。