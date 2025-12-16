<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>تنبه – Tanabbah</title>

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="container">

    <!-- Header -->
    <header class="header">
        <div class="brand">
            <div class="brand-logo">
                🛡️
            </div>
            <div class="brand-info">
                <h1 class="brand-title">تنبه</h1>
                <div class="brand-tagline">DIGITAL SECURITY AWARENESS</div>
            </div>
        </div>

        <div class="header-actions">
            <button class="header-btn">
                ⭐ <span class="btn-label">التطبيق</span>
            </button>

            <div class="header-divider"></div>

            <button class="header-btn report-btn">
                🚨 <span class="btn-label">إبلاغ</span>
            </button>
        </div>
    </header>

    <!-- Main Layout -->
    <div class="main-layout">

        <!-- Input Panel -->
        <div class="input-panel">
            <div class="card">
                <label class="input-label">الصق الرسالة أو الرابط المشبوه هنا:</label>

                <textarea class="message-textarea"
                    placeholder="مثال: تم تعليق حسابك. يرجى الدخول عبر الرابط لتحديث البيانات خلال 24 ساعة..."></textarea>

                <div class="button-row">
                    <button class="btn btn-paste">📋 لصق</button>
                    <button class="btn btn-clear">🗑 مسح</button>
                    <button class="btn btn-analyze">🔍 فحص الرسالة</button>
                </div>

                <div class="loading">
                    <div class="spinner"></div>
                    جارٍ تحليل المحتوى...
                </div>

                <!-- Result -->
                <div class="result-card safe">
                    <div class="result-header">
                        <div class="result-icon">✅</div>
                        <div class="result-info">
                            <div class="result-title">آمن غالبًا</div>
                            <div class="result-subtitle">لم يتم رصد مؤشرات احتيال</div>
                            <div class="risk-score">Risk Score: 12</div>
                        </div>
                    </div>

                    <div class="result-explanation">
                        الرابط تابع لنطاق موثوق ولا يحتوي على مؤشرات تصيد أو طلب بيانات حساسة.
                    </div>

                    <div class="warnings-section">
                        <div class="warnings-title">نصائح:</div>
                        <div class="warning-item">✔ تحقق دائمًا من اسم النطاق</div>
                        <div class="warning-item">✔ لا تشارك رمز التحقق</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Tips Panel -->
        <div class="tips-panel">
            <div class="info-box">
                <h3>🛡️ نصائح الأمان</h3>
                <ul>
                    <li>لا تضغط على روابط مجهولة</li>
                    <li>الجهات الرسمية لا تطلب بياناتك</li>
                    <li>تأكد من النطاق الرسمي للجهة</li>
                    <li>تنبه لا يطلب أي صلاحيات</li>
                </ul>
            </div>
        </div>

    </div>
</div>

<!-- JS -->
<script src="script.js"></script>

</body>
</html>
