- 👋 Hi, I’m @sig-kika
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
sig-kika/sig-kika is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Обчислення площі трикутника</title>
    <script>
        function calculateArea() {
            const base = parseFloat(document.getElementById("base").value);
            const height = parseFloat(document.getElementById("height").value);
            
            if (isNaN(base) || isNaN(height) || base <= 0 || height <= 0) {
                alert("Будь ласка, введіть коректні значення для основи та висоти!");
                return;
            }
            
            const area = 0.5 * base * height;
            document.getElementById("area").value = area;
        }
    </script>
</head>
<body>
    <h2>Обчислення площі прямокутного трикутника</h2>
    <div>
        <label>Основа: <input type="number" id="base" placeholder="Введіть основу"></label><br><br>
        <label>Висота: <input type="number" id="height" placeholder="Введіть висоту"></label><br><br>
        <button onclick="calculateArea()">Обчислити</button>
    </div>
    <div>
        <label>Площа: <input type="text" id="area" readonly></label>
    </div>
<
  /body>
</html>
