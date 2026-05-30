# 💅 Nailify – Advanced Nail Virtual Try-On and Booking System
> **Hệ thống Đặt lịch & Công cụ Thử móng Thông minh dành cho Chuỗi Salon**  
> Đồ án tốt nghiệp ngành Kỹ thuật Phần mềm (Software Engineering) – Trường Đại học FPT.

---

## 👨‍💻 Nhóm thực hiện đề tài (Team Members)
* **Giảng viên hướng dẫn (Supervisor):** Thầy **Đỗ Tấn Nhàn** (nhandt35@fe.edu.vn)

| STT | Họ và tên | Mã sinh viên | Vai trò trong nhóm |
|:-:|---|:-:|---|
| 1 | **Đoàn Trung Thành** | SE185105 | **Leader, Backend Developer** |
| 2 | **Phan Đỗ Gia Tuệ** | SE183566 | **Backend Developer** |
| 3 | **Nguyễn Ngọc Minh** | SE182009 | **Frontend Web** |
| 4 | **Võ Anh Kiệt** | SE172259 | **Frontend Mobile/Web, Backend Developer** |
| 5 | **Nguyễn Trung Hiếu** | SE181813 | **Frontend Mobile** |

---

## 📂 Cấu trúc Hệ sinh thái Repositories (Project Structure)
Để đảm bảo tính modular và dễ dàng mở rộng theo kiến trúc Clean Architecture, dự án được chia thành các phân hệ chính sau:

* 📑 **[nailify-docs](https://github.com/nailify/nailify-docs):** Nơi lưu trữ toàn bộ tài liệu đặc tả yêu cầu (SRS), phân tích hệ thống (AD/DD), thiết kế cơ sở dữ liệu (ERD) và báo cáo tiến độ.
* 📱 **[Nailify-Mobile](https://github.com/NailifyCapstone-SU26SE23/Nailify-Mobile):** Mã nguồn ứng dụng di động dành cho **Khách hàng (Customer)** được xây dựng trên nền tảng di động mạnh mẽ và ổn định bằng **Flutter & Kotlin**.
* 💻 **[Nailify-FE-Web](https://github.com/NailifyCapstone-SU26SE23/Nailify-FE-Web):** Cổng thông tin web quản trị dành cho **Admin**, **Salon Manager** và **Thợ làm móng (Staff Artist)** phát triển bằng **Next.js, ReactJS & TypeScript**.
* ⚙️ **[Nailify-BE](https://github.com/NailifyCapstone-SU26SE23/Nailify-BE):** Mã nguồn Backend API Core sử dụng **.NET Clean Architecture**, chịu trách nhiệm xử lý nghiệp vụ, quản lý cơ sở dữ liệu và quản lý trạng thái đặt lịch.

---

## 🎯 Định hướng & Tính năng nổi bật của Dự án
**Nailify** ra đời nhằm số hóa toàn diện quy trình vận hành chuỗi Salon móng nghệ thuật, giải quyết triệt để hai vấn đề lớn: Khách hàng khó hình dung mẫu móng lên tay thực tế và các tiệm nail gặp khó khăn trong bài toán tối ưu hóa lịch làm việc của thợ.

### ✨ Đối với Khách hàng (Customer App):
* 📸 **Virtual Try-On (Thử móng AI):** Đưa tay lên trước camera để ướm thử bất kỳ mẫu móng thiết kế nào trước khi đặt lịch, giúp cá nhân hóa quyết định làm đẹp.
* 🧠 **AI Style Quiz:** Trắc nghiệm cá tính 12 câu hỏi thông minh giúp phân tích tông da, phong cách sống và gợi ý mẫu móng tương thích hoàn hảo.
* 🧱 **Component-Based Pricing Builder:** Tự thiết kế bộ móng theo ý thích từ móng nền, độ dài, màu sơn nền đến họa tiết vẽ 3D/charm đính kèm kèm bảng tính giá minh bạch thời gian thực.
* 📅 **Smart Slot Suggestion:** Hệ thống tự động gợi ý 3 khung giờ tối ưu dựa trên độ phức tạp của mẫu móng, vị trí di chuyển và lịch sử đúng giờ của khách.

### 🎨 Đối với Thợ làm móng (Staff Artist):
* 🔗 **Staff-Skill Mapping:** Kết nối kỹ năng của thợ với yêu cầu kỹ thuật của mẫu móng để đảm bảo phân công chuẩn xác.
* 📅 **Lịch làm việc thông minh:** Xem lịch ca trực, danh sách khách hàng được phân công trong ngày và cập nhật tiến độ làm việc tức thì.

### 🏢 Đối với Quản lý & Admin (Manager & Admin Dashboard):
* 🗂️ **Bảng điều khiển Kanban:** Quản lý luồng trạng thái booking trực quan, hỗ trợ quy trình xác nhận 2 bước chống xung đột lịch.
* 📊 **Analytics & Reports:** Báo cáo thời gian thực về doanh thu chuỗi, tỷ lệ lấp đầy cơ sở, hiệu suất thợ và xu hướng mẫu móng thị trường.

---

## 🛠️ Công nghệ Sử dụng (Technology Stack)

| Phân hệ | Công nghệ chủ đạo |
|---|---|
| **Server-Side Core** | C# .NET, Web API, EF Core, Clean Architecture |
| **AI & Recommendation** | Python, FastAPI, Gemini API (Vision / LLM) |
| **Database** | SQL Server / PostgreSQL |
| **Mobile App (Client)** | Flutter, Kotlin |
| **Web App (Admin)** | NextJS, ReactJS, TailwindCSS, Ant Design / Shadcn UI |
| **Hosting & Cloud** | Windows Azure / AWS, Docker |

---

## 💎 Ý nghĩa Thực tiễn của Đề tài
Với **Nailify**, nhóm mong muốn mang đến một cuộc cách mạng công nghệ nhỏ cho ngành dịch vụ làm móng tại Việt Nam – nơi các mô hình kinh doanh truyền thống vẫn đang quản lý thủ công. 

Dự án không chỉ giúp nâng cao trải nghiệm mua sắm và làm đẹp trực quan cho khách hàng thông qua trí tuệ nhân tạo (AI), mà còn tối ưu hóa năng suất lao động cho người thợ, giảm thiểu tình trạng hủy lịch ẩn danh (no-shows) và đem lại dòng dữ liệu phân tích khách hàng giá trị cao cho các chủ doanh nghiệp chuỗi.
