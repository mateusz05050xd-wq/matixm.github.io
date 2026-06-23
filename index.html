<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rekrutacja na Serwer</title>
    <style>
        :root {
            --bg-color: #36393f;
            --bg-dark: #202225;
            --bg-light: #40444b;
            --accent: #5865F2;
            --accent-hover: #4752C4;
            --text-main: #dcddde;
            --text-muted: #8e9297;
            --danger: #ed4245;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: var(--bg-dark);
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }

        header h1 { font-size: 1.5rem; color: #fff; }

        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            width: 100%;
        }

        .view { display: none; }
        .view.active { display: block; animation: fadeIn 0.3s; }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .card {
            background-color: var(--bg-dark);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        .card h2 { margin-bottom: 20px; color: #fff; text-align: center; }

        input, textarea, select {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            background-color: var(--bg-light);
            border: 1px solid #2f3136;
            color: #fff;
            border-radius: 4px;
            outline: none;
        }
        input:focus, textarea:focus { border-color: var(--accent); }

        button.primary-btn {
            width: 100%;
            background-color: var(--accent);
            color: #fff;
            border: none;
            padding: 12px;
            font-size: 1.1rem;
            border-radius: 4px;
            cursor: pointer;
            transition: 0.2s;
        }
        button.primary-btn:hover { background-color: var(--accent-hover); }
        button:disabled { background-color: var(--bg-light); cursor: not-allowed; }

        .rank-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }

        .rank-card {
            background-color: var(--bg-light);
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.2s;
            font-weight: bold;
            border: 2px solid transparent;
        }
        .rank-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent);
            background-color: #4f545c;
        }

        /* Kolory rang ze zdjęcia */
        .r-technik { color: #9b59b6; }
        .r-rekrutator { color: #3498db; }
        .r-grafik { color: #9b59b6; }
        .r-admin { color: #e74c3c; }
        .r-moderator { color: #2ecc71; }
        .r-helper { color: #3498db; }
        .r-chatmod { color: #2ecc71; }
        .r-budowniczy { color: #e67e22; }
        .r-tworca { color: #e84393; }
        
        .back-btn { background: transparent; color: var(--accent); border: none; cursor: pointer; margin-bottom: 20px; font-size: 1rem; }
    </style>
</head>
<body>

    <header>
        <h1>SerwerMC - Rekrutacja do Administracji</h1>
    </header>

    <div class="container">
        
        <div id="step-nick" class="view active">
            <div class="card">
                <h2>Witaj! Podaj swój nick</h2>
                <p style="text-align: center; margin-bottom: 20px; color: var(--text-muted);">Aby rozpocząć, wpisz swój dokładny nick z Discorda.</p>
                <input type="text" id="discord-nick" placeholder="Np. Bladex lub bladex#1234" required>
                <button class="primary-btn" onclick="saveNick()">Przejdź dalej</button>
            </div>
        </div>

        <div id="step-rank" class="view">
            <div class="card">
                <button class="back-btn" onclick="showView('step-nick')">← Powrót</button>
                <h2>Wybierz rangę, na którą aplikujesz</h2>
                <div class="rank-grid">
                    <div class="rank-card r-technik" onclick="selectRank('Technik')">🛠️ TECHNIK</div>
                    <div class="rank-card r-rekrutator" onclick="selectRank('Rekrutator')">📋 REKRUTATOR</div>
                    <div class="rank-card r-grafik" onclick="selectRank('Grafik')">🖼️ GRAFIK</div>
                    <div class="rank-card r-admin" onclick="selectRank('Admin')">🔴 ADMIN</div>
                    <div class="rank-card r-moderator" onclick="selectRank('Moderator')">🟢 MODERATOR</div>
                    <div class="rank-card r-helper" onclick="selectRank('Helper')">🔵 HELPER</div>
                    <div class="rank-card r-chatmod" onclick="selectRank('ChatMod')">💬 CHATMOD</div>
                    <div class="rank-card r-budowniczy" onclick="selectRank('Budowniczy')">🏗️ BUDOWNICZY</div>
                    <div class="rank-card r-tworca" onclick="selectRank('Twórca')">🎨 TWÓRCA</div>
                </div>
            </div>
        </div>

        <div id="step-form" class="view">
            <div class="card">
                <button class="back-btn" onclick="showView('step-rank')">← Zmień rangę</button>
                <h2 id="form-title">Aplikacja na rangę</h2>
                
                <form id="recruitment-form" onsubmit="submitForm(event)">
                    <label>Ile masz lat?</label>
                    <input type="number" id="q-age" placeholder="Wiek" required min="10" max="99">

                    <label>Czy posiadasz sprawny mikrofon?</label>
                    <select id="q-mic">
                        <option value="Tak">Tak</option>
                        <option value="Nie">Nie</option>
                    </select>

                    <label>Napisz coś o sobie (minimum 3 zdania):</label>
                    <textarea id="q-about" rows="3" placeholder="Opisz siebie..." required></textarea>

                    <label>Dlaczego myślisz, że nadajesz się na to stanowisko?</label>
                    <textarea id="q-why" rows="3" required></textarea>

                    <div id="specific-question-container"></div>

                    <button type="submit" id="submit-btn" class="primary-btn">Wyślij Aplikację na Discorda</button>
                </form>
            </div>
        </div>

        <div id="step-success" class="view">
            <div class="card" style="text-align: center;">
                <h2 style="color: #2ecc71;">Aplikacja Wysłana Pomyślnie!</h2>
                <p style="margin-top: 10px;">Twoje zgłoszenie trafiło bezpośrednio na nasz serwer Discord do weryfikacji właściciela.</p>
                <br>
                <button class="primary-btn" onclick="resetApp()">Wypełnij ponownie</button>
            </div>
        </div>

    </div>

    <script>
        // === TUTAJ WKLEJ LINK DO SWOJEGO WEBHOOKA Z DISCORDA ===
        const DISCORD_WEBHOOK_URL = "TUTAJ_WKLEJ_SWOJ_WEBHOOK_Z_DISCORDA";

        let currentNick = "";
        let currentRank = "";

        const specificQuestions = {
            'Technik': 'Jakie języki programowania/skryptowania znasz (Java, Skript) i co potrafisz zrobić?',
            'Rekrutator': 'Jakie kroki podjąłbyś podczas sprawdzania nowego kandydata na Helpera?',
            'Grafik': 'Wklej link do swojego portfolio (Imgur, Behance, Dysk Google):',
            'Admin': 'Jakie masz doświadczenie w zarządzaniu serwerem i bazami danych?',
            'Moderator': 'Gracz używa KillAury, a na serwerze nie ma Admina. Co robisz po kolei?',
            'Helper': 'Wymień 3 podstawowe komendy pomocnicze i opisz ich działanie:',
            'ChatMod': 'Dwóch graczy kłóci się na czacie publicznym używając wulgaryzmów. Twoja reakcja?',
            'Budowniczy': 'Wklej link do screenów swoich budowli i napisz w jakim stylu budujesz najlepiej:',
            'Twórca': 'Podaj link do swojego kanału (YouTube/TikTok/Twitch) oraz średnią ilość wyświetleń:'
        };

        function showView(viewId) {
            document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
            document.getElementById(viewId).classList.add('active');
        }

        function saveNick() {
            const nickInput = document.getElementById('discord-nick').value.trim();
            if (nickInput === "") {
                alert("Musisz podać swój nick!");
                return;
            }
            currentNick = nickInput;
            showView('step-rank');
        }

        function selectRank(rank) {
            currentRank = rank;
            document.getElementById('form-title').innerText = `Aplikacja na: ${rank}`;
            
            const specQ = specificQuestions[rank] || "Dodatkowe informacje:";
            document.getElementById('specific-question-container').innerHTML = `
                <label style="color: var(--accent); font-weight:bold; display:block; margin-top:15px;">Pytanie dedykowane dla rangi [ ${rank} ]:</label>
                <p style="font-size: 0.9em; margin-bottom:8px; color: var(--text-muted);">${specQ}</p>
                <textarea id="q-specific" rows="3" required></textarea>
            `;
            
            showView('step-form');
        }

        function submitForm(event) {
            event.preventDefault();
            
            const submitBtn = document.getElementById('submit-btn');
            submitBtn.innerText = "Wysyłanie...";
            submitBtn.disabled = true;

            const age = document.getElementById('q-age').value;
            const mic = document.getElementById('q-mic').value;
            const about = document.getElementById('q-about').value;
            const why = document.getElementById('q-why').value;
            const specific = document.getElementById('q-specific').value;

            // Przygotowanie ładnej wiadomości do wysłania na Discorda w formie tzw. Embed
            const discordMessage = {
                username: "System Rekrutacji Serwera",
                avatar_url: "https://i.imgur.com/wSTFkRM.png",
                embeds: [{
                    title: `📝 NOWE PODANIE NA RANGĘ: ${currentRank.toUpperCase()}`,
                    color: 5814783, // Kolor paska (Discord Blurple)
                    fields: [
                        { name: "👤 Nick z Discorda", value: currentNick, inline: true },
                        { name: "🎂 Wiek", value: age, inline: true },
                        { name: "🎙️ Sprawny Mikrofon", value: mic, inline: true },
                        { name: "📖 O sobie", value: about },
                        { name: "❓ Dlaczego on/ona", value: why },
                        { name: `🛠️ Pytanie dodatkowe (${currentRank})`, value: specific }
                    ],
                    footer: { text: "BladexMC Rekrutacja" },
                    timestamp: new Date()
                }]
            };

            // Wysyłanie danych przez Webhook
            fetch(DISCORD_WEBHOOK_URL, {
                method: "POST",
                headers: { "Content-Type": "application/json" },
                body: JSON.stringify(discordMessage)
            })
            .then(response => {
                if (response.ok) {
                    document.getElementById('recruitment-form').reset();
                    showView('step-success');
                } else {
                    alert("Wystąpił błąd podczas wysyłania na Discord. Sprawdź poprawność URL Webhooka.");
                }
            })
            .catch(error => {
                console.error("Błąd:", error);
                alert("Nie udało się nawiązać połączenia. Upewnij się, że wpisałeś poprawny Webhook.");
            })
            .finally(() => {
                submitBtn.innerText = "Wyślij Aplikację";
                submitBtn.disabled = false;
            });
        }

        function resetApp() {
            currentNick = "";
            currentRank = "";
            document.getElementById('discord-nick').value = "";
            showView('step-nick');
        }
    </script>
</body>
</html>
