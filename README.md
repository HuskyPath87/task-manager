📝 Task Manager
🖥️ O projektu
Task Manager je webová aplikace postavená na frameworku Django, která umožňuje správu úkolů. Uživatelé mohou vytvářet, upravovat a mazat úkoly, přičemž aplikace poskytuje jednoduché a přehledné rozhraní. Tento projekt slouží jako praktická ukázka práce s Django, HTML/CSS, a databázemi v rámci CRUD operací.

✨ Funkce
✅ Přidávání, úprava a mazání úkolů
✅ Označení úkolu jako dokončeného
✅ Zobrazení seznamu úkolů v přehledném rozhraní
✅ Použití Django forms pro validaci dat
✅ Jednoduchý a uživatelsky přívětivý design

🛠️ Použité technologie
Python (Django framework)
HTML & CSS (šablony v Django)
SQLite (výchozí databáze v Django)
Bootstrap (pro základní stylování)
🚀 Jak projekt spustit
1️⃣ Naklonujte si repozitář

sh
Copy
Edit
git clone https://github.com/HuskyPath87/task-manager.git
cd task-manager
2️⃣ Vytvořte a aktivujte virtuální prostředí

sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # Na Windows: venv\Scripts\activate
3️⃣ Nainstalujte závislosti

sh
Copy
Edit
pip install -r requirements.txt
4️⃣ Proveďte migrace a spusťte aplikaci

sh
Copy
Edit
python manage.py migrate
python manage.py runserver
Aplikace poběží na http://127.0.0.1:8000/

📌 Plánované vylepšení
🔹 Přidání uživatelského přihlášení a správy uživatelů
🔹 Možnost třídění a filtrování úkolů
🔹 Lepší design pomocí Tailwind CSS nebo Bootstrap

📌 Pokud máš nějaké nápady nebo chceš přispět, budu ráda za jakýkoliv feedback! 😊
