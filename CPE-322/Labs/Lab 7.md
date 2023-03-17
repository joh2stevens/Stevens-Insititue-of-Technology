# Lab 7A - ThingSpeak
* Create new channel cpu_loop wiht field 1 cpu_pc and field2 mem_avail_mb

  ![Create new Channel](https://user-images.githubusercontent.com/98679243/168070860-ec22202a-2738-466b-872e-99066c15aef4.png)

* Install psutil

  ![Install psutil](https://user-images.githubusercontent.com/98679243/168070906-c5a76457-f444-46f6-9a91-19f21fb5a89a.png)

* cat thingspeak_cpu_loop.py

  ![thingspeak_cpu_loop](https://user-images.githubusercontent.com/98679243/168071000-e7703e46-77b5-4fa4-b538-289aaacdec94.png)

* cat thingspeak_feed.py

  ![thingspeak_feed](https://user-images.githubusercontent.com/98679243/168071037-963e2120-5066-4f38-aed2-55740c6deaff.png)

* python3 thingspeak_feed.py

  ![python3_thingspeak_feed](https://user-images.githubusercontent.com/98679243/168071084-a13c969d-bd10-450b-955f-42cc841a3b07.png)

  ![cpu_loop](https://user-images.githubusercontent.com/98679243/168071205-b29a21d0-3209-4aaf-aa00-f21e83dfb59e.png)


# Lab 7B - Google Sheets
* Install gspread and oauth2client

  ![Install gspread and oauth2client](https://user-images.githubusercontent.com/98679243/168071314-e5204848-e8c6-4fc1-baa6-f5803fc37652.png)

* Copy system_infor.py and rpi_spreadsheet.py to ~/demo, and Move JSON key file 

  ![copy files](https://user-images.githubusercontent.com/98679243/168071399-421509b6-0ec6-4cae-bd63-c120aa15fa9c.png)

* Edit rpi_spreadsheet.py

  ![rpi_spreadsheet edit](https://user-images.githubusercontent.com/98679243/168071447-f91fa7cb-40de-4015-8067-58227fc61b14.png)

* Run rpi_spreadsheet.py

  ![python3 rpi_spreadsheet](https://user-images.githubusercontent.com/98679243/168071506-9ec868a9-0e69-4a17-a183-78453799a6a1.png)

  ![google sheet](https://user-images.githubusercontent.com/98679243/168071535-823991b2-1d19-416c-a032-14c2f34f5cb7.png)

