<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JunMoods PROXY - Authentication</title>
    <link rel="stylesheet" href="css/14cc0e81_all.min.css">
    <script src="js/a11f23d3_api.js" async defer></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }

        body {
            background-color: #000000;
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            background-image: 
                radial-gradient(circle at 50% 0%, rgba(139, 92, 246, 0.15) 0%, transparent 70%),
                radial-gradient(circle at 50% 100%, rgba(59, 130, 246, 0.1) 0%, transparent 70%);
        }

        nav {
            padding: 20px 32px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            background: rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(12px);
        }

        .brand {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .brand img {
            width: 36px;
            height: 36px;
            object-fit: contain;
            filter: drop-shadow(0 0 8px rgba(139, 92, 246, 0.6));
        }

        .brand-title {
            font-size: 16px;
            font-weight: 800;
            letter-spacing: 0.05em;
            background: linear-gradient(135deg, #ffffff 0%, #a855f7 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
        }

        .admin-btn {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            padding: 8px 16px;
            color: #a1a1aa;
            font-size: 13px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            gap: 6px;
            backdrop-filter: blur(4px);
        }

        .admin-btn:hover {
            background: rgba(168, 85, 247, 0.15);
            border-color: rgba(168, 85, 247, 0.3);
            color: #ffffff;
            box-shadow: 0 0 20px rgba(168, 85, 247, 0.15);
        }

        main {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 40px 20px;
        }

        .card {
            background: rgba(10, 10, 12, 0.8);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 20px;
            padding: 36px;
            width: 100%;
            max-width: 440px;
            box-shadow: 
                0 0 50px -10px rgba(139, 92, 246, 0.15),
                inset 0 0 20px rgba(255, 255, 255, 0.02);
            backdrop-filter: blur(20px);
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, transparent, #a855f7, transparent);
            animation: scanline 4s infinite;
        }

        @keyframes scanline {
            0% { left: -100%; }
            50%, 100% { left: 100%; }
        }

        .card-header {
            text-align: center;
            margin-bottom: 28px;
        }

        .logo-wrapper {
            width: 72px;
            height: 72px;
            background: rgba(168, 85, 247, 0.08);
            border: 1px solid rgba(168, 85, 247, 0.2);
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 16px;
            box-shadow: 0 0 20px rgba(168, 85, 247, 0.2);
        }

        .logo-wrapper img {
            width: 50px;
            height: 50px;
            object-fit: contain;
        }

        .card-header h2 {
            font-size: 20px;
            font-weight: 700;
            color: #ffffff;
            margin-bottom: 6px;
        }

        .card-header p {
            font-size: 13px;
            color: #71717a;
        }

        .input-group {
            position: relative;
            margin-bottom: 20px;
        }

        .input-icon {
            position: absolute;
            left: 14px;
            top: 50%;
            transform: translateY(-50%);
            color: #52525b;
            display: flex;
            align-items: center;
        }

        input {
            width: 100%;
            padding: 14px 14px 14px 44px;
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 12px;
            color: #ffffff;
            font-size: 14px;
            outline: none;
            transition: all 0.2s ease;
        }

        input:focus {
            border-color: #a855f7;
            background: rgba(255, 255, 255, 0.05);
            box-shadow: 0 0 16px rgba(168, 85, 247, 0.2);
        }

        .cf-turnstile {
            display: flex;
            justify-content: center;
            margin: 16px 0 12px 0;
        }

        .btn-submit {
            width: 100%;
            padding: 14px;
            background: linear-gradient(135deg, #9333ea 0%, #4f46e5 100%);
            color: #ffffff;
            border: none;
            border-radius: 12px;
            font-size: 14px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            box-shadow: 0 4px 20px rgba(147, 51, 234, 0.3);
            margin-bottom: 12px;
        }

        .btn-submit:hover {
            opacity: 0.95;
            transform: translateY(-1px);
            box-shadow: 0 6px 24px rgba(147, 51, 234, 0.4);
        }

        .btn-submit:active {
            transform: translateY(0);
        }

        .btn-submit:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none !important;
        }

        .action-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        .btn-secondary {
            padding: 12px;
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 12px;
            color: #e4e4e7;
            font-size: 13px;
            font-weight: 600;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            transition: all 0.2s ease;
            cursor: pointer;
        }

        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.08);
            border-color: rgba(255, 255, 255, 0.15);
            color: #ffffff;
        }

        .btn-wa:hover {
            border-color: rgba(34, 197, 94, 0.4);
            color: #4ade80;
        }

        .alert {
            margin-top: 20px;
            padding: 12px 16px;
            border-radius: 10px;
            font-size: 13px;
            display: none;
            align-items: center;
            gap: 10px;
        }

        .alert-success {
            background: rgba(34, 197, 94, 0.1);
            color: #4ade80;
            border: 1px solid rgba(34, 197, 94, 0.2);
        }

        .alert-error {
            background: rgba(239, 68, 68, 0.1);
            color: #fca5a5;
            border: 1px solid rgba(239, 68, 68, 0.2);
        }

        footer {
            padding: 20px;
            text-align: center;
            font-size: 12px;
            color: #3f3f46;
            border-top: 1px solid rgba(255, 255, 255, 0.03);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 6px;
        }

        .spinner {
            display: inline-block;
            width: 16px;
            height: 16px;
            border: 2px solid rgba(255,255,255,0.3);
            border-radius: 50%;
            border-top-color: #fff;
            animation: spin 0.8s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }
    </style>
