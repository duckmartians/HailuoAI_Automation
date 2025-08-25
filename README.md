# 🚀 Hailuo Automation Tool v5.0

Chào mừng bạn đến với **Hailuo Automation Tool**\! Đây là công cụ giúp tự động hóa hoàn toàn quá trình tạo video từ ảnh trên trang web **Hailuo AI Video Generator**, giúp bạn tiết kiệm thời gian và công sức tối đa.
<img width="902" height="912" alt="Screenshot 2025-08-25 095053" src="https://github.com/user-attachments/assets/637e499c-5a7f-437c-beee-042fe5d5f2c0" />

-----

## ✅ Các tính năng chính

  * **Tự động hóa hoàn toàn**: Tự động tải ảnh lên, nhập prompt, và khởi tạo quá trình tạo video mà không cần can thiệp thủ công.
  * **Xử lý hàng loạt**: Dễ dàng thêm một hoặc nhiều thư mục chứa ảnh để tool tự động xử lý tuần tự.
  * **Lưu và Tiếp tục Thông minh**: Tự động lưu lại tiến trình sau mỗi ảnh, cho phép bạn tiếp tục công việc một cách chính xác nếu bị gián đoạn.
  * **Quay vòng Prompt Linh hoạt**: Tự động tái sử dụng danh sách prompt một cách tuần hoàn, không cần chuẩn bị số lượng prompt bằng số lượng ảnh.
  * **Quản lý Hàng đợi Thông minh**: Tool tự động kiểm tra hàng đợi của Hailuo AI và sẽ tạm dừng nếu hàng đợi đầy, tránh lãng phí tài nguyên.
  * **Tùy chỉnh linh hoạt**: Cung cấp nhiều cài đặt chi tiết như thời gian chờ, số lần thử lại, giới hạn số ảnh trên mỗi thư mục, và nhiều hơn nữa.
  * **Hẹn giờ Tác vụ**: Lên lịch tự động tạm dừng và tiếp tục công việc vào những thời điểm cụ thể trong ngày.
  * **Giao diện Thân thiện & Tùy biến**: Giao diện trực quan, dễ sử dụng với hai chế độ Sáng/Tối, nhiều chủ đề màu sắc và hệ thống ghi log chi tiết.
  * **Xử lý Lỗi Bền bỉ**: Tự động thử lại khi gặp lỗi tải ảnh. Các ảnh bị lỗi sau nhiều lần thử sẽ được ghi lại để bạn dễ dàng kiểm tra.

-----

## 🖼️ Giao diện chính

Giao diện của tool được chia thành các khu vực chức năng rõ ràng để bạn dễ dàng thao tác.

1.  **Khu vực Dữ liệu đầu vào**: Nơi bạn thêm các thư mục ảnh và file prompt.
2.  **Khu vực Cài đặt Tác vụ**: Nơi bạn tùy chỉnh các thông số cho quá trình tự động hóa.
3.  **Khu vực Hẹn giờ**: Tùy chọn nâng cao để lên lịch chạy/dừng cho tool.
4.  **Khu vực Điều khiển**: Các nút chính để bắt đầu, tạm dừng và kết thúc tác vụ.
5.  **Khu vực Log**: Hiển thị chi tiết tiến trình công việc, các cảnh báo và lỗi (nếu có).

-----

## 📋 Hướng dẫn sử dụng

Thực hiện theo các bước sau để bắt đầu quá trình tự động hóa:

1.  **Chuẩn bị Dữ liệu**:

      * Tạo các thư mục chứa ảnh bạn muốn làm video.
      * Tạo một file `.txt` chứa danh sách các câu lệnh (prompt), mỗi prompt nằm trên một dòng. *(Lưu ý: Bạn không cần tạo số prompt bằng số ảnh, tool sẽ tự động quay vòng).*

