# Hướng dẫn gỡ cài đặt môi trường python

1. Nhấn phím Windows, gõ Control Panel và mở nó lên
2. Chọn Programs > Programs and Features
3. Tìm danh sách các mục có tên bắt đầu bằng Python(ví dụ: Python 3.9.x, Python Launcher)
4. Chuột phải vào từng phiên bản Python đó và chọn Uninstall
5. Xóa các tệp tin còn sót lại trong folder C:\Users\Admin\AppData\Local\Programs\Python\
6. Kiểm tra lại biến môi trường
   1. Vào thanh tìm kiếm Windows, gõ và chọn Edit the system environment variables
   2. Nhấn nút Environment Variables
   3. Trong phần User variables và System variables, tìm dòng Path, nhấn Edit
   4. Nếu thấy đường dẫn Python cũ (ví dụ: .../Python39/...), hãy chọn và nhấn Delete
7. Xác nhận đã gỡ sạch bằng cách
   1. Mở Command Prompt (cmd) và gõ: python --version

# Hướng dẫn cài đặt môi trường python các thư viện cần thiết

1. Truy cập trang web chính thức: https://www.python.org/downloads/windows/
2. Tìm phiên bản 3.11.9
3. Chọn Windows installer (64-bit)
4. Mở file đã tải và nhấn đúp để chạy
5. Tại cửa sổ cài đặt đầu tiên, bạn BẮT BUỘC phải tích vào ô "Add python.exe to PATH" ở phía dưới cùng. Việc này giúp bạn có thể chạy Python từ bất kỳ thư mục nào thông qua Command Prompt.
6. Chọn "Install Now": Nhấn nút này để bắt đầu quá trình cài đặt mặc định.
7. Hoàn tất: Chờ vài phút cho đến khi thấy thông báo "Setup was successful", sau đó nhấn Close.
8. Cập nhập bộ cài thư viện (pip): python -m pip install --upgrade pip
9. Cài các thư viện cần thiết cho ML: pip install -r requirements.txt

# Cài đặt extensions Jupyter trên vscode để chạy từng dòng code python

1. Tạo file có đuôi .ipynb
2. Nhấn Select Kernel
3. Chọn Python 3.11.9
4. Nhấn +code để tạo một đoạn code riêng

# Quy trinh lam viec khi code

1. Cap nhap code moi nhat
   Run: git pull origin main
2. Code va kiem tra
   Run: git status
3. add file
   Run: git add .
4. commit
   Run: git commit -m "message"
5. push lên github
   Run: git push
