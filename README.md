# 🍅 Pomodoro Study App

**Pomodoro Study App** là một ứng dụng web dạng "Single-file" (tất cả trong một file HTML) mạnh mẽ, được thiết kế để mang lại không gian học tập và làm việc siêu tập trung. Thay vì chỉ là một chiếc đồng hồ bấm giờ thông thường, ứng dụng tích hợp trực tiếp **Trợ lý Gemini AI**, **YouTube Background**, và hệ thống **Kho Tri Thức cá nhân hóa**.

Ứng dụng chạy hoàn toàn ở phía client, dữ liệu được giữ riêng tư 100% trên máy tính của bạn thông qua `localStorage`. Khởi động nhanh, không cần cài đặt server hay cơ sở dữ liệu!

---

## 🚀 Tính năng nổi bật

### ⏱️ Quản lý thời gian linh hoạt
*   **Pomodoro truyền thống:** Hỗ trợ đặt 2 preset (Kiểu A / Kiểu B) để luân phiên thay đổi thời gian Làm việc - Nghỉ ngắn - Nghỉ dài dễ dàng.
*   **Flowtime Mode (🌊 Flow):** Đồng hồ đếm tiến (Stopwatch) dành cho trạng thái "dòng chảy" (Flow state). Bạn làm việc đến khi nào mệt mới tự bấm nghỉ.
*   **Hạ nhiệt (Wind-down):** Khoảng thời gian đệm (từ 1-2 phút) giữa lúc làm và lúc nghỉ, giúp bạn có thời gian để ghi chú "Next steps" hoặc dọn dẹp không gian làm việc.
*   **Chế độ Zen (👁️):** Ẩn toàn bộ giao diện phức tạp để bạn chỉ tập trung vào một chiếc đồng hồ hiện trên hình nền trong suốt tuyệt đẹp.

### 🧠 Tích hợp Gemini AI
*   **Chatbot riêng:** Hỏi đáp trực tiếp về chủ đề đang học (yêu cầu cấu hình Gemini API Key tùy chọn).
*   **Tự động định dạng văn bản (Auto-format):** Soạn thảo ghi chú nháp thô, sau đó chỉ bằng một cú click chuột, AI sẽ phân tách tiêu đề, in đậm từ khóa quan trọng và tạo danh sách gọn gàng (HTML format).
*   *Lưu ý: Mọi tính năng AI hoạt động trực tiếp từ trình duyệt kết nối tới Google Generative Language API.*

### 🎵 Không gian làm việc đắm chìm
*   **Nhạc nền Youtube (Youtube Player):** Dán bất kỳ link Youtube Lofi / Playlist nào vào. Ứng dụng sẽ phát nhạc ở dạng nền, đồng thời tự động mượn luôn hình thu nhỏ (Thumbnail chất lượng cao) của video đó làm ảnh nền không gian học tập của bạn.
*   **Đa dạng chủ đề (Themes):** Không thích Youtube? Chọn các presets có sẵn bao gồm *Trà sữa (Light), Dễ thương (Pastel), Lofi Study Room* hoặc *Space Station*. Không giới hạn, bạn hoàn toàn có thể Upload thư mục/ảnh nền máy tính trực tiếp từ giao diện.
*   **Chuông báo tùy chỉnh:** Tải lên các file âm thanh (`.mp3`, `.wav`,...) riêng của bạn để làm chuông báo lúc hết giờ Làm hoặc lúc hết giờ Nghỉ thay vì chuông mặc định.

### 📚 Hệ thống quản lý tri thức sâu (Wiki)
*   **Cấu trúc Lĩnh vực -> Chủ đề con:** Phân mảnh kiến thức dễ hơn (VD: Tiếng Anh -> Phát âm).
*   **Danh sách công việc (To-do list):** Đi kèm riêng cho từng subtopic.
*   **Kho Tri Thức riêng rẽ:** Mỗi chủ đề con có khu vực nhập liệu kiến thức riêng với trình soạn thảo Rich Text Format. Tránh được tình trạng ghi chú Toán lẫn lộn với ghi chú Tiếng Anh.

### 🛡️ Độ riêng tư & Sao lưu
*   **Hoạt động OFFLINE** (ngoại trừ Youtube & API AI).
*   Dữ liệu được tự động lưu cục bộ (`localStorage`).
*   Khả năng xuất/nhập tệp `.json` để sao lưu thủ công hoặc chuyển dữ liệu từ máy tính sang điện thoại/máy tính khác.

---

## 🛠️ Cài đặt & Sử dụng

Vì là một "Single-file App", bạn có **2 cách** vô cùng đơn giản để sử dụng:

### Cách 1: Chạy trực tiếp (Local)
1. Tải file `02.html` về máy.
2. Click đúp chuột, mở nó bằng bằng trình duyệt yêu thích của bạn (Chrome, Edge, Safari...).
3. Bắt đầu phiên làm việc! 

### Cách 2: Host trên Github Pages (Khuyên dùng 😎)
Nếu bạn muốn truy cập không gian học tập này từ bất kì đâu (công ty, nhà, điện thoại):
1. Đăng nhập vào Github, tạo một repository mới (ví dụ: `study-zone`).
2. Kích hoạt tính năng **Github Pages** trên repo đó.
3. Upload tệp `02.html` lên repo và đổi tên nó thành `index.html`.
4. Bây giờ web sẽ sống tại đường dẫn: `https://<ten_cua_ban>.github.io/study-zone`. Mọi dữ liệu vẫn chỉ lưu tự động trên thiết bị nơi bạn dùng vào link đó.

---

## ⌨️ Phím tắt (Hotkeys)
Để tối đa tính "Flow", ứng dụng hỗ trợ các phím tắt bàn phím:
*   `Space`: Bắt đầu / Tạm dừng / Tiếp tục đồng hồ.
*   `N`: Bỏ qua (Skip) phiên hiện tại và chuyển sang phiên kế tiếp.
*   `Esc`: Tắt và đóng các Modal thông báo hoặc Cửa sổ Cài đặt.
*   `Alt + Các phím mũi tên`: Thay đổi vị trí / dịch chuyển đồng hồ khi đang trong Chế độ Zen.

---

## ⚙️ Cấu hình Gemini AI (Tùy chọn)

1. Truy cập [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Tạo một khóa API (API Key) hoàn toàn miễn phí.
3. Kích hoạt ứng dụng, nhấn vào nút hình Bánh răng ⚙️ ở dưới cùng menu bên trái. 
4. Qua tab **Tích hợp**, dán mã khóa vào ô `Gemini API Key`. Mọi tính năng cực chất của AI sẽ được bật lên tức thì!

---

## 🙋 Đóng góp
Dù là một dự án nhỏ cá nhân, nếu bạn có ý tưởng tối ưu hiệu suất tốt hơn hoặc muốn đóng góp mã nguồn (PR/Issue), mọi ý kiến đều được hoan nghênh nồng nhiệt!
