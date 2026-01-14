# QUY TẮC VIẾT ĐỒ ÁN TỐT NGHIỆP CHO AI (AI RULES)

Tài liệu này tổng hợp các quy tắc bắt buộc khi viết nội dung cho Đồ án Tốt nghiệp dựa trên Template quy định của Trường Đại học Bách khoa Hà Nội.
**YÊU CẦU:** AI phải đọc và tuân thủ tuyệt đối các quy tắc này khi soạn thảo hoặc chỉnh sửa nội dung trong dự án.

## 0. Đọc source code ở phần Chat-app/server/src và Chat-app/client/src

## 1. VĂN PHONG VÀ HÌNH THỨC (QUAN TRỌNG NHẤT)
- **Văn phong khoa học:** Tuyệt đối **KHÔNG** dùng văn nói, từ ngữ cảm thán, phóng đại, thiếu khách quan (ví dụ: *tuyệt vời, cực kỳ, rất hay, vô cùng hữu ích*...). Câu văn phải ngắn gọn, súc tích, mang tính học thuật.
- **Cấu trúc đoạn văn:**
  - Mỗi đoạn văn chỉ chứa **một ý chính** rõ ràng.
  - Câu sau phải có tính liên kết chặt chẽ với câu trước.
- **Hạn chế gạch đầu dòng:** Tuyệt đối **KHÔNG** dùng gạch đầu dòng (bullet points) để viết mô tả, giới thiệu, kết luận hay các phần tóm tắt. Phải viết thành **đoạn văn liền mạch**.
- **Tham chiếu chéo (Cross-referencing):**
  - Mọi Hình ảnh, Bảng biểu, Công thức được thêm vào phải có trích dẫn và phân tích trong nội dung (ví dụ: *"như thể hiện tại Hình 2.1..."*, *"sô liệu trong Bảng 3.2 cho thấy..."*).
  - Không được để hình/bảng "trôi nổi" mà không có lời dẫn.

## 2. QUY TẮC NỘI DUNG TỪNG CHƯƠNG

### Chương 1: Giới thiệu
- **Độ dài:** 3 - 6 trang.
- **Bố cục:** Phần "Bố cục đồ án" mô tả nội dung các chương tiếp theo phải viết thành đoạn văn xuôi, không được liệt kê dạng danh sách.

### Chương 2: Khảo sát và Phân tích
- **Nội dung:** Phải so sánh, đánh giá ưu/nhược điểm các hệ thống tương tự.
- **Đặc tả Use case:** Chỉ chọn 4-7 Use case **quan trọng nhất** để đặc tả chi tiết. Không liệt kê tràn lan.

### Chương 3: Công nghệ sử dụng (hoặc Cơ sở lý thuyết)
- **Lập luận:** Phải giải thích rõ **LÝ DO** chọn công nghệ/thuật toán đó để giải quyết vấn đề gì đã nêu ở Chương 2.
- **Minh chứng:** Phải trích dẫn nguồn tài liệu tham khảo uy tín khi nhắc đến lý thuyết hoặc công nghệ.

### Chương 4: Kết quả thực nghiệm
- **Kiến trúc:** Phân tích sự phù hợp của kiến trúc (Client-Server, MVC...) với bài toán.
- **Biểu đồ:**
  - **Biểu đồ gói (Package Diagram):** Phải phân tầng rõ ràng (Presentation, Logic, Data...), các gói không phụ thuộc vòng tròn.
  - **Thiết kế lớp (Class Design):** Chỉ cần hiện tên lớp và quan hệ, không cần hiển thị chi tiết method/attribute trong biểu đồ gói tổng quan.
- **Thống kê:** Bắt buộc có bảng thống kê kết quả (Số dòng code, số class, màn hình chính, độ bao phủ test...).

### Chương 5: Giải pháp và Đóng góp (QUAN TRỌNG)
- **Độ dài:** Tối thiểu 5 trang.
- **Nội dung:** Đây là "trái tim" của đồ án. Tập trung sâu vào các giải pháp kỹ thuật khó, thuật toán xử lý phức tạp, hoặc mô hình tối ưu mà sinh viên tự làm được.
- **Tránh lặp:** Các chương trước chỉ giới thiệu sơ lược và trỏ tham chiếu về chương này (ví dụ: *"chi tiết giải thuật sẽ được trình bày ở Chương 5"*).

### Chương 6: Kết luận và Hướng phát triển
- **Đánh giá:** Trung thực về những gì đã làm được và những hạn chế (chưa làm được).
- **Phát triển:** Đề xuất các hướng nâng cấp cụ thể, có tính khả thi.

## 3. QUY TẮC TÀI LIỆU THAM KHẢO
- **Nguồn hợp lệ:** Sách chuyên khảo, Bài báo tạp chí khoa học, Kỷ yếu hội nghị, Tài liệu kỹ thuật chính hãng (Official Documentation/References).
- **NGHIÊM CẤM:** Không trích dẫn từ Wikipedia, Slide bài giảng, Blog cá nhân, Forum, hoặc các trang web tin tức thông thường.
- **Định dạng:** Tuân thủ chuẩn IEEE (hoặc theo file `.bib` mẫu của dự án).

## 4. QUY TẮC LATEX
- Sử dụng đúng các lệnh của template: `\cite{...}`, `\ref{...}`, `\label{...}`.
- Không tự ý thay đổi các gói (packages) hoặc định dạng (margin, font) đã quy định trong file `DoAn.tex` trừ khi thực sự cần thiết.

## 5. QUY TẮC VẼ CÁC BIỂU ĐỒ
- Đảm bảo cho đúng các  ký hiệu của ngôn ngữ uml 2.5 viết dưới dạng ngôn ngữ để đưa vào công cụ planUML hoặc ngôn ngữ mermaidJs để vẽ các biểu đồ sau đó lưu dưới dạng tex vào thư mục mermaidjs (Nếu là ngôn ngữ mermaidJs)
