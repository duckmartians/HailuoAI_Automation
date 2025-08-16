<img width="902" height="812" alt="image" src="https://github.com/user-attachments/assets/889cf103-046c-44b3-acd5-ebdd687178ed" />

### **HƯỚNG DẪN SỬ DỤNG TOOL TỰ ĐỘNG HAILUO v4.0**

**Ngày cập nhật:** 16 tháng 8, 2025
***
#### **1. Giới thiệu**

Chào mừng bạn đến với Tool Tự động Hailuo v4.0\! Công cụ này được thiết kế để tự động hóa hoàn toàn quá trình tạo video từ ảnh và prompt trên nền tảng Hailuo AI, giúp bạn tiết kiệm thời gian và công sức tối đa.

#### **2. Yêu cầu Hệ thống**

Để sử dụng tool, máy tính của bạn cần đáp ứng các yêu cầu sau:

  * **Hệ điều hành:** Windows 10 hoặc Windows 11.
  * **Trình duyệt web:** **Mozilla Firefox** (bắt buộc phải được cài đặt trên máy).
  * **File chương trình:** `HailuoAI v4.0.exe`.

#### **3. Cài đặt và Chuẩn bị (Quan trọng - Chỉ làm 1 lần đầu tiên)**

Trước khi chạy tool, bạn cần chuẩn bị một vài thứ sau:

**Bước 1: Đăng nhập tài khoản trên Firefox (Rất quan trọng)**
Do phiên Firefox đặc biệt dùng cho tool không hỗ trợ đăng nhập Google, bạn cần phải đăng nhập trước trên Firefox thông thường để website Hailuo ghi nhớ tài khoản.

