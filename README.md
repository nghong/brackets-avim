#Brackets-AVIM
Extension này sẽ tích hợp bộ gõ AVIM vào Brackets, hỗ trợ bạn gõ được Tiếng Việt mà không cần đến bộ gõ bên ngoài. Quan trọng nhất là, trên Linux, bộ gõ Tiếng Việt AVIM giúp bạn không gặp lỗi khi sử dụng chức năng Autocomplete như khi dùng các bộ gõ trên máy.

**Lưu ý**: *Tắt bộ gõ Tiếng Việt trên máy (ví dụ: ibus-unikey) khi dùng extension này.*

##Cài đặt

###Cách 1
1. Tải **Brackets-AVIM** về máy https://github.com/baivong/brackets-avim/archive/master.zip
2. Giải nén và chép vào thư mục **extensions / user** của Brackets (**Help > Show Extensions Folder**).
3. Khởi chạy lại Brackets (**F5**).

###Cách 2
1. Mở trình quản lý Extension (**File > Extension Manager...**).
2. Tìm Extension *Bộ gõ Tiếng Việt AVIM* với từ khoá ```AVIM```
3. **Install** và khởi chạy lại Brackets (**F5**).

##Hướng dẫn
Bật / tắt bằng cách chọn trên menu **Edit > Bộ gõ AVIM**.

Chọn kiểu gõ **Debug > Open Preferences File** tìm thông số `baivong.avim.method` và thay giá trị tương ứng với kiểu gõ bạn cần:

* **0** = AUTO
* **1** = TELEX
* **2** = VNI
* **3** = VIQR
* **4** = VIQR*

Ví dụ, chọn kiểu gõ **VNI** thì dùng `"baivong.avim.method": 2`

Lưu lại và khởi chạy lại Brackets (**F5**).

##Bộ gõ AVIM
**Tác giả**: Đặng Trần Hiếu <lt2hieu2004@users.sf.net>
**Trang chủ**: http://rhos.sourceforge.net/
**Phiên bản**: 28-07-2008