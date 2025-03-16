# Hướng dẫn tạo trang trên GitHub

## Bước 1: Tạo repository mới
1. Đăng nhập vào tài khoản GitHub của bạn.
2. Nhấn vào nút **New** để tạo repository mới.
3. Điền tên repository và chọn chế độ công khai hoặc riêng tư.
4. Nhấn **Create repository**.

## Bước 2: Clone repository về máy tính
1. Mở terminal hoặc command prompt.
2. Chạy lệnh sau để clone repository về máy tính:
    ```sh
    git clone https://github.com/username/repository-name.git
    ```
3. Thay `username` bằng tên người dùng GitHub của bạn và `repository-name` bằng tên repository của bạn.

## Bước 3: Tạo trang GitHub
1. Tạo file `index.html` trong thư mục repository.
2. Thêm nội dung HTML vào file `index.html`. Ví dụ:
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My GitHub Page</title>
    </head>
    <body>
        <h1>Welcome to my GitHub Page</h1>
        <p>This is a sample page.</p>
    </body>
    </html>
    ```

## Bước 4: Đẩy thay đổi lên GitHub
1. Thêm thay đổi vào git:
    ```sh
    git add .
    ```
2. Commit thay đổi:
    ```sh
    git commit -m "Initial commit"
    ```
3. Đẩy thay đổi lên GitHub:
    ```sh
    git push origin main
    ```

## Bước 5: Kích hoạt GitHub Pages
1. Truy cập vào repository trên GitHub.
2. Nhấn vào tab **Settings**.
3. Cuộn xuống phần **GitHub Pages**.
4. Trong phần **Source**, chọn nhánh `main` và thư mục `/root`.
5. Nhấn **Save**.

Trang GitHub của bạn sẽ có sẵn tại `https://username.github.io/repository-name`.
