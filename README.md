### 1. Название и краткое описание  
Название: Игра "Поле Чудес" (Wheel of Fortune)  
Описание:  
Это консольная версия популярной игры "Поле Чудес", где игроку нужно угадать слово по буквам или целиком. Игра поддерживает русские и английские слова, а также предоставляет дополнительные команды для удобства.  

Title: Wheel of Fortune Game  
Description:  
This is a console version of the popular "Wheel of Fortune" game where the player needs to guess a word letter by letter or entirely. The game supports both Russian and English words and provides additional commands for convenience.  

---

### 2. Правила игры  
- Игроку предлагается угадать слово, скрытое за звёздочками.  
- Можно вводить буквы по одной или слово целиком.  
- Если буква есть в слове, она открывается во всех позициях.  
- Если буквы нет, игрок получает сообщение об ошибке.  
- Можно использовать команды для получения подсказок или сдачи.  

Game Rules:  
- The player needs to guess a word hidden behind asterisks.  
- You can input letters one by one or the whole word.  
- If a letter is in the word, it is revealed in all positions.  
- If the letter is not in the word, the player gets an error message.  
- Additional commands are available for hints or surrendering.  

---

### 3. Описание механизма игры глазами игрока  
1. Игра начинается с вывода загаданного слова в виде звёздочек (например, ****).  
2. Игрок вводит букву или слово.  
3. Если буква угадана правильно, она открывается в слове (например, С***).  
4. Если слово введено целиком и верно, игра завершается победой.  
5. Можно использовать команды (/HELP, /STOP и др.) для управления игрой.  

Player's Perspective:  
1. The game starts by displaying the hidden word as asterisks (e.g., ****).  
2. The player inputs a letter or the whole word.  
3. If the letter is correct, it appears in the word (e.g., C***).  
4. If the entire word is guessed correctly, the game ends with a victory.  
5. Commands (/HELP, /STOP, etc.) can be used for game control.  

---

### 4. Возможности игры  
- Поддержка двух языков: русские и английские слова.  
- Команды:  
  - /HELP – правила игры.  
  - /STOP – завершить игру.  
  - /VVOD – показать введённые буквы.  
  - /OST – показать оставшиеся буквы алфавита.  
- Неограниченное число попыток.  

Features:  
- Dual-language support: Russian and English words.  
- Commands:  
  - /HELP – show game rules.  
  - /STOP – quit the game.  
  - /VVOD – show entered letters.  
  - /OST – show remaining letters.  
- Unlimited attempts.  

---

### 5. Алгоритм игры (программная логика)  
1. Загружается список слов, выбирается случайное слово.  
2. Создаётся "загадка" (****).  
3. В цикле обрабатывается ввод игрока:  
   - Если буква: проверяется наличие в слове, открывается.  
   - Если команда: выполняется соответствующее действие.  
   - Если слово: проверяется на совпадение.  
4. Игра завершается при угадывании слова или команде /STOP.  

Game Algorithm:  
1. A word list is loaded, a random word is selected.  
2. A hidden version (****) is created.  
3. Player input is processed in a loop:  
   - If a letter: check if it's in the word, reveal it.  
   - If a command: execute the action.  
   - If a word: check for a match.  
4. The game ends when the word is guessed or /STOP is used.  

---

### Технологии и особенности  
- Язык: Python  
- Используемые модули: random  
- Особенности:  
  - Поддержка двух языков в словах.  
  - Интерактивные команды для удобства.  

Technologies & Features:  
- Language: Python  
- Modules: random  
- Key features:  
  - Dual-language word support.  
  - Interactive commands for better UX.
