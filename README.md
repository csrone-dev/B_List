# B_List
# 使用教學
1. 先到Google Cloud Platform申請一個帳號
<img width="2559" height="1496" alt="image" src="https://github.com/user-attachments/assets/f9f33742-4e66-4ba4-a857-492c67d69957" />
2. 在搜尋欄輸入"Cloud Vision API"並啟用<br>
3. 點開左側的"API和服務"->"已啟用的API和服務"->"憑證"->"建立憑證"，建立一個服務帳戶的憑證，並將權限設為擁有者<br>
4. 點進剛剛創好的帳號並點開"金鑰"->"新增鍵"->"新增新的金鑰"->"json"來建立憑證
<img width="2559" height="1494" alt="image" src="https://github.com/user-attachments/assets/ebf278d1-9ac3-4ee9-b266-fbfde903658d" />
5. 找出剛剛下載的憑證，並將它改名為"api_key"，接下來將github上的code下載下來<br>
6. 把api_key放到跟Readme同一層的位置，然後在終端執行pip install -r requirements.txt<br>
7. 執行BList_crawler.py即可使用，使用前要把報告書放在test_reports資料夾，在選擇報告書位置時直接選擇該資料夾即可，輸出的csv會放在csv_file資料夾<br>
<img width="588" height="255" alt="image" src="https://github.com/user-attachments/assets/02bca473-835c-41d0-b38a-ae932a848132" />



