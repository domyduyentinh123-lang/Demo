# Demo
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ẩm Thực Việt Nam</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fffaf0;
        }

        header {
            background-color: #d62828;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #f77f00;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .banner {
            background-image: url('https://images.unsplash.com/photo-1604908176997-4317c4d08b38');
            background-size: cover;
            background-position: center;
            height: 250px;
        }

        .container {
            padding: 20px;
        }

        .food {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            overflow: hidden;
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card h3 {
            margin: 10px;
        }

        .card p {
            margin: 10px;
        }

        footer {
            background-color: #003049;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Ẩm Thực Việt Nam</h1>
    <p>Khám phá sự phong phú và đa dạng của ẩm thực Việt</p>
</header>

<nav>
    <a href="#">Trang chủ</a>
    <a href="#">Món Bắc</a>
    <a href="#">Món Trung</a>
    <a href="#">Món Nam</a>
</nav>

<div class="banner"></div>

<div class="container">
    <h2>Những món ăn nổi bật</h2>
    <div class="food">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1585032226651-759b368d7246" alt="Phở">
            <h3>Phở</h3>
            <p>Món ăn truyền thống nổi tiếng với nước dùng đậm đà và bánh phở mềm.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1604908554167-4c3e09c0c1f0" alt="Bánh mì">
            <h3>Bánh mì</h3>
            <p>Sự kết hợp giữa ẩm thực Việt và Pháp, giòn rụm và đầy hương vị.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1625944525903-0b2b77c9b6c2" alt="Bún bò Huế">
            <h3>Bún bò Huế</h3>
            <p>Món ăn cay nồng đặc trưng của miền Trung.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1598514982830-92db5c5e4f5a" alt="Gỏi cuốn">
            <h3>Gỏi cuốn</h3>
            <p>Món ăn thanh mát, tốt cho sức khỏe, phổ biến ở miền Nam.</p>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 Ẩm thực Việt Nam | Thiết kế bởi bạn</p>
</footer>

</body>
</html>
