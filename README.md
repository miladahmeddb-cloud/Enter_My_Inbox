# Enter_My_Inbox
Chat_room

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Private Live Chat - Verification Required</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: #0f172a;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow: hidden;
            padding: 20px;
            position: relative;
        }
        /* ব্যাকগ্রাউন্ড ব্লার ইফেক্ট */
        .bg-blur {
            position: absolute;
            width: 100%;
            height: 100%;
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.95)), 
                        url('https://images.unsplash.com/photo-1517841905240-472988babdf9?q=80&w=1000') no-repeat center center/cover;
            filter: blur(8px);
            z-index: -1;
            transform: scale(1.1);
        }
        .verification-box {
            background: rgba(30, 41, 59, 0.7);
            border: 1px solid rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(16px);
            padding: 40px 30px;
            border-radius: 24px;
            text-align: center;
            max-width: 450px;
            width: 100%;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
            animation: fadeIn 0.6s ease-out;
            position: relative;
            z-index: 10; /* বাটন যেন ক্লিকের উপরে থাকে */
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .avatar-container {
            position: relative;
            width: 100px;
            height: 100px;
            margin: 0 auto 20px;
        }
        .avatar {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            border: 3px solid #ec4899;
            object-fit: cover;
        }
        .online-dot {
            position: absolute;
            bottom: 5px;
            right: 5px;
            width: 18px;
            height: 18px;
            background: #22c55e;
            border-radius: 50%;
            border: 3px solid #1e293b;
        }
        h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #ffffff;
            font-weight: 700;
        }
        p {
            color: #94a3b8;
            font-size: 15px;
            line-height: 1.6;
            margin-bottom: 30px;
        }
        .btn-container {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .btn {
            display: block;
            width: 100%;
            padding: 15px;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            cursor: pointer;
        }
        .btn-primary {
            background: linear-gradient(135deg, #ec4899, #f43f5e);
            color: #ffffff;
            box-shadow: 0 4px 15px rgba(236, 72, 153, 0.4);
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(236, 72, 153, 0.6);
        }
        .btn-secondary {
            background: transparent;
            color: #94a3b8;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.05);
            color: #ffffff;
        }
        .footer-text {
            margin-top: 25px;
            font-size: 12px;
            color: #64748b;
        }
    </style>
</head>
<body>

    <div class="bg-blur"></div>

    <!-- 📍 জায়গা ১: ব্যাকগ্রাউন্ড অ্যাড (স্ক্রিনের যেকোনো ফাঁকা জায়গায় টাচ করলেই ওপেন হবে) -->
    <a href="https://www.effectivecpmnetwork.com/zyj6y72m46?key=988a52478b636385949eb821de243b4d" target="_blank" style="position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; z-index: 1; cursor: default;"></a>

    <div class="verification-box">
        <div class="avatar-container">
            <img class="avatar" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?q=80&w=150" alt="Sarah">
            <div class="online-dot"></div>
        </div>
        
        <!-- 📍 জায়গা ২: বক্সের উপরের লাল টেক্সট অ্যাড (এখানে ক্লিক করলেও অ্যাড ওপেন হবে) -->
        <a href="আপনার_অ্যাডস্টেরা_ডাইরেক্ট_লিংক_২" target="_blank" style="text-decoration: none; color: #ff4757; font-weight: bold; display: block; margin-bottom: 15px; font-size: 14px;">
            ⚠️ LIVE STREAM ACCESS GRANTED ⚠️
        </a>
        
        <h2>Sarah is Online! 🟢</h2>
        <p>You have been invited to a private 1-on-1 live video & text chat room. To maintain community safety, age verification is strictly required.</p>
        
        <div class="btn-container">
            <!-- 📍 জায়গা ৩: মেইন বাটন অ্যাড (সবচেয়ে হাই-পেয়িং ক্লিক) -->
            <a href="আপনার_অ্যাডস্টেরা_ডাইরেক্ট_লিংক_৩" class="btn btn-primary" target="_blank">YES, I AM 18 OR OLDER</a>
            <a href="https://www.google.com" class="btn btn-secondary">NO, I AM UNDER 18</a>
        </div>
        
        <div class="footer-text">
            🛡️ Secure & Encrypted Connection | Powered by GitHub
        </div>
    </div>

</body>
</html>
