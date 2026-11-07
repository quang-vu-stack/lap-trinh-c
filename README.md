# C ACADEMY — Học lập trình C từ cơ bản đến nâng cao

Website tự học lập trình **C (C11)** bằng tiếng Việt, chạy trực tiếp trên trình duyệt và không cần npm / Node.js.

## Nội dung
- **9 chương**, **34 bài giảng**, ví dụ code C và phần ghi nhớ.
- **238 bài tập** từ dễ đến khó, gợi ý khi cần.
- **68 câu hỏi trắc nghiệm** có giải thích đáp án sau khi nộp.
- Phòng thực hành với trình soạn thảo code C, ô nhập dữ liệu `stdin`, tải file `.c`.
- Video học C công khai, tìm kiếm, chế độ sáng/tối, sử dụng trên điện thoại.
- Lưu tiến độ và code nháp ở trình duyệt; xuất/nhập dữ liệu JSON để sao lưu.

## Cách mở
- Trên máy tính: tải `index.html` rồi mở bằng Chrome hoặc Edge.
- Khi bật GitHub Pages cho nhánh `main` / thư mục `/ (root)`, truy cập trang Pages của kho này.

## Chạy code
Trình chạy code dùng **Wandbox API** miễn phí và cần internet. Khi bạn bấm chạy, đoạn code và nội dung stdin sẽ gửi đến máy chủ của Wandbox; không nhập thông tin bí mật. Nếu API không hoạt động, có thể tải file `.c` và dùng GCC hoặc [Programiz C Online Compiler](https://www.programiz.com/c-programming/online-compiler/).

```bash
gcc -std=c11 -Wall -Wextra -Wpedantic main.c -o main
./main
```

Lưu ý: Hiện bài tập được tự đánh dấu hoàn thành, **chưa có chấm tự động theo bộ test**. Trình chạy C từ bên thứ ba có thể gián đoạn. Tiến độ lưu cục bộ theo từng trình duyệt, nên hãy xuất bản sao JSON định kỳ.

## Cấu trúc dự án
```
index.html   # Toàn bộ website C Academy
README.md    # Hướng dẫn
```
