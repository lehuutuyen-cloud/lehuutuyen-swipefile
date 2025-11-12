# lehuutuyen-swipefile
Kho tri thức có cấu trúc do Lê Hữu Tuyến xây dựng, nhằm lưu trữ và hệ thống hóa những tinh hoa rút ra từ sách thông qua mô hình 5 lớp chiết xuất — giúp hỗ trợ tư duy, học tập và ứng dụng cùng AI trong marketing và chiến lược kinh doanh.

# 🧠 Mental Swipefile

Lưu trữ tri thức đọc được, theo 5 bộ lọc cố định trong từng chương:

1. 🧠 Core Mindsets (Tư duy Cốt lõi)
2. 💡 Counter-intuitive Views (Góc nhìn Mới / Phản trực giác)
3. 🎣 Hooks & Angles (Mồi câu & Hooks)
4. 🛠️ Frameworks & Strategies (Mô hình & Chiến lược)
5. 💬 Golden Quotes (Trích dẫn Vàng)

---

## 📂 Cấu trúc thư mục
- mental-swipefile/
- ├── books/
- │ ├── book_name/
- │ │ ├── chapter_01.txt
- │ │ ├── chapter_02.txt
- │ │ └── summary.txt
- └── templates/
- └── chapter_template.txt

---

## 🧩 Cách sử dụng với AI

- Dùng dự án này như **bộ nhớ dài hạn** khi làm việc với GPT.  
- Khi cần trích dẫn, bảo AI truy vấn:  
  > “Tìm trong `core-mindsets` những bài học liên quan đến tư duy hệ thống.”  
- Có thể thêm metadata trong `index.json` để AI tra cứu nhanh hơn.
- [Gemini thực hiện](https://gemini.google.com/gem/1UD5XnH4tLSvwcQ79PkFBk6mwo_2fLj_Y?usp=sharing)

---

## ⚙️ Tự động mở rộng

- Khi thêm sách mới → chỉ cần tạo thư mục mới trong `/books/`.
- Không cần cập nhật `index.json`.
- Có thể viết script (Python hoặc Node) để tự quét và cập nhật metadata nếu muốn dùng với AI.

---

## Liên hệ
- Owner: Lê Hữu Tuyến
- Website: http://lehuutuyen.com
