# ChatBot-ver-2.0
﻿Hướng dẫn Setup
 
Bước 1 : import data kma.sql vào data

Bước 2 : cấu hình config => điền thông tin cơ sở dữ liệu , thông tin ID bot , Token ...

Bước 3 : cấu hình chatfuel
      
      - https://domain.com/update.php?ID={{messenger user id}}&gt={{gender}} => Setup ở [Welcome messenger] , [Default answer] , [thamgia] để update thông tin người dùng lên data
	  
      - https://domain.com/thamgia.php?ID={{messenger user id}}&gt={{gender}} => Setup ở block [thamgia] để người sử dụng được đưa vào hàng chờ
	   
      - https://domain.com/thoat.php?ID={{messenger user id}} => Setup ở block [thoat] dùng để thoát hàng chờ , thoát chát.
      - https://domain.com/send_chat.php?id={{messenger user id}}&noidung={{noidung}} => Setup để gửi tin nhắn
	 
Các bạn chú ý nên đặt từ tiếng anh để tránh sự hiểu từ ngữ gần đúng của AI . Thanks
