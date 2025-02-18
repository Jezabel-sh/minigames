# 🎮 Python Mini-Games Collection

<div align="center">
    <input type="radio" id="tab1" name="tabs" checked>
    <label for="tab1">🇬🇧 English</label>
    
    <input type="radio" id="tab2" name="tabs">
    <label for="tab2">🇪🇸 Español</label>
    
    <div id="content1">
        <h2>📌 Games Included</h2>

        ### 1️⃣ The Infernal Dungeon (`mazmorra.py`)
        A text-based adventure game where you help Naruto navigate through a dark dungeon to take the perfect Instagram photo.  
        Make decisions, collect items, and face challenges along the way!

        - ⭐ Interactive text-based story.
        - ⚔️ Different choices affect the outcome.
        - 🐉 Face a powerful dragon at the end!

        ### 2️⃣ Wordle Clone (`wordle.py`)
        Try to guess the secret 5-letter word in 6 attempts or less. Letters will give you hints:
        ✅ Correct letter in the correct position.  
        ❎ Correct letter in the wrong position.

        - 🧠 Random words every time you play.
        - ⌛ Limited attempts to guess the word.
        - 🏆 Win by finding the word before you run out of tries!

        ### 3️⃣ Rock, Paper, Scissors (`ppt.py`)
        A simple game where you play "Rock, Paper, Scissors" against the computer in a best-of-three match.

        - 🪨 Rock beats Scissors.
        - 📄 Paper beats Rock.
        - ✂️ Scissors beat Paper.

        ## 🚀 How to Play
        1. Make sure you have Python installed on your system.
        2. Download or clone this repository.
        3. Run any of the games using the command:
           ```sh
           python3 mazmorra.py
           python3 wordle.py
           python3 ppt.py
           ```

        ## 📜 License
        These games are open-source. Feel free to modify and improve them!
    </div>

    <div id="content2">
        <h2>📌 Juegos Incluidos</h2>

        ### 1️⃣ La Mazmorra Infernal (`mazmorra.py`)
        Un juego de aventuras basado en texto donde ayudas a Naruto a recorrer una mazmorra oscura para tomar la foto perfecta para Instagram.  
        ¡Toma decisiones, recolecta objetos y enfréntate a desafíos en el camino!

        - ⭐ Historia interactiva basada en texto.
        - ⚔️ Diferentes elecciones afectan el resultado.
        - 🐉 ¡Enfréntate a un poderoso dragón al final!

        ### 2️⃣ Clon de Wordle (`wordle.py`)
        Intenta adivinar la palabra secreta de 5 letras en 6 intentos o menos. Las letras te darán pistas:  
        ✅ Letra correcta en la posición correcta.  
        ❎ Letra correcta en la posición incorrecta.

        - 🧠 Palabras aleatorias en cada partida.
        - ⌛ Intentos limitados para adivinar la palabra.
        - 🏆 ¡Gana encontrando la palabra antes de quedarte sin intentos!

        ### 3️⃣ Piedra, Papel o Tijera (`ppt.py`)
        Un simple juego donde juegas "Piedra, Papel o Tijera" contra la computadora en una partida al mejor de tres.

        - 🪨 Piedra gana a Tijeras.
        - 📄 Papel gana a Piedra.
        - ✂️ Tijeras ganan a Papel.

        ## 🚀 Cómo Jugar
        1. Asegúrate de tener Python instalado en tu sistema.
        2. Descarga o clona este repositorio.
        3. Ejecuta cualquiera de los juegos con el comando:
           ```sh
           python3 mazmorra.py
           python3 wordle.py
           python3 ppt.py
           ```

        ## 📜 Licencia
        Estos juegos son de código abierto. ¡Siéntete libre de modificarlos y mejorarlos!
    </div>
</div>

<style>
    input[name="tabs"] { display: none; }
    label { 
        cursor: pointer; 
        padding: 10px 20px; 
        background: #f5b31d; 
        border-radius: 5px;
        margin-right: 10px;
        font-weight: bold;
    }
    div[id^="content"] { display: none; padding: 20px; border-top: 3px solid #1b3652; }
    input#tab1:checked ~ #content1, input#tab2:checked ~ #content2 { display: block; }
</style>
