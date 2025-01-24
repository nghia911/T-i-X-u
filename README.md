# Tai xiu
Uy tín
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Không Chữ</title>
    <style>
        /* Đảm bảo trang đầy đủ chiều cao và không có khoảng trống */
        body {
            margin: 0;
            padding: 0;
            height: 100vh; /* Chiều cao của trang = chiều cao của màn hình */
            display: flex;
            justify-content: center; /* Căn giữa theo chiều ngang */
            align-items: center; /* Căn giữa theo chiều dọc */
            background-color: #f2f2f2;
        }

        /* Hình ảnh chiếm toàn bộ màn hình, giữ tỷ lệ đẹp */
        img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover; /* Đảm bảo hình ảnh bao phủ toàn màn hình mà không bị méo */
        }

        /* Media Query để điều chỉnh cho các thiết bị với màn hình nhỏ */
        @media (max-width: 768px) {
            img {
                object-fit: contain; /* Nếu trên các thiết bị nhỏ hơn, hình ảnh sẽ tự điều chỉnh để không bị cắt */
            }
        }
    </style>
</head>
<body>
    <!-- Chỉ hiển thị hình ảnh mà không có chữ -->
    <img src="https://cdn.tima.vn/content-image/2024/4/2024427_chia-se-thong-tin-ve-tai-xiu.jpg" alt="Hình ảnh Tài Xỉu">
</body>
</html>
