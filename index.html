<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Gateway</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #00a0e9;
            --secondary: #0077b6;
            --dark: #121212;
            --darker: #0a0a0a;
            --light: #e0e0e0;
            --lighter: #f5f5f5;
            --success: #4bb543;
            --card-bg: #1e1e1e;
            --border: #333;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--dark);
            color: var(--light);
            line-height: 1.6;
        }
        
        .container {
            max-width: 600px;
            margin: 40px auto;
            padding: 25px;
            background: var(--darker);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            border: 1px solid var(--border);
            animation: fadeInUp 0.6s ease-out;
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
            animation: fadeIn 0.8s ease-in;
        }
        
        .header h1 {
            color: var(--primary);
            font-size: 2.2rem;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(0, 160, 233, 0.3);
        }
        
        .header p {
            color: #aaa;
        }
        
        .payment-method {
            margin: 25px 0;
            padding: 20px;
            border-radius: 10px;
            background: var(--card-bg);
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
            border: 1px solid var(--border);
            animation: slideIn 0.5s ease-out forwards;
            opacity: 0;
            transform: translateY(20px);
        }
        
        .payment-method:nth-child(2) {
            animation-delay: 0.2s;
        }
        
        .payment-method:nth-child(3) {
            animation-delay: 0.4s;
        }
        
        .payment-method:hover {
            transform: translateY(-5px) scale(1.01);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        .method-header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .method-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            margin-right: 15px;
            box-shadow: 0 0 10px rgba(0, 160, 233, 0.3);
            transition: all 0.3s ease;
        }
        
        .payment-method:hover .method-icon {
            transform: rotate(15deg) scale(1.1);
            box-shadow: 0 0 20px rgba(0, 160, 233, 0.5);
        }
        
        .method-title {
            font-size: 1.3rem;
            font-weight: 600;
            color: var(--lighter);
            transition: all 0.3s ease;
        }
        
        .payment-method:hover .method-title {
            color: var(--primary);
            text-shadow: 0 0 8px rgba(0, 160, 233, 0.2);
        }
        
        .qr-container {
            text-align: center;
            margin: 20px 0;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        
        .qr-code {
            max-width: 250px;
            border-radius: 10px;
            border: 1px solid var(--border);
            padding: 10px;
            background: white;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            filter: drop-shadow(0 5px 5px rgba(0, 0, 0, 0.1));
        }
        
        .qr-container:hover .qr-code {
            transform: scale(1.05);
            box-shadow: 0 0 25px rgba(0, 160, 233, 0.3);
            filter: drop-shadow(0 10px 10px rgba(0, 160, 233, 0.2));
        }
        
        .qr-container p {
            margin-top: 10px;
            color: #aaa;
            transition: all 0.3s ease;
        }
        
        .qr-container:hover p {
            color: var(--primary);
        }
        
        .copy-box {
            display: flex;
            align-items: center;
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 10px 15px;
            margin: 15px 0;
            transition: all 0.3s ease;
        }
        
        .payment-method:hover .copy-box {
            border-color: var(--primary);
            box-shadow: 0 0 15px rgba(0, 160, 233, 0.1);
        }
        
        .copy-input {
            flex: 1;
            border: none;
            outline: none;
            font-size: 1rem;
            font-weight: 500;
            color: var(--lighter);
            background: transparent;
        }
        
        .copy-btn {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: 500;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
        }
        
        .copy-btn::after {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: all 0.5s ease;
        }
        
        .copy-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 15px rgba(0, 160, 233, 0.3);
        }
        
        .copy-btn:hover::after {
            left: 100%;
        }
        
        .copy-btn i {
            margin-right: 5px;
            transition: all 0.3s ease;
        }
        
        .copy-btn:hover i {
            transform: scale(1.2);
        }
        
        .instructions {
            margin-top: 20px;
            padding: 15px;
            background: rgba(30, 30, 30, 0.7);
            border-radius: 8px;
            font-size: 0.9rem;
            border: 1px solid var(--border);
            transition: all 0.3s ease;
        }
        
        .payment-method:hover .instructions {
            border-color: var(--primary);
        }
        
        .instructions h4 {
            color: var(--primary);
            margin-bottom: 10px;
            transition: all 0.3s ease;
        }
        
        .payment-method:hover .instructions h4 {
            transform: translateX(5px);
        }
        
        .instructions ol {
            padding-left: 20px;
        }
        
        .instructions li {
            margin-bottom: 8px;
            color: #ccc;
            transition: all 0.3s ease;
            position: relative;
            padding-left: 10px;
        }
        
        .instructions li::before {
            content: '';
            position: absolute;
            left: 0;
            top: 8px;
            width: 5px;
            height: 5px;
            background: var(--primary);
            border-radius: 50%;
            opacity: 0;
            transition: all 0.3s ease;
        }
        
        .payment-method:hover .instructions li {
            color: var(--light);
            padding-left: 15px;
        }
        
        .payment-method:hover .instructions li::before {
            opacity: 1;
            left: 5px;
        }
        
        .success-message {
            display: none;
            background: var(--success);
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            margin-top: 10px;
            animation: fadeIn 0.5s, bounceIn 0.5s;
        }
        
        /* Modal QR Code */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(5px);
            animation: fadeIn 0.3s;
        }
        
        .modal-content {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
            animation: zoomIn 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        
        .modal-qr {
            max-width: 80%;
            max-height: 80%;
            border-radius: 15px;
            border: 2px solid var(--primary);
            box-shadow: 0 0 30px rgba(0, 160, 233, 0.5);
            transform-origin: center;
        }
        
        .close-modal {
            position: absolute;
            top: 20px;
            right: 30px;
            color: white;
            font-size: 35px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        
        .close-modal:hover {
            color: var(--primary);
            transform: rotate(90deg) scale(1.1);
            text-shadow: 0 0 15px rgba(0, 160, 233, 0.7);
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #666;
            font-size: 0.9rem;
            animation: fadeIn 1s ease-in;
        }
        
        /* Keyframe Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes slideIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes zoomIn {
            from {
                transform: scale(0.8);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }
        
        @keyframes bounceIn {
            0% {
                transform: scale(0.8);
                opacity: 0;
            }
            50% {
                transform: scale(1.05);
                opacity: 1;
            }
            70% {
                transform: scale(0.95);
            }
            100% {
                transform: scale(1);
            }
        }
        
        @keyframes pulse {
            0% {
                box-shadow: 0 0 0 0 rgba(0, 160, 233, 0.4);
            }
            70% {
                box-shadow: 0 0 0 10px rgba(0, 160, 233, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(0, 160, 233, 0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Payment</h1>
            <p>Pilih metode pembayaran yang tersedia</p>
        </div>
        
        <div class="payment-method">
            <div class="method-header">
                <div class="method-icon">
                    <i class="fas fa-qrcode"></i>
                </div>
                <div class="method-title">QRIS Payment</div>
            </div>
            
            <div class="qr-container" onclick="openModal()">
                <img src="https://j.top4top.io/p_3476gf73r1.jpg" alt="QR Code" class="qr-code">
                <p>Klik QR Code untuk memperbesar</p>
            </div>
        </div>
        
        <div class="payment-method">
            <div class="method-header">
                <div class="method-icon">
                    <i class="fab fa-d-and-d"></i>
                </div>
                <div class="method-title">DANA Transfer</div>
            </div>
            
            <p>Salin nomor DANA di bawah ini dan transfer sesuai nominal pembayaran Anda:</p>
            
            <div class="copy-box">
                <input type="text" value="082245535288" id="dana-number" class="copy-input" readonly>
                <button class="copy-btn" onclick="copyToClipboard()">
                    <i class="fas fa-copy"></i> Salin
                </button>
            </div>
            
            <div id="success-msg" class="success-message">
                Nomor berhasil disalin!
            </div>
            
            <div class="instructions">
                <h4>Petunjuk Pembayaran:</h4>
                <ol>
                    <li>Salin nomor DANA di atas</li>
                    <li>Buka aplikasi DANA di perangkat Anda</li>
                    <li>Pilih menu "Kirim" dan tempelkan nomor tujuan</li>
                    <li>Masukkan nominal pembayaran dan konfirmasi</li>
                    <li>Screenshot bukti transfer dan kirim ke admin</li>
                </ol>
            </div>
        </div>
        
        <div class="footer">
            <p>&copy; 2025 Rendzz Official Payment Gateway. All rights reserved.</p>
        </div>
    </div>
    
    <!-- Modal QR Code -->
    <div id="qrModal" class="modal">
        <span class="close-modal" onclick="closeModal()">&times;</span>
        <div class="modal-content">
            <img src="https://j.top4top.io/p_3476gf73r1.jpg" alt="QR Code" class="modal-qr">
        </div>
    </div>
    
    <script>
        function copyToClipboard() {
            const copyText = document.getElementById("dana-number");
            copyText.select();
            copyText.setSelectionRange(0, 99999);
            navigator.clipboard.writeText(copyText.value);
            
            const successMsg = document.getElementById("success-msg");
            successMsg.style.display = "block";
            
            setTimeout(() => {
                successMsg.style.display = "none";
            }, 2000);
        }
        
        // Modal QR Code functions
        function openModal() {
            document.getElementById("qrModal").style.display = "block";
            document.body.style.overflow = "hidden";
        }
        
        function closeModal() {
            const modal = document.getElementById("qrModal");
            modal.style.animation = "fadeIn 0.3s reverse";
            setTimeout(() => {
                modal.style.display = "none";
                modal.style.animation = "fadeIn 0.3s";
                document.body.style.overflow = "auto";
            }, 300);
        }
        
        // Close modal when clicking outside
        window.onclick = function(event) {
            const modal = document.getElementById("qrModal");
            if (event.target == modal) {
                closeModal();
            }
        }
        
        // Add pulse animation to payment methods periodically
        setInterval(() => {
            const methods = document.querySelectorAll('.payment-method');
            methods.forEach((method, index) => {
                setTimeout(() => {
                    method.style.animation = "pulse 1.5s";
                    setTimeout(() => {
                        method.style.animation = "";
                    }, 1500);
                }, index * 500);
            });
        }, 10000);
    </script>
</body>
</html>
