# 📝 Task Manager

Jednoduchá aplikace pro správu úkolů postavená na **Django** frameworku. Umožňuje vytvářet, upravovat a mazat úkoly s přehledným webovým rozhraním.

## 🚀 Funkce

- 🆕 Vytváření úkolů s názvem, popisem a stavem dokončení  
- ✏️ Úprava existujících úkolů  
- 🗑️ Odstraňování úkolů  
- 📅 Automatické ukládání data vytvoření úkolu  
- 💡 Uživatelsky přívětivé rozhraní  

## 🛠️ Použité technologie

- **Backend:** Django, Django ORM  
- **Frontend:** HTML, CSS, Bootstrap  
- **Databáze:** SQLite (možno nahradit PostgreSQL/MySQL)  

## 📥 Instalace a spuštění

1. Naklonuj si tento repozitář:
   ```sh
   git clone https://github.com/HuskyPath87/task-manager.git
   cd task-manager

2. Vytvoř a aktivuj virtuální prostředí:
   ```sh
   python -m venv venv
   source venv/bin/activate  # Na Windows: venv\Scripts\activate

3. Nainstaluj závislosti:
   ```sh
   pip install -r requirements.txt

5. Proveď migrace databáze:
   ```sh
   python manage.py migrate

7. Spusť lokální server:
   ```sh
   python manage.py runserver


