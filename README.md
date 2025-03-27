<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WhatsApp AI Bot</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700;600;500;400&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            margin: 0;
            padding: 20px;
            color: white;
        }
        
        .ad-container {
            max-width: 500px;
            margin: 0 auto;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 20px;
            padding: 25px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            overflow: hidden;
            position: relative;
        }
        
        .ad-container::before {
            content: "";
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
            animation: rotate 15s linear infinite;
            z-index: -1;
        }
        
        @keyframes rotate {
            100% { transform: rotate(360deg); }
        }
        
        .header {
            text-align: center;
            margin-bottom: 20px;
            position: relative;
        }
        
        .title {
            font-size: 28px;
            font-weight: 700;
            margin: 0;
            background: linear-gradient(to right, #ff8a00, #e52e71);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
        
        .subtitle {
            font-size: 16px;
            opacity: 0.9;
            margin: 10px 0 0;
        }
        
        .features {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 15px;
            margin: 20px 0;
        }
        
        .feature-list {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
            list-style: none;
            padding: 0;
        }
        
        .feature-item {
            display: flex;
            align-items: center;
            font-size: 14px;
            padding: 8px 10px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 8px;
            transition: all 0.3s;
        }
        
        .feature-item:hover {
            transform: translateY(-3px);
            background: rgba(255, 255, 255, 0.2);
        }
        
        .feature-item::before {
            content: "✓";
            color: #4CAF50;
            font-weight: bold;
            margin-right: 8px;
        }
        
        .highlight {
            font-weight: 600;
            color: #FFEB3B;
        }
        
        .testimonial {
            font-style: italic;
            text-align: center;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            margin: 20px 0;
            position: relative;
        }
        
        .testimonial::before, .testimonial::after {
            content: '"';
            font-size: 24px;
            color: rgba(255, 255, 255, 0.5);
        }
        
        .cta {
            text-align: center;
            margin-top: 25px;
        }
        
        .contact-button {
            display: inline-block;
            background: linear-gradient(45deg, #25D366, #128C7E);
            color: white;
            padding: 12px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 18px;
            box-shadow: 0 5px 15px rgba(18, 140, 126, 0.4);
            transition: all 0.3s;
            border: none;
            cursor: pointer;
        }
        
        .contact-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(18, 140, 126, 0.6);
        }
        
        .contact-button:active {
            transform: translateY(1px);
        }
        
        .emoji {
            font-size: 20px;
            margin-right: 5px;
            vertical-align: middle;
        }
        
        .note {
            font-size: 12px;
            text-align: center;
            opacity: 0.7;
            margin-top: 15px;
        }
        
        @media (max-width: 480px) {
            .feature-list {
                grid-template-columns: 1fr;
            }
            
            .title {
                font-size: 24px;
            }
        }
    </style>
</head>
<body>
    <div class="ad-container">
        <div class="header">
            <h1 class="title">🚀 Supercharge Your WhatsApp with SAMITECH AI! 🤖</h1>
            <p class="subtitle">300+ Powerful Commands - Control WhatsApp like never before!</p>
        </div>
        
        <div class="features">
            <ul class="feature-list">
                <li class="feature-item"><span class="emoji">📸</span> Save view-once messages</li>
                <li class="feature-item"><span class="emoji">❤️</span> Auto-view & like messages</li>
                <li class="feature-item"><span class="emoji">🔄</span> Auto-add/remove group contacts</li>
                <li class="feature-item"><span class="emoji">👊</span> Fun commands (slap, prank)</li>
                <li class="feature-item"><span class="emoji">🎨</span> Turn text into stylish images</li>
                <li class="feature-item"><span class="emoji">🕵️</span> View deleted messages</li>
                <li class="feature-item"><span class="emoji">😂</span> Auto-react to messages</li>
                <li class="feature-item"><span class="emoji">⚡</span> Stay "online" 24/7</li>
            </ul>
        </div>
        
        <div class="testimonial">
            "This bot changed how I use WhatsApp! The auto-reply feature saves me hours every week."
            <div class="highlight">- Happy User</div>
        </div>
        
        <div class="cta">
            <a href="https://wa.me/237674137259" class="contact-button">
                <span class="emoji">📲</span> Contact Me Now!
            </a>
            <div class="note">WhatsApp: +237 674 137 259</div>
        </div>
    </div>
</body>
</html>
