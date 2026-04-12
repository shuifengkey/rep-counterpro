Dưới đây là mô tả chi tiết về các khía cạnh của app:

### 1. Mục đích và Đối tượng sử dụng
* **Mục đích:** Đếm số lần thực hiện động tác một cách chuyên nghiệp, hỗ trợ cả đếm thủ công và đếm tự động theo nhịp.
* **Phong cách thiết kế:** Giao diện mang đậm chất thể thao, mạnh mẽ với tông màu tối (**Dark Mode**), kết hợp giữa màu đen, cam neon, vàng và xanh lá. Font chữ sử dụng là *Bebas Neue* và *Barlow Condensed*, gợi liên tưởng đến các bảng đồng hồ đo tốc độ hoặc phòng gym hiện đại.
* **Biểu tượng (Icon):** Hình ảnh một chiếc giày **inline speed skate** (giày trượt tốc độ), cho thấy app này có thể được tối ưu cho các bài tập bổ trợ trong môn trượt patin tốc độ.

### 2. Các tính năng chính
* **Bộ đếm Reps & Sets:** * Hiển thị số rep đang thực hiện bằng font chữ rất lớn ở trung tâm.
    * Có thanh tiến trình (progress bar) trực quan cho từng hiệp.
* **Chế độ Đếm Tự động (Auto Mode):** * Cho phép cài đặt **RPM (Reps Per Minute)** để app tự động đếm theo nhịp.
    * Có thông báo đếm ngược (Countdown) trước khi bắt đầu để người dùng chuẩn bị.
* **Hệ thống Phản hồi Đa phương tiện:**
    * **Âm thanh:** Tiếng "beep" mỗi khi đếm hoặc hoàn thành hiệp.
    * **Giọng nói (Voice Count):** Hỗ trợ đọc số bằng tiếng Anh hoặc **tiếng Việt**.
    * **Rung (Vibration):** Phản hồi xúc giác khi chạm hoặc khi hoàn thành mục tiêu.
* **Quản lý Nghỉ ngơi (Rest Time):** Có đồng hồ đếm ngược thời gian nghỉ giữa các hiệp và cho phép người dùng bỏ qua (skip) nếu muốn tập tiếp ngay.
* **Lịch sử Hiệp tập:** Hiển thị danh sách các hiệp đã hoàn thành ngay trên màn hình chính dưới dạng các thẻ (badges).

### 3. Khả năng tùy chỉnh (Settings)
Người dùng có thể điều chỉnh linh hoạt:
* **Mục tiêu:** Số rep mỗi hiệp, số hiệp mục tiêu, hoặc tổng thời gian tập luyện.
* **Thời gian:** Độ dài thời gian nghỉ, nhịp độ đếm tự động (RPM).
* **Hiển thị:** Giữ màn hình luôn sáng (**Wake Lock**) để không bị tắt máy khi đang tập.

### 4. Công nghệ đặc trưng
* **PWA (Progressive Web App):** Có thể cài đặt trực tiếp lên màn hình điện thoại giống như một ứng dụng thực thụ mà không cần thông qua App Store/CH Play.
* **NoSleep/Wake Lock:** Tích hợp các kỹ thuật để ngăn điện thoại tự động khóa màn hình trong lúc người dùng đang thực hiện bài tập.
* **Offline:** Có sử dụng Service Worker để app có thể hoạt động mà không cần kết nối mạng.

### 5. Trải nghiệm người dùng
App được thiết kế để thao tác bằng một tay hoặc đặt trên sàn/giá đỡ. Nút **"TAP"** rất lớn và nhạy, giúp việc tương tác trong khi đang vận động mạnh trở nên dễ dàng hơn.
Here is the English description of the **Rep Counter Pro** app based on the code provided:

## App Overview
**Rep Counter Pro** is a high-performance Progressive Web App (PWA) specifically designed to track workout repetitions (reps) and sets. It features a professional, sports-oriented interface with a high-contrast dark theme using neon orange, gold, and green accents.

---

## Key Features

* **Reps & Sets Tracker:** * Displays the current rep count in a large, central font for maximum visibility.
    * Includes a dynamic progress bar that fills as you approach your set target.
* **Auto Mode:** * Features an "Auto Mode" where the app counts automatically based on a set **RPM (Reps Per Minute)**.
    * Includes a visual and audio countdown before the automatic counting begins.
* **Multimedia Feedback:** * **Audio:** Playback of "beeps" upon every rep and distinct tones when a set or session is completed.
    * **Voice Counting:** Supports synthesized voice counting in both **English and Vietnamese**.
    * **Haptics:** Utilizes device vibration for tactile feedback during milestones.
* **Rest Management:** * Includes a dedicated rest overlay with a countdown timer between sets.
    * Allows users to "Skip Rest" to proceed immediately to the next set.
* **Workout History:** * Displays a scrollable history row of completed sets and reps directly on the main dashboard.

---

## Technical Highlights

* **PWA Integration:** The app includes an inline manifest and service worker, allowing it to be installed on a home screen and used offline.
* **Wake Lock System:** Uses a multi-layered approach (Native API, silent video, and audio pings) to ensure the screen stays on during a workout.
* **Customization:** * Users can set targets for reps, sets, and total session time.
    * Adjustable timing for rest intervals and Auto-RPM.
* **Inline Skate Focus:** The custom-generated icon features an **inline speed skate**, suggesting the app is tailored for speed skating drills (like dry-land training or specific interval laps).

---

## User Experience
The app is built for hands-free or one-handed use. The **"TAP"** button is oversized and responsive, ensuring that even during intense physical activity, interacting with the counter remains effortless.
