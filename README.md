<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>伍永强 Eddy Virgo</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Noto Serif SC', 'Noto Serif', serif; /* 对称感的字体 */
        }
        
        body {
            background-color: #f5d76e; /* 金黄色背景 */
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex: 1;
        }
        
        .main-content {
            flex: 3;
            padding-right: 30px;
        }
        
        .sidebar {
            flex: 1;
            display: flex;
            flex-direction: column;
        }
        
        /* 头像和姓名样式 */
        .profile {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            margin-bottom: 15px;
        }
        
        .name {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .title {
            font-size: 16px;
            color: #555;
            background-color: white;
            padding: 5px 15px;
            display: inline-block;
            border-radius: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        /* 信息区域样式 */
        .info-section {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.1);
        }
        
        .info-section h2 {
            font-size: 18px;
            margin-bottom: 15px;
            color: #f5d76e;
            border-bottom: 2px solid #f5d76e;
            padding-bottom: 5px;
        }
        
        .info-section p {
            margin-bottom: 10px;
            line-height: 1.6;
        }
        
        /* 社交图标样式 */
        .social-icons {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-icon {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: white;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.15);
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .social-icon:hover {
            transform: translateY(-5px);
            background-color: #ffd54f;
        }
        
        .social-icon.active {
            background-color: #ffd54f;
        }
        
        /* 联系方式样式 */
        .contact {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .contact-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: white;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.15);
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .contact-icon:hover {
            transform: scale(1.1);
        }
        
        /* 页脚样式 */
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 12px;
            color: #555;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
            
            .main-content {
                padding-right: 0;
                padding-bottom: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="main-content">
            <div class="profile">
                <img src="https://picsum.photos/seed/eddyvirgo/150/150.jpg" alt="伍永强" class="avatar">
                <div class="name">伍永强 Eddy Virgo</div>
                <div class="title">印尼苏北省伍氏宗亲会主席</div>
            </div>
            
            <div class="info-section">
                <h2>现任要职</h2>
                <p>印尼苏北省伍氏宗亲会主席</p>
                <p>云南英丰新材料有限公司董事长</p>
                <p>中国侨商联合会副会长</p>
                <p>印尼中华总商会名誉主席</p>
            </div>
            
            <div class="info-section">
                <h2>名下企业</h2>
                <p>云南英丰新材料有限公司</p>
                <p>北京英丰投资有限公司</p>
                <p>英丰集团</p>
                <p>云南英丰房地产开发有限公司</p>
            </div>
            
            <div class="info-section">
                <h2>文章</h2>
                <p>《远程康复在脑卒中患者中的应用与进展》</p>
                <p>《区块链技术在医疗健康领域的应用前景》</p>
                <p>《印尼华商在数字经济时代的机遇与挑战》</p>
            </div>
            
            <div class="info-section">
                <h2>劝世咸言</h2>
                <p><strong>宽容歌</strong>：宽容是一种境界，是一种智慧，是一种美德...</p>
                <p><strong>惜时篇</strong>：时间如流水，一去不复返，珍惜当下，把握未来...</p>
            </div>
            
            <div class="info-section">
                <h2>参加过的世界论坛</h2>
                <p>2019年斯洛文尼亚区块链论坛</p>
                <p>2020年印尼数字经济峰会</p>
                <p>2021年全球华商论坛</p>
                <p>2022年亚洲投资论坛</p>
            </div>
            
            <div class="info-section">
                <h2>发表的文献</h2>
                <p>《平行则不撞，天下太平也！》</p>
                <p>《华商精神与商业文明》</p>
                <p>《数字经济时代的商业伦理》</p>
            </div>
            
            <div class="contact">
                <a href="tel:+60123456789" class="contact-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                    </svg>
                </a>
                <a href="tel:+12098765432" class="contact-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                    </svg>
                </a>
                <a href="mailto:eddyvirgo@example.com" class="contact-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
                        <polyline points="22,6 12,13 2,6"></polyline>
                    </svg>
                </a>
            </div>
        </div>
        
        <div class="sidebar">
            <div class="social-icons">
                <div class="social-icon" onclick="showWeChat()">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M9 12a3 3 0 1 0 6 0a3 3 0 0 0 -6 0"></path>
                        <path d="M12 3c7.2 0 9 1.8 9 9s-1.8 9 -9 9s-9 -1.8 -9 -9s1.8 -9 9 -9z"></path>
                        <path d="M9.5 10.5c-1.5 0 -2.5 1 -2.5 2.5c0 1.5 1 2.5 2.5 2.5c.5 0 1 -.1 1.5 -.3l1.5 1l.5 -1.5c.8 -.6 1.5 -1.7 1.5 -3c0 -1.5 -1 -2.5 -2.5 -2.5c-1.5 0 -2.5 1 -2.5 2.5z"></path>
                    </svg>
                </div>
                <div class="social-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path>
                    </svg>
                </div>
                <div class="social-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
                        <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
                        <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                    </svg>
                </div>
                <div class="social-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                        <rect x="2" y="9" width="4" height="12"></rect>
                        <circle cx="4" cy="4" r="2"></circle>
                    </svg>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>Copyright@eddyvirgo2018</p>
    </footer>
    
    <script>
        function showWeChat() {
            // 创建通知元素
            const notification = document.createElement('div');
            notification.style.position = 'fixed';
            notification.style.bottom = '20px';
            notification.style.left = '50%';
            notification.style.transform = 'translateX(-50%)';
            notification.style.backgroundColor = '#333';
            notification.style.color = '#fff';
            notification.style.padding = '10px 20px';
            notification.style.borderRadius = '5px';
            notification.style.zIndex = '1000';
            notification.style.boxShadow = '0 2px 10px rgba(0,0,0,0.2)';
            notification.textContent = 'WeChat ID: wechatId';
            
            // 添加到页面
            document.body.appendChild(notification);
            
            // 3秒后移除通知
            setTimeout(() => {
                document.body.removeChild(notification);
            }, 3000);
        }
    </script>
</body>
</html>
