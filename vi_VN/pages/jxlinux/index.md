# Chuyên mục JX Linux

🍀 [Hội quán võ lâm](https://fb.com/groups/volamquan), 17/11/2023
💡 **Tác giả**: [Vinh TtN](https://www.facebook.com/nghiemtucdeptrai/)
✍️ **Soạn giả**: [Huy Nguyen](https://fb.com/groups/volamquan)

> Tags: #resources #installation #guidance #1click #jx80 #jx82 #jxoffline #vltk1 #huongdan #centosOnly #vmware #game_y

[🏠](https://hackmd.io/@eurofun/home) > [Kỳ trân dị bảo](../index.md)



## 🏆 Nội dung

Chào AE.

Xin phép cho mình post 1 bài cập nhật riêng về app quanlyserver nữa vì bài chính đã quá dài. (Mình hứa từ đây tới năm sau hạn chế post lại.)
Sau sự tiếp đón nồng nhiệt từ AE về bộ cài offline. Có 1 vấn đề là cái game server mình share kèm theo làm demo bị ai đó xóa các vật phẩm trong Kỳ Trân Cát

Nhưng không lẽ mình sửa xong phải up lại toàn bộ rồi AE phải down lại từ đầu? Cái khó ló cái khôn, app quanlyserver đã được nâng cấp lên phiên bản 1.1 để giải quyết vấn đề này và có thể mở ra nhiều thứ khác.


#### 1. APP QUANLYSERVER PHIÊN BẢN MỚI 1.1


Tính năng mới của nó là **Cập nhật qua GitHub** (tương tự như autoupdate của VNG, nhưng mình để bạn update bằng tay)

Nó cho phép bạn update game (cả server lẫn client) chỉ qua 1 cú click chuột.

**Hoạt động với mọi GitHub**.

Điều này có nghĩa là ví dụ GitHub Hội Quán được cập nhật chẳng hạn; (mà bác Cao Minh Thành đang miệt mài cập nhật hàng ngày); thì AE chỉ cần mở app lên, điền địa chỉ GitHub hội quán vào, và -> xong. Bản game của AE đã cập nhật tới bản mới nhất trên repo của Hội Quán.

Một ví dụ khác là thì dụ mình ra mod Chiến Loạn hay Tống Kim phiên bản mới, thì AE chỉ cần click chuột cập nhật là xong. Không cần mò mẫm cài đặt, sửa lỗi, cập nhật WinSCP hay làm gì cả.


#### 2. SỬA LỖI KỲ TRÂN CÁT



Như đã nói, bản game của mình share trong bài kia bị lỗi thiếu vật phẩm trong Kỳ Trân Cát.

Cách sửa:
Mở QLSV 1.1 (nhớ bỏ trong thư mục game VLTK rồi hả mở để nó cập nhật game trong đó)
Điền đúng Server IP và chọn Cập nhật GS
Điền vào địa chỉ github của mình (hình đính kèm) là **vinh-ttn/server82v** đây là nơi mình sửa lỗi cho bản game đó.
Xong. Khởi động lại game và server của bạn, và KTC đã được sửa.

**Chú ý**: đây là github của mình để sửa lỗi KTC cho game server của mình đã share. Không hoạt động hay sửa lỗi KTC với các game server khác vì mỗi server mỗi mã nguồn khác nhau.
ae


#### 3. App Quản lý server
- App này phải bỏ chung thư mục với thư mục game VLTK khi sử dụng
- Chỉ dùng cho bộ server offline CentOS - xem thêm Hướng Dẫn - Võ Lâm 1click1VM
- Nếu MD5 của file app mà bạn đang sử dụng khác mã MD5 trong danh sách sau thì nó đã bị chỉnh sửa + thêm virus 

Để xem md5 của 1 file thì dùng web này
https://emn178.github.io/online-tools/md5_checksum.html


| Phiên bản | Ngày       | Thay đổi                                                     |
| --------- | ---------- | ------------------------------------------------------------ |
| 1.0.0     | 14-11-2023 | Chức năng: <br />- Tắt + mở server <br />- Đồng bộ các file configs giữa 2 server <br /><br />MD5: 0dfbe05225abda963784eab23589b756 |
| 1.1.0     | 17-11-2023 | Thêm: <br />- Chức năng download server/game từ nguồn GitHub <br />- Thay đổi giao diện cho gọn gàng <br />-Thêm tùy chỉnh nâng cáo để khởi động từng phần nếu muốn  <br /><br />MD5:  6539975033e1d0c40b12da5a301e0fb7 |
| 1.1.1     | 17-11-2023 | Thêm: <br />- Tự động xóa các logs và file core dump trên server để giảm dung lượng <br />Sửa <br />- Lỗi giao diện cho tùy chỉnh nâng cao  <br /><br />MD5: 954cf7505a4778d9cdea38159a938780 |