2.  **Khởi động Tool**: Chạy file `HailuoAI v5.0.exe`.

      * *Lần đầu tiên sử dụng*: Một cửa sổ **Kích hoạt bản quyền** sẽ hiện ra. Hãy làm theo hướng dẫn để kích hoạt tool.

3.  **Thêm Thư mục ảnh**:

      * Nhấn nút **"Thêm thư mục..."** để chọn từng thư mục.
      * Hoặc dán danh sách đường dẫn vào ô lớn rồi nhấn **"Thêm từ danh sách"**.

4.  **Chọn File Prompt**:

      * Nhấn nút **"Browse..."** ở mục "File prompt" và chọn file `.txt` bạn đã chuẩn bị.

5.  **Tùy chỉnh Cài đặt**:

      * Chỉnh sửa các thông số trong khu vực "Cài đặt tác vụ" nếu cần. Xem giải thích chi tiết ở phần dưới.

6.  **Kết nối Trình duyệt**:

      * **Quan trọng**: Hãy đóng tất cả các cửa sổ Firefox đang mở trên máy của bạn.
      * Nhấn nút **"Mở trình duyệt"**. Tool sẽ mở một cửa sổ Firefox mới với profile mặc định của bạn.
      * Hãy chắc chắn bạn đã đăng nhập vào trang `hailuoai.video` trên trình duyệt này.
      * *Nếu trình duyệt không mở*: Nhấn nút **"Chọn Profile"** để tự chọn thủ công thư mục profile Firefox của bạn rồi thử lại.

7.  **Bắt đầu Chạy**:

      * Khi trình duyệt đã sẵn sàng, nhấn nút **"Bắt đầu chạy"**. Quá trình tự động hóa sẽ bắt đầu.

8.  **Theo dõi và Điều khiển**:

      * Quan sát tiến trình trong khu vực Log.
      * Sử dụng nút **"Tạm dừng"** / **"Tiếp tục"** để quản lý tác vụ.
      * Nhấn **"Kết thúc"** để dừng hoàn toàn quá trình (tool sẽ hoàn thành nốt tác vụ đang dở và dừng lại).

-----

## 💡 Cơ chế Thông minh

Tool được tích hợp các cơ chế tự động giúp trải nghiệm của bạn mượt mà và hiệu quả hơn.

### 1\. Tự động lưu tiến trình

Sau khi xử lý thành công **mỗi một ảnh**, tool sẽ **tự động cập nhật giá trị trong ô "Bắt đầu từ ảnh số"** lên con số tiếp theo. Nếu bạn chủ động nhấn "Kết thúc" hoặc tool dừng lại vì bất kỳ lý do gì, bạn không cần phải nhớ mình đã làm đến ảnh nào. Khi chạy lại, chỉ cần chọn lại đúng thư mục đó, tool sẽ tự động bắt đầu từ ảnh còn dang dở.

### 2\. Tự động quay vòng Prompt

Nếu số lượng ảnh trong thư mục nhiều hơn số lượng prompt, tool sẽ **tự động quay vòng, sử dụng lại các prompt từ đầu**. Ví dụ: bạn có 100 ảnh nhưng chỉ có 10 prompt. Ảnh thứ 11 sẽ tự động quay lại sử dụng prompt 1. Điều này giúp bạn không cần chuẩn bị một danh sách prompt quá dài.

-----

## ⚙️ Giải thích các Cài đặt

### Khu vực Dữ liệu đầu vào

  * **Thêm thư mục...**: Mở hộp thoại để chọn một thư mục ảnh và thêm vào hàng đợi.
  * **Xóa thư mục / Xóa tất cả**: Xóa các thư mục đã chọn hoặc xóa toàn bộ khỏi hàng đợi.
  * **Dán danh sách đường dẫn**: Bạn có thể dán nhiều đường dẫn thư mục (mỗi đường dẫn một dòng) vào đây và nhấn **Thêm từ danh sách** để thêm hàng loạt.
  * **File prompt**: Đường dẫn đến file `.txt` chứa các câu lệnh của bạn.