</head>
<body>

    <nav>
        <div class="brand">
            <img src="lib/logo.png" alt="Logo">
            <span class="brand-title">JunMoods PROXY</span>
        </div>

    </nav>

    <main>
        <div class="card">
            <div class="card-header">
                <div class="logo-wrapper">
                    <img src="lib/logo.png" alt="Logo">
                </div>
                <h2>VIP License Key</h2>
                <p>Enter your key to unlock proxy access</p>
            </div>

            <div class="input-group">
                <div class="input-icon">
                    <i class="fa-solid fa-key"></i>
                </div>
                <input type="text" id="keyInput" placeholder="JUNN-XXXX-XXXX" autocomplete="off">
            </div>



            <button class="btn-submit" id="btnVerify" onclick="verifyKey()">
                <i class="fa-solid fa-shield-halved"></i>
                <span>Activate Key</span>
                <i class="fa-solid fa-arrow-right-to-bracket"></i>
            </button>

            <button class="btn-submit" id="btnGetKey" onclick="generateKeyLink()" style="background: linear-gradient(135deg, #059669 0%, #10b981 100%); box-shadow: 0 4px 20px rgba(16, 185, 129, 0.3);">
                <i class="fa-solid fa-coins"></i>
                <span>Get Free Key (Shortlink)</span>
                <i class="fa-solid fa-arrow-up-right-from-square"></i>
            </button>

            <div class="action-grid">
                <a href="https://whatsapp.com/channel/0029VbBnIVuCMY0POm5gqO1P" target="_blank" class="btn-secondary">
                    <i class="fa-brands fa-whatsapp"></i>
                    <span>Channel</span>
                </a>
                <a href="https://chat.whatsapp.com/CBFdnAwAuQu5r2zXbNGPdS?s=cl&p=a&ilr=1" target="_blank" class="btn-secondary btn-wa">
                    <i class="fa-solid fa-users"></i>
                    <span>WA Group</span>
                </a>
            </div>
            <div class="cf-turnstile" data-sitekey="0x4AAAAAAEl52Dpa8qj3i8hN" data-theme="dark"></div>
            <div id="alertBox" class="alert"></div>
        </div>
    </main>

    <footer>
        <i class="fa-regular fa-copyright"></i>
        <span>2026 JunMoods PROXY. All rights reserved.</span>
    </footer>

    <script>
        window.addEventListener('DOMContentLoaded', () => {
            const isLoggedIn = localStorage.getItem('user_vip_key');
            const loginTime = localStorage.getItem('login_time');
            
            if (isLoggedIn && loginTime) {
                const now = Date.now();
                const expired = parseInt(loginTime) + (24 * 60 * 60 * 1000);
                if (now < expired) {
                    window.location.href = '/jun/official/home.html';
                    return;
                } else {
                    localStorage.removeItem('user_vip_key');
                    localStorage.removeItem('login_time');
                }
            }

            const savedKey = localStorage.getItem('user_vip_key');
            if (savedKey) {
                document.getElementById('keyInput').value = savedKey;
            }
        });

        function checkAdBlock() {
            return new Promise((resolve) => {
                const bait = document.createElement('div');
                bait.className = 'adsbygoogle ad-zone ad-space pub_300x250';
                bait.style.cssText = 'position:absolute; top:-9999px; left:-9999px; width:1px; height:1px;';
                document.body.appendChild(bait);

                setTimeout(() => {
                    const isBlocked = window.getComputedStyle(bait).getPropertyValue('display') === 'none' || 
                                      bait.offsetParent === null || 
                                      bait.offsetHeight === 0 || 
                                      bait.offsetWidth === 0;
                    
                    if (document.body.contains(bait)) {
                        document.body.removeChild(bait);
                    }
                    
                    resolve(isBlocked);
                }, 100);
            });
        }

        async function verifyKey() {
            const keyInput = document.getElementById('keyInput');
            const alertBox = document.getElementById('alertBox');
            const btn = document.getElementById('btnVerify');
            const btnText = btn.querySelector('span');
            const key = keyInput.value.trim();

            const turnstileWidget = document.querySelector('.cf-turnstile');
            const tokenInput = turnstileWidget ? turnstileWidget.querySelector('[name="cf-turnstile-response"]') : null;
            const token = tokenInput ? tokenInput.value : '';

            if (!key) {
                showAlert('Please enter your license key!', 'error', 'fa-triangle-exclamation');
                if (typeof turnstile !== 'undefined') turnstile.reset();
                return;
            }

            if (!token) {
                showAlert('Please complete the verification!', 'error', 'fa-triangle-exclamation');
                return;
            }

            btn.disabled = true;
            btn.style.opacity = '0.6';
            btnText.innerHTML = '<span class="spinner"></span> Verifying...';
            alertBox.style.display = 'none';

            try {
                const response = await fetch('/api/verify_key', {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({ 
                        key: key,
                        turnstile_token: token
                    })
                });

                const result = await response.json();

                if (result.code === 0) {
                    localStorage.setItem('user_vip_key', key);
                    localStorage.setItem('login_time', Date.now().toString());
                    
                    showAlert('Access Granted! Redirecting to dashboard...', 'success', 'fa-circle-check');
                    setTimeout(() => {
                        window.location.href = '/jun/official/home.html';
                    }, 1500);
                } else {
                    showAlert(result.message || 'Invalid license key!', 'error', 'fa-circle-xmark');
                    if (typeof turnstile !== 'undefined') turnstile.reset();
                }
            } catch (err) {
                showAlert('Failed to connect to proxy server!', 'error', 'fa-wifi');
                if (typeof turnstile !== 'undefined') turnstile.reset();
            } finally {
                btn.disabled = false;
                btn.style.opacity = '1';
                btnText.innerHTML = 'Activate Key';
            }
        }

        async function generateKeyLink() {
            const btn = document.getElementById('btnGetKey');
            const btnText = btn.querySelector('span');

            btn.disabled = true;
            btn.style.opacity = '0.6';
            btnText.innerHTML = '<span class="spinner"></span> Checking Network...';

            const isAdBlockActive = await checkAdBlock();
            if (isAdBlockActive) {
                showAlert('Private DNS / AdBlock detected! Please disable any Custom DNS or AdBlocker in your phone settings to claim key.', 'error', 'fa-shield-virus');
                btn.disabled = false;
                btn.style.opacity = '1';
                btnText.innerHTML = 'Get Free Key (Shortlink)';
                return;
            }

            btnText.innerHTML = '<span class="spinner"></span> Generating Link...';

            try {
                const response = await fetch('/api/generate_shortlink', {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' }
                });

                const result = await response.json();

                if (result.code === 0 && result.shortlink) {
                    window.location.href = result.shortlink;
                } else {
                    showAlert(result.message || 'Failed to generate shortlink', 'error', 'fa-triangle-exclamation');
                }
            } catch (err) {
                showAlert('Connection error to shortlink service', 'error', 'fa-wifi');
            } finally {
                btn.disabled = false;
                btn.style.opacity = '1';
                btnText.innerHTML = 'Get Free Key (Shortlink)';
            }
        }

        function showAlert(msg, type, iconClass) {
            const alertBox = document.getElementById('alertBox');
            alertBox.innerHTML = `<i class="fa-solid ${iconClass}"></i> <span>${msg}</span>`;
            alertBox.className = 'alert alert-' + type;
            alertBox.style.display = 'flex';
        }
    </script>

</body>
</html>