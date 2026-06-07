Xeffy bot - Hana

Link: https://t.me/Xeffy_Bot?start=ref_6292310143

Chức năng:
- Ref
- Connect x (bypass x)
- Checkin
- Task + daily quiz (auto đáp án đúng)
- Xuất data số điểm

- HDSD:

+ data.txt: query
+ proxy.txt : định dạng ip:port:user:pass
+ xtoken: token của acc x (định dạng auth token|ct0 , ví dụ 53e530f...|2b9bf85)
+ file config: cấu hình số luồng và chức năng

Lưu ý:
- Nếu connect x: trong file xtoken để đúng định dạng, mỗi acc x 1 dòng.
Sau khi connect thành công/token die  => auto xoá và lưu token đã connect sang file x_connected.txt (token die thì chỉ xoá)
- Nếu bypass x:  tắt chức năng connect x trong file config đi
=> nó sẽ login, checkin, làm task k liên quan đến x, quiz...