### Khu vực Cài đặt Tác vụ

  * **Bắt đầu từ ảnh số**: Tool sẽ bắt đầu xử lý từ ảnh thứ `N` trong thư mục. Giá trị này sẽ được tự động cập nhật.
  * **Số lần thử lại**: Nếu một ảnh bị lỗi khi tải lên, tool sẽ tự động thử lại `N` lần trước khi bỏ qua.
  * **Giao diện (Tối / Sáng) và Chủ đề**: Cho phép bạn tùy chỉnh giao diện. Nhấn nút gạt để đổi chế độ Sáng/Tối, hoặc chọn một chủ đề màu sắc khác từ menu thả xuống.
  * **Chờ xử lý ảnh (s)**: Thời gian (giây) tool sẽ chờ sau khi tải ảnh lên để trang web xử lý.
  * **Chờ tạo video (s)**: Thời gian (giây) tool sẽ chờ sau khi nhấn nút tạo video.
  * **Chờ hàng đợi (s)**: Nếu hàng đợi của Hailuo AI đầy, tool sẽ chờ `N` giây trước khi kiểm tra lại.
  * **Số ảnh / thư mục (0 = tất cả)**: Giới hạn số lượng ảnh sẽ được xử lý trong mỗi thư mục. Để `0` nếu muốn xử lý tất cả ảnh.

### Khu vực Điều khiển

  * **Mở trình duyệt**: Mở trình duyệt Firefox và kết nối với tool.
  * **Chọn Profile**: Dùng trong trường hợp tool không tự tìm thấy profile Firefox. Nút này cho phép bạn chọn thủ công và sẽ mở sẵn thư mục profile phổ biến nhất.
  * **Bắt đầu chạy**: Khởi động quá trình tự động hóa.
  * **Tạm dừng / Tiếp tục**: Tạm dừng hoặc tiếp tục tác vụ đang chạy.
  * **Kết thúc**: Gửi yêu cầu dừng tác vụ một cách an toàn.

-----

## ⚠️ Lưu ý quan trọng

  * Luôn **đóng tất cả các cửa sổ Firefox khác** trước khi nhấn nút "Mở trình duyệt" để đảm bảo tool có thể kết nối đúng cách.
  * Tool sử dụng **profile mặc định** của Firefox để bạn không cần đăng nhập lại. Hãy đảm bảo bạn đã đăng nhập vào Hailuo AI trên Firefox trước đó.
  * Nếu bạn nhấn **Kết thúc**, tool sẽ lưu lại thư mục đang xử lý dang dở. Lần chạy tiếp theo, bạn có thể bắt đầu lại từ thư mục đó.

-----

## ❓ Giải đáp thắc mắc

  * **Hỏi:** Tool báo lỗi "Không thể tự động tìm thấy profile Firefox"?

      * **Đáp:** Do Firefox của bạn được cài ở một vị trí không chuẩn. Hãy nhấn nút **"Chọn Profile"** và tự điều hướng đến thư mục profile của bạn.

  * **Hỏi:** Tại sao một số ảnh bị lỗi và bị bỏ qua?

      * **Đáp:** Có thể do kết nối mạng không ổn định hoặc ảnh có định dạng không được hỗ trợ. Tool đã tự động thử lại nhiều lần nhưng không thành công. Bạn có thể xem danh sách các ảnh lỗi bằng cách nhấn vào chữ **"Log: (X ảnh lỗi)"**.

  * **Hỏi:** Tool đang chạy thì dừng lại mà không có thông báo gì?

      * **Đáp:** Hãy kiểm tra khu vực Log để xem thông báo lỗi cuối cùng. Nguyên nhân có thể do mất kết nối internet, trang Hailuo AI thay đổi giao diện, hoặc trình duyệt bị treo. Hãy thử khởi động lại tool.
