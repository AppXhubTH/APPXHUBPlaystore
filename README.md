<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ปุ่ม Telegram</title>
    <style>
        /* สไตล์พื้นฐานสำหรับปุ่ม */
        .telegram-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #0088cc;  /* สีฟ้า Telegram */
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-family: Arial, sans-serif;
            font-size: 16px;
            font-weight: bold;
            transition: background-color 0.3s;
            border: none;
            cursor: pointer;
        }

        /* เมื่อ hover ปุ่ม */
        .telegram-button:hover {
            background-color: #006699;
        }

        /* เพิ่มไอคอน Telegram */
        .telegram-button::before {
            content: "📱 ";
            font-size: 18px;
        }
    </style>
</head>
<body>
    <!-- ปุ่มลิงก์ไปยัง Telegram -->
    <a href="https://t.me/xhub_ccomx" 
       class="telegram-button" 
       target="_blank" 
       rel="noopener noreferrer">
        ติดต่อเรา @xhub_ccomx
    </a>

    <!-- อีกแบบ: ปุ่มที่มีเฉพาะข้อความ -->
    <br><br>
    <a href="https://t.me/xhub_ccomx" 
       style="display: inline-block; padding: 10px 20px; background-color: #26A5E4; color: white; text-decoration: none; border-radius: 5px; font-family: system-ui;" 
       target="_blank">
        🔗 เข้าร่วม Telegram @xhub_ccomx
    </a>

    <!-- แบบที่ 3: ปุ่มที่มีโลโก้ Telegram -->
    <br><br>
    <button onclick="window.open('https://t.me/xhub_ccomx', '_blank')" 
            style="padding: 15px 30px; background: linear-gradient(45deg, #0088cc, #00aced); color: white; border: none; border-radius: 50px; font-size: 18px; cursor: pointer; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
        <span style="margin-right: 8px;">✈️</span>
        Telegram: @xhub_ccomx
    </button>
</body>
</html>
