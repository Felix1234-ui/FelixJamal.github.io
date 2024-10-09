<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        @keyframes shake {
            0% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            50% { transform: translateX(5px); }
            75% { transform: translateX(-5px); }
            100% { transform: translateX(0); }
        }

        @keyframes backgroundShake {
            0% { transform: translate(0); }
            25% { transform: translate(2px, 2px); }
            50% { transform: translate(-2px, -2px); }
            75% { transform: translate(2px, -2px); }
            100% { transform: translate(0); }
        }

        body {
            font-family: Arial, sans-serif;
            background-image: url('https://files.catbox.moe/0bu7an.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: white;
            position: relative;
            overflow: hidden; /* Menyembunyikan bagian salju yang keluar dari area */
            animation: backgroundShake 10s infinite alternate; /* Menambahkan animasi goyang pada background */
        }

        .login-container {
            background-color: rgba(0, 0, 0, 0.8); /* Hitam transparan */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(255, 0, 0, 0.6); /* Efek bayangan merah */
        }
        .login-container h2 {
            margin-bottom: 20px;
            text-align: center;
            color: #ff4d4d; /* Warna merah */
        }
        .login-container input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ff4d4d; /* Garis merah */
            border-radius: 5px;
            background-color: #333; /* Latar belakang abu gelap */
            color: white;
        }
        .login-container input::placeholder {
            color: #aaa;
        }
        .login-container button {
            width: 100%;
            padding: 10px;
            background-color: #ff4d4d; /* Tombol merah */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .login-container button:hover {
            background-color: #e60000; /* Warna merah lebih tua saat hover */
        }
        .error {
            color: #ff4d4d;
            text-align: center;
        }

        /* Tambahkan kelas shake untuk animasi */
        .shake {
            animation: shake 0.5s ease;
        }

        /* Watermark di bagian bawah */
        .watermark {
            position: absolute;
            bottom: 10px;
            right: 10px;
            font-size: 12px;
            color: rgba(255, 255, 255, 0.6); /* Warna putih dengan sedikit transparansi */
        }

        /* CSS untuk efek salju */
        .snow {
            position: absolute;
            top: -10%;
            width: 100%;
            pointer-events: none; /* Agar tidak mengganggu interaksi dengan elemen lain */
        }

        .snowflake {
            position: absolute;
            background: #ff4d4d; /* Warna merah untuk salju */
            border-radius: 50%;
            opacity: 0.8;
            animation: fall linear infinite;
        }

        @keyframes fall {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(100vh);
            }
        }
    </style>
</head>
<body>

    <div class="snow" id="snow-container"></div>

    <div class="login-container" id="login-container">
        <h2>Login to Roblox</h2>
        <div class="error" id="error-message"></div>
        <input type="text" id="username" placeholder="Username">
        <input type="password" id="password" placeholder="Password">
        <button onclick="login()">Login</button>
    </div>

    <!-- Watermark di bagian bawah -->
    <div class="watermark">Panel by Felix</div>

    <!-- Elemen audio untuk bunyi saat password salah -->
    <audio id="error-sound" src="https://files.catbox.moe/ovzrlt.mp3"></audio>

    <script>
        // Fungsi untuk membuat salju
        function createSnowflakes() {
            const snowContainer = document.getElementById('snow-container');

            for (let i = 0; i < 50; i++) { // Mengatur jumlah salju yang jatuh
                const snowflake = document.createElement('div');
                snowflake.classList.add('snowflake');
                snowflake.style.width = `${Math.random() * 10 + 5}px`; // Lebar acak
                snowflake.style.height = snowflake.style.width; // Tinggi sama dengan lebar
                snowflake.style.left = `${Math.random() * 100}vw`; // Posisi horizontal acak
                snowflake.style.animationDuration = `${Math.random() * 3 + 2}s`; // Durasi jatuh acak
                snowflake.style.animationDelay = `${Math.random() * 5}s`; // Penundaan jatuh acak
                snowContainer.appendChild(snowflake);
            }
        }

        // Memanggil fungsi untuk membuat salju
        createSnowflakes();

        function login() {
            var username = document.getElementById('username').value;
            var password = document.getElementById('password').value;
            var errorMessage = document.getElementById('error-message');
            var loginContainer = document.getElementById('login-container');
            var errorSound = document.getElementById('error-sound'); // Ambil elemen audio

            // Validasi untuk dua username
            if ((username === 'hafis' && password === 'Anjayani') || 
                (username === 'diwa' && password === 'kokp')) {
                window.location.href = 'https://www.roblox.com';
            } else {
                errorMessage.textContent = 'Username tidak tersedia atau password salah!';
                errorSound.play(); // Mainkan bunyi saat password salah
                loginContainer.classList.add('shake'); // Tambahkan kelas shake

                // Hapus animasi shake setelah selesai
                setTimeout(function() {
                    loginContainer.classList.remove('shake');
                }, 500); // Durasi animasi shake 0.5 detik
            }
        }
    </script>

</body>
</html>
