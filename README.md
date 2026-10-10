<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>测试1</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft Yahei", sans-serif;
        }
        body {
            background-color: #f4f7fa;
            color: #333;
        }
        /* 导航栏 */
        nav {
            background-color: #2563eb;
            padding: 1rem 5%;
        }
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            color: white;
            font-size: 24px;
            font-weight: bold;
        }
        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 30px;
            font-size:16px;
        }
        .nav-links a:hover {
            text-decoration: underline;
        }
        /* 首页横幅 */
        .banner {
            background: linear-gradient(135deg,#2563eb,#4f46e5);
            color:white;
            padding: 100px 20px;
            text-align:center;
        }
        .banner h1 {
            font-size:48px;
            margin-bottom:20px;
        }
        .banner p {
            font-size:20px;
            opacity:0.9;
            max-width:700px;
            margin:0 auto 30px;
        }
        .btn {
            display:inline-block;
            background:#fff;
            color:#2563eb;
            padding:14px 32px;
            border-radius:8px;
            text-decoration:none;
            font-weight:bold;
        }
        .btn:hover {
            opacity:0.9;
        }
        /* 内容区块 */
        .section {
            max-width:1200px;
            margin:80px auto;
            padding:0 20px;
        }
        .section-title {
            text-align:center;
            font-size:32px;
            margin-bottom:50px;
        }
        .card-wrap {
            display:grid;
            grid-template-columns: repeat(auto-fit, minmax(280px,1fr));
            gap:30px;
        }
        .card {
            background:white;
            padding:30px;
            border-radius:12px;
            box-shadow:0 4px 12px rgba(0,0,0,0.08);
        }
        .card h3 {
            margin-bottom:15px;
            font-size:22px;
        }
        /* 页脚 */
        footer {
            background:#1e293b;
            color:#ccc;
            text-align:center;
            padding:30px;
        }
    </style>
</head>
<body>
    <!--导航-->
    <nav>
        <div class="nav-container">
            <div class="logo">我的站点</div>
            <div class="nav-links">
                <a href="#home">首页</a>
                <a href="#about">关于</a>
                <a href="#service">服务</a>
                <a href="#contact">联系</a>
            </div>
        </div>
    </nav>

    <!--横幅-->
    <div class="banner" id="home">
        <h1>欢迎来到我的网站</h1>
        <p>这是一个示例网站，你可以自由修改文字、颜色、图片，改成你想要的样子。</p>
        <a href="#about" class="btn">了解更多</a>
    </div>

    <!--关于我-->
    <div class="section" id="about">
        <h2 class="section-title">关于我们</h2>
        <div class="card-wrap">
            <div class="card">
                <h3>专注开发</h3>
                <p>制作网页、小程序、各类网站项目，追求简洁美观的界面。</p>
            </div>
            <div class="card">
                <h3>响应式</h3>
                <p>电脑、手机都可以正常浏览，自动适配屏幕大小。</p>
            </div>
            <div class="card">
                <h3>易于修改</h3>
                <p>代码结构清晰，直接修改文字颜色就能改成你的专属网站。</p>
            </div>
        </div>
    </div>

    <!--联系区域-->
    <div class="section" id="contact">
        <h2 class="section-title">联系方式</h2>
        <div class="card" style="max-width:600px;margin:0 auto;">
            <p>邮箱：example@mail.com</p>
            <p>电话：138‑0000‑0000</p>
        </div>
    </div>

    <footer>
        © 2026 我的网站 | 版权所有
    </footer>

<script>
//简单JS示例：点击控制台输出提示
console.log("网站加载完成！");
</script>
</body>
</html>

