<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>加入我们 - 飞书商务合作</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: '微软雅黑', sans-serif;
        }

        
        body {
    background: #f0f2f5;
    line-height: 1.6;
    width: 100%;
    height: 100%;
    background-image: url(https://shsjyn.github.io/beijing.png);
}

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 50px;
        }

        .logo {
            width: 90px;
            margin-bottom: 20px;
        }

        h1 {
            color: #1a1a1a;
            font-size: 2.5em;
            margin-bottom: 15px;
        }

        .content {
            display: flex;
            gap: 40px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 320px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .qrcode {
            width: 200px;
            height: 200px;
            margin: 20px auto;
            border: 1px solid #ddd;
            padding: 10px;
            background: white;
        }

        .cta-button {
            display: inline-block;
            background: #3370ff;
            color: white !important;
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: background 0.3s ease;
        }

        .cta-button:hover {
            background: #295dbf;
        }

        .steps {
            margin: 30px 0;
            text-align: left;
        }

        .step {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 8px;
        }

        .step-number {
            background: #3370ff;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .card {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <!-- 替换成你的Logo -->
            <img src="https://shsjyn.github.io/logo.jpg" alt="Logo" class="logo">
            <h1>立即添加商务飞书</h1>
            <p>获取最新资讯与专属服务</p>
        </div>

        <div class="content">
            <div class="card">
                <h2>扫码添加好友</h2>
                <!-- 替换成你的二维码 -->
                <img src="https://shsjyn.github.io/erweima.jpg" alt="飞书二维码" class="qrcode">
                <p>或直接点击下方按钮添加</p>
                <!-- 替换成你的飞书链接 -->
                <a href="https://www.feishu.cn/invitation/page/add_contact/?token=864v1cc0-b526-4f99-83fa-515cc9dcb467&amp;unique_id=dFSNyxpF-ylx7xIllOqVKA==" class="cta-button" target="_blank">立即添加</a>
            </div>

            <div class="card">
                <h2>添加指引</h2>
                <div class="steps">
                    <div class="step">
                        <div class="step-number">1</div>
                        打开飞书APP
                    </div>
                    <div class="step">
                        <div class="step-number">2</div>
                        点击"通讯录" → "添加好友"
                    </div>
                    <div class="step">
                        <div class="step-number">3</div>
                        扫描二维码或搜索ID
                    </div>
                </div>
            </div>
        </div>

        <div style="text-align: center; margin-top: 50px; color: #666;">
            <p>工作日24小时内回复 | 企业官方认证账号</p>
        </div>
    </div>
</body>
</html>