1.  Mở trình duyệt Firefox của bạn một cách bình thường.
2.  Truy cập vào trang web: **[https://hailuoai.video](https://hailuoai.video)**
3.  Thực hiện **Đăng nhập (Login)** bằng tài khoản Google của bạn.
4.  Sau khi đăng nhập thành công, hãy tắt Firefox đi. Quá trình này chỉ cần làm một lần.

**Bước 2: Chuẩn bị Thư mục Dữ liệu**

  * **Thư mục Ảnh:** Tạo một thư mục và sao chép tất cả các file ảnh bạn muốn tạo video vào đó.
  * **File Prompt:** Tạo một file văn bản (`.txt`). Trong file này, mỗi dòng là một câu prompt. Thứ tự các dòng prompt phải tương ứng với thứ tự các file ảnh trong thư mục của bạn.

**Bước 3: Tạo Lối tắt (Shortcut) để khởi động Firefox đặc biệt**
Bây giờ, chúng ta sẽ tạo một lối tắt để chạy Firefox ở chế độ tool có thể kết nối.

1.  Nhấn chuột phải vào màn hình Desktop, chọn **New** -\> **Shortcut**.
2.  Trong ô "Type the location of the item", hãy sao chép và dán chính xác dòng lệnh dưới đây vào:
    ```
    "C:\Program Files\Mozilla Firefox\firefox.exe" -marionette -start-debugger-server 2828
    ```
3.  Nhấn **Next**.
4.  Ở ô đặt tên, bạn có thể gõ `Khởi động Firefox cho Tool` rồi nhấn **Finish**.

Bây giờ bạn đã có một icon shortcut mới trên màn hình.

#### **4. Hướng dẫn Sử dụng**

**Bước 1: Khởi động**

1.  Nhấn đúp chuột vào shortcut **"Khởi động Firefox cho Tool"** mà bạn vừa tạo. Một cửa sổ Firefox sẽ mở ra và tự động truy cập trang Hailuo (bạn sẽ thấy mình đã ở trong trạng thái đăng nhập).
2.  **Giữ nguyên cửa sổ Firefox đó**, không được tắt.
3.  Bây giờ, hãy chạy file `HailuoAI v4.0.exe`. Giao diện chính của tool sẽ hiện ra.

**Bước 2: Kích hoạt bản quyền (Lần đầu tiên)**
Nếu đây là lần đầu bạn chạy tool, một cửa sổ "Kích hoạt" sẽ hiện ra.

1.  Nhấn nút "Sao chép" để lấy mã nhận dạng.
2.  Gửi mã này cho nhà phát triển để nhận Chuỗi kích hoạt.
3.  Dán chuỗi kích hoạt vào ô và nhấn "Kích hoạt".

**Bước 3: Thiết lập các Tác vụ**
Trên giao diện chính, hãy điền các thông tin sau:

  * **Thư mục ảnh:** Nhấn nút **"Browse..."** và chọn đến thư mục chứa ảnh bạn đã chuẩn bị.
  * **File prompt:** Nhấn nút **"Browse..."** và chọn đến file `.txt` chứa các câu lệnh của bạn.
  * **Bắt đầu từ ảnh số:** Mặc định là `1`. Nếu bạn muốn chạy tiếp từ ảnh số 5, hãy điền `5`.
  * **Số lần thử lại:** Nếu một ảnh bị lỗi, tool sẽ tự động thử lại bấy nhiêu lần trước khi bỏ qua. Mặc định là `3`.
  * **Giao diện:**
      * **Nút "Chế độ Sáng" / "Chế độ Tối":** Nhấn để lọc danh sách theme trong menu bên cạnh.
      * **Menu thả xuống:** Chọn một phong cách giao diện bạn thích.
  * **Các ô Thời gian chờ (giây):**
      * **Chờ xử lý ảnh:** Thời gian chờ sau khi tải ảnh lên.
      * **Chờ tạo video:** Thời gian chờ sau khi bấm nút "Run" để video được tạo.
      * **Chờ hàng đợi:** Thời gian chờ nếu phát hiện hàng đợi của Hailuo đang đầy.

**Bước 4: Bắt đầu chạy**

  * **Bắt đầu chạy:** Sau khi thiết lập xong, nhấn nút này. Nút sẽ chuyển thành "Đang chạy" và quá trình tự động hóa sẽ bắt đầu.
  * **Tạm dừng / Tiếp tục:** Nhấn để tạm dừng. Nút sẽ chuyển thành "Tiếp tục". Nhấn lần nữa để chạy lại.
  * **Kết thúc:** Dừng hoàn toàn quá trình đang chạy.

**Bước 5: Theo dõi tiến trình**

  * Toàn bộ quá trình làm việc của tool sẽ được hiển thị chi tiết trong ô **"Log"**.
  * Nếu có ảnh nào bị lỗi sau khi đã thử lại nhiều lần, nhãn "Log" sẽ cập nhật số lượng (ví dụ: `Log: (2 ảnh lỗi)`). Bạn có thể nhấn vào nhãn này để xem danh sách các ảnh đã bị lỗi.

#### **5. Xử lý Lỗi thường gặp**

  * **Tool báo lỗi "Không thể kết nối..." hoặc không chạy?**

      * **Nguyên nhân:** Rất có thể bạn đã quên không chạy shortcut **"Khởi động Firefox cho Tool"** trước, hoặc đã lỡ tay tắt cửa sổ Firefox đó.
      * **Giải pháp:** Tắt tool đi. Chạy lại shortcut Firefox, sau đó mở lại tool.

  * **Tool chạy nhưng không đăng nhập được?**

      * **Nguyên nhân:** Bạn đã bỏ qua **Bước 1** trong phần "Cài đặt và Chuẩn bị".
      * **Giải pháp:** Tắt tool và shortcut Firefox. Mở Firefox bình thường, đăng nhập vào trang Hailuo, sau đó làm lại từ đầu.

  * **Tool bị treo hoặc dừng lại rất lâu?**

      * **Nguyên nhân:** Có thể hàng đợi của Hailuo đang rất đầy.
      * **Giải pháp:** Hãy nhìn vào ô Log, tool sẽ báo "Hàng đợi đang đầy...". Vui lòng kiên nhẫn chờ, tool sẽ tự động chạy tiếp khi hàng đợi giảm xuống.

  * **Chương trình bị phần mềm diệt virus chặn?**

      * **Nguyên nhân:** Đôi khi các chương trình `.exe` tự tạo bị nhận diện nhầm là virus.
      * **Giải pháp:** Đây là cảnh báo sai (false positive). Bạn có thể tạm thời tắt phần mềm diệt virus hoặc thêm file `HailuoAI v4.0.exe` vào danh sách an toàn/ngoại lệ (exception list).

Chúc bạn sử dụng công cụ hiệu quả\!

***

### **Hailuo Automation Tool v4.0 User Guide**

**Last Updated:** August 16, 2025

**1. Introduction**

Welcome to the Hailuo Automation Tool v4.0! This tool is designed to fully automate the process of creating videos from images and prompts on the Hailuo AI platform, helping you save maximum time and effort.

**2. System Requirements**

To use the tool, your computer must meet the following requirements:
* **Operating System:** Windows 10 or Windows 11.
* **Web Browser:** **Mozilla Firefox** (must be installed on the machine).
* **Program File:** `HailuoAI v4.0.exe`.

**3. Installation and Preparation (Important - First Time Only)**

Before running the tool, you need to prepare a few things:

**Step 1: Log in to your account on Firefox (Very Important)**
Because the special Firefox session used by the tool does not support Google login, you need to log in beforehand on a normal Firefox session so the Hailuo website can remember your account.
1.  Open your Mozilla Firefox browser normally.
2.  Navigate to the website: **[https://hailuoai.video](https://hailuoai.video)**
3.  **Log in** using your Google account.
4.  After a successful login, you can close Firefox. This process only needs to be done once.

**Step 2: Prepare Your Data Folders**
* **Image Folder:** Create a folder and copy all the image files you want to create videos from into it.
* **Prompt File:** Create a text file (`.txt`). In this file, each line is a single prompt. The order of the prompt lines must correspond to the order of the image files in your folder.

**Step 3: Create a Shortcut to Launch the Special Firefox Session**
Now, we will create a shortcut to run Firefox in a mode that the tool can connect to.
1.  Right-click on your Desktop, select **New** -> **Shortcut**.
2.  In the "Type the location of the item" field, copy and paste the following command exactly:
    `"C:\Program Files\Mozilla Firefox\firefox.exe" -marionette -start-debugger-server 2828`
3.  Click **Next**.
4.  For the shortcut name, you can type `Launch Firefox for Tool` and then click **Finish**.
You now have a new shortcut icon on your desktop.

**4. How to Use**

**Step 1: Launching the Application**
1.  Double-click the **"Launch Firefox for Tool"** shortcut you just created. A Firefox window will open and navigate to the Hailuo page (you should see that you are already logged in).
2.  **Keep this Firefox window open.** Do not close it.
3.  Now, run the `HailuoAI v4.0.exe` file. The tool's main interface will appear.

**Step 2: License Activation (First Time Only)**
The first time you run the tool, an "Activation" window will appear.
1.  Click the "Copy" button to get your machine ID.
2.  Send this ID to the developer to receive an Activation Key.
3.  Paste the key into the input field and click "Activate".

**Step 3: Configuring Tasks**
On the main interface, fill in the following information:
* **Image Folder:** Click the **"Browse..."** button and select your prepared image folder.
* **Prompt File:** Click the **"Browse..."** button and select your prompt `.txt` file.
* **Start from image:** Defaults to `1`. If you want to resume from image number 5, enter `5`.
* **Retry count:** If an image fails to process, the tool will retry this many times before skipping. Defaults to `3`.
* **Interface:**
    * **"Light Mode" / "Dark Mode" Buttons:** Click to filter the theme list in the dropdown menu.
    * **Dropdown Menu:** Choose an interface style that you like.
* **Wait Times (seconds):**
    * **Image processing wait:** Time to wait after uploading an image.
    * **Video creation wait:** Time to wait after clicking "Run" for the video to be generated.
    * **Queue wait:** Time to wait if the Hailuo queue is detected to be full.

**Step 4: Running the Automation**
* **Start Automation:** After finishing setup, click this button. It will change to "Running..." and the automation process will begin.
* **Pause / Resume:** Click to pause the process. The button will change to "Resume". Click it again to continue.
* **Stop:** Completely stops the current process.

**Step 5: Monitoring Progress**
* The entire workflow of the tool will be displayed in detail in the **"Log"** area.
* If any image fails after all retries, the "Log" label will update with a count (e.g., `Log: (2 failed images)`). You can click this label to see a list of the failed images.

**5. Troubleshooting Common Issues**

* **Tool shows a "Cannot connect..." error or doesn't run?**
    * **Cause:** You likely forgot to run the **"Launch Firefox for Tool"** shortcut first, or you accidentally closed the special Firefox window.
    * **Solution:** Close the tool. Run the Firefox shortcut again, then re-launch the tool.

* **Tool runs but isn't logged in?**
    * **Cause:** You skipped **Step 1** in the "Installation and Preparation" section.
    * **Solution:** Close the tool and the special Firefox window. Open Firefox normally, log in to the Hailuo website, then start over.

* **Tool seems frozen or stops for a long time?**
    * **Cause:** The Hailuo queue might be very full.
    * **Solution:** Look at the Log window; the tool will report "Queue is full...". Please be patient, the tool will automatically resume when the queue has space.

* **Program is blocked by Antivirus software?**
    * **Cause:** Sometimes, custom-made `.exe` programs are mistakenly flagged as viruses.
    * **Solution:** This is a false positive. You can temporarily disable your antivirus or add the `HailuoAI v4.0.exe` file to its whitelist/exception list.

We hope you enjoy using the tool effectively!
