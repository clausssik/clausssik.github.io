<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="assets/index.css">
    <link rel="icon" type="image/x-icon" href="https://play-lh.googleusercontent.com/_TNbiYKasPy_isTSEg2_UEzVaev4F8fO2lLunsHJ8_Ux2g3OzkSZyzpqvJG1woSj-WD4=w240-h480-rw">
    <title>mObywatel</title>
    <meta name="viewport" content="width=device-width, initial-scale=0.8, user-scalable=no">
</head>
<body>
    <img src="https://play-lh.googleusercontent.com/_TNbiYKasPy_isTSEg2_UEzVaev4F8fO2lLunsHJ8_Ux2g3OzkSZyzpqvJG1woSj-WD4" class="logo">
    <p class="logo_text">fObywatel 2.0</p>

    <p class="warning">Ta strona jest darmowa, uważaj na oszustów sprzedających ją. Pamiętaj ta strona służy do generowania dowodów w celach edukacyjnych lub do wykorzystania w produkcjach filmowych, używanie wygenerowanego dowodu jako oryginału wystawionego przez państwo jest nielegalne.</p>

    <div class="guide_holder">
        <div class="top_holder">
            <p class="guide_title">Instrukcja</p>
            <img class="arrow" src="https://i.imgur.com/aUZmu0W.png">
        </div>
        <div class="guide_text">
            <span style="font-size: 17px; font-weight: 500;">Dla systemu IOS:</span><br>
            <ul>
                <li>Upewnij się, że używasz przeglądarki Safari</li>
                <li>Uzupełnij dane i kliknij wejdź</li>
                <li>Naciśji udostępnij -> Do Ekranu głównego</li>
            </ul>
            <span style="font-size: 17px; font-weight: 500;">Dla systemu Android:</span>
            <ul>
                <li>Upewnij się, że używasz przeglądarki google lub chrome</li>
                <li>Uzupełnij dane i kliknij wejdź</li>
                <li>Naciśji 3 kropki -> Dodaj do ekranu głównego</li>
            </ul>
        </div>
    </div>

    <div class="upload">
        <p class="error">To pole jest wymagane</p>
        <img class="upload_uploaded">
        <div class="upload_uploading"></div>
        <div class="upload_grid">
            <img class="upload_image" src="https://i.imgur.com/vwIQErh.png">
            <p class="upload_text">Dodaj zdjęcie</p>
        </div>
    </div>

    <div class="input_holder">
        <input type="text" id="name" class="input" placeholder="">
        <span class="placeholder">Imię (imiona)</span>
        <p class="error">To pole jest wymagane</p>
    </div>
 
    <div class="input_holder">
        <input type="text" id="surname" class="input" placeholder="">
        <span class="placeholder">Nazwisko</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <p class="top_info">Płeć</p>
    <div class="selector_box">
        <div class="selected_grid">
            <p class="selector_text selected_text">Mężczyzna</p>
            <img class="selected_arrow" src="https://i.imgur.com/RXsdBB6.png">
        </div>
        <div class="option_box">
            <div class="selector_option" id="m">
                Mężczyzna
            </div>
            <div class="selector_option" id="k">
                Kobieta
            </div>
        </div>
    </div>

    <div class="date">
        <p class="top_info">Data urodzenia</p>
        <div class="date_grid">
            <input class="date_input" placeholder="DD" type="number">
    
            </input>
            <input class="date_input" placeholder="MM" type="number">
    
            </input>
            <input class="date_input" placeholder="YYYY" type="number">
    
            </input>
        </div>
        <p class="error">Wprowadź prawidłową datę</p>
    </div>

    <div class="input_holder">
        <input type="text" id="nationality" class="input" placeholder="">
        <span class="placeholder">Obywatelstwo</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="familyName" class="input" placeholder="">
        <span class="placeholder">Nazwisko rodowe</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="fathersFamilyName" class="input" placeholder="">
        <span class="placeholder">Nazwisko rodowe ojca</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="mothersFamilyName" class="input" placeholder="">
        <span class="placeholder">Nazwisko rodowe matki</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <p class="subtext">Miejsce zamieszkania</p>

    <div class="input_holder">
        <input type="text" id="birthPlace" class="input" placeholder="">
        <span class="placeholder">Miejsce urodzenia</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="countryOfBirth" class="input" placeholder="">
        <span class="placeholder">Kraj urodzenia</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="adress1" class="input" placeholder="">
        <span class="placeholder">Ulica i numer domu</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="adress2" class="input" placeholder="">
        <span class="placeholder">Kod pocztowy</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="city" class="input" placeholder="">
        <span class="placeholder">Miasto</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <a class="go">wejdź</a>
    <div class="discord" onclick="window.open('https://discord.gg/EDg7A8sWqm')">
        <div class="inner_grid">
            <img class="discord_image" src="https://i.imgur.com/eie0S0W.png">
            <p class="discord_text">Dołącz do naszego discorda</p>
        </div>
    </div>

    <script src="assets/index.js"></script>
    <script src="assets/manifest.js"></script>
</body>
