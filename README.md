<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Trường THPT Nguyễn Huệ - Hà Tĩnh</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            background-color: #f4f6f9;
            line-height: 1.6;
        }

        /* ===== BANNER ===== */
        .banner {
            position: relative;
            height: 300px;
            background: url("banner.jpg") center/cover no-repeat;
        }

        .banner-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: rgba(0,0,0,0.55);
            color: white;
            padding: 20px 30px;
            text-align: center;
            border-radius: 10px;
        }

        nav {
            background-color: #144a7d;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            padding: 20px;
            background-color: white;
        }

        h2 {
            color: #1e6bb8;
            border-bottom: 2px solid #1e6bb8;
            padding-bottom: 5px;
        }

        ul {
            margin-left: 20px;
        }

        footer {
            background-color: #1e6bb8;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        /* ===== MOBILE ===== */
        @media (max-width: 600px) {
            .banner {
                height: 220px;
            }

            nav a {
                display: block;
                margin: 8px 0;
            }
        }
    </style>
</head>
<body>

<!-- ===== BANNER ===== -->
<div class="banner">
    <div class="banner-text">
        <h1>Trường THPT Nguyễn Huệ</h1>
        <p>Hơn 50 năm xây dựng và phát triển (1972 – nay)</p>
    </div>
</div>

<!-- ===== MENU ===== -->
<nav>
    <a href="#gioithieu">Giới thiệu</a>
    <a href="#lichsu">Lịch sử</a>
    <a href="#cosovatchat">Cơ sở vật chất</a>
    <a href="#hoatdong">Hoạt động</a>
    <a href="#doingu">Đội ngũ</a>
</nav>

<div class="container">

    <section id="gioithieu">
        <h2>Giới thiệu chung</h2>
        <p>
            Trường THPT Nguyễn Huệ tại Hà Tĩnh là ngôi trường có bề dày lịch sử,
            được thành lập năm 1972 tại Kỳ Anh. Trải qua nhiều giai đoạn khó khăn,
            nhà trường luôn nỗ lực dạy tốt – học tốt, xây dựng môi trường học tập
            xanh, sạch, an toàn với khuôn viên rộng rãi, nhiều sân chơi và bãi tập TDTT.
        </p>
        <ul>
            <li><b>Tên đầy đủ:</b> Trường THPT Nguyễn Huệ</li>
            <li><b>Địa chỉ:</b> Xã Kỳ Xuân, huyện Kỳ Anh, tỉnh Hà Tĩnh</li>
            <li><b>Thành lập:</b> 31/7/1972</li>
            <li><b>Website:</b> thptnguyenhuehatinh.edu.vn</li>
        </ul>
    </section>

    <section id="lichsu">
        <h2>Lịch sử và truyền thống</h2>
        <p>
            Trường THPT Nguyễn Huệ có lịch sử hơn 50 năm, gắn liền với vùng đất
            giàu truyền thống văn hóa, hiếu học (Xứ Voi) và tên tuổi người anh hùng
            Quang Trung – Nguyễn Huệ.
        </p>
        <ul>
            <li>Thành lập năm 1972 tại xã Kỳ Tiến</li>
            <li>Huân chương Lao động hạng Ba</li>
            <li>Bằng khen của Thủ tướng Chính phủ</li>
        </ul>
    </section>

    <section id="cosovatchat">
        <h2>Cơ sở vật chất</h2>
        <ul>
            <li>5 dãy nhà cao tầng, phòng học và phòng chức năng</li>
            <li>Phòng thí nghiệm, phòng làm việc hiện đại</li>
            <li>Sân bóng, bãi tập TDTT</li>
            <li>Khuôn viên xanh – sạch – đẹp</li>
        </ul>
    </section>

    <section id="hoatdong">
        <h2>Hoạt động nổi bật</h2>
        <ul>
            <li>Tiếng hát giáo viên</li>
            <li>Tìm kiếm tài năng học sinh</li>
            <li>Tuyên truyền pháp luật</li>
            <li>Xuân Yêu Thương – Tết Nhân Ái</li>
        </ul>
    </section>

    <section id="doingu">
        <h2>Đội ngũ Ban Giám hiệu</h2>
        <ul>
            <li><b>Hiệu trưởng:</b> Võ Tiến Hùng</li>
            <li><b>Phó Hiệu trưởng:</b> Phạm Hồng Dương</li>
            <li><b>Phó Hiệu trưởng:</b> Lê Ngọc Sơn</li>
        </ul>
    </section>

</div>

<footer>
    © 2025 Trường THPT Nguyễn Huệ – Hà Tĩnh
</footer>

</body>
</html>
