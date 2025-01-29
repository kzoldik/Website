<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة ويب بسيطة</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body { background-color: #f8f9fa; }
        .hero { padding: 50px 20px; text-align: center; }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">موقعي</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">الرئيسية</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">خدماتنا</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">اتصل بنا</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="hero bg-primary text-white">
        <h1>مرحبًا بك في موقعي</h1>
        <p>هذا مثال لصفحة ويب حديثة باستخدام Bootstrap</p>
        <a href="#" class="btn btn-light">تعرف أكثر</a>
    </div>

    <div class="container my-5">
        <div class="row">
            <div class="col-md-4">
                <div class="card p-3 text-center">
                    <h3>ميزة 1</h3>
                    <p>وصف مختصر عن الميزة</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card p-3 text-center">
                    <h3>ميزة 2</h3>
                    <p>وصف مختصر عن الميزة</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card p-3 text-center">
                    <h3>ميزة 3</h3>
                    <p>وصف مختصر عن الميزة</p>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-dark text-white text-center py-3">
        &copy; 2025 جميع الحقوق محفوظة
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
