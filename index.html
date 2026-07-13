<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Мой сайт</title>
</head>
<body>

    <!-- Секция входа -->
    <div id="auth-section">
        <h1>Вход</h1>
        <button id="login-btn">Войти через Google</button>
    </div>

    <!-- Секция профиля (показывается после входа) -->
    <div id="profile-section" style="display:none;">
        <h1>Твой аккаунт</h1>
        <p id="user-info"></p>
        <button id="logout-btn">Выйти</button>
    </div>

    <!-- Подключаем Firebase через модули -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/9.22.1/firebase-app.js";
        import { getAuth, signInWithPopup, GoogleAuthProvider, signOut, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/9.22.1/firebase-auth.js";

        // Твоя конфигурация
        const firebaseConfig = {
            apiKey: "AIzaSyBI0_cJasOJZYKtycOlhLuwwSc2h5buznc",
            authDomain: "my-sait-c7862.firebaseapp.com",
            projectId: "my-sait-c7862",
            storageBucket: "my-sait-c7862.firebasestorage.app",
            messagingSenderId: "921533837162",
            appId: "1:921533837162:web:b642c0692f8401e8bb3f13"
        };

        const app = initializeApp(firebaseConfig);
        const auth = getAuth();
        const provider = new GoogleAuthProvider();

        // Элементы
        const loginBtn = document.getElementById('login-btn');
        const logoutBtn = document.getElementById('logout-btn');
        const authSection = document.getElementById('auth-section');
        const profileSection = document.getElementById('profile-section');
        const userInfo = document.getElementById('user-info');

        // Логика входа
        loginBtn.onclick = () => signInWithPopup(auth, provider);
        logoutBtn.onclick = () => signOut(auth);

        // Проверка состояния
        onAuthStateChanged(auth, (user) => {
            if (user) {
                authSection.style.display = 'none';
                profileSection.style.display = 'block';
                userInfo.innerText = `Почта: ${user.email}`;
            } else {
                authSection.style.display = 'block';
                profileSection.style.display = 'none';
            }
        });
    </script>
</body>
</html>
