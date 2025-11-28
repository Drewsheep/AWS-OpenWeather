# 🌥️ AWS Cloud - OpenWeather
Ennek a projektnek az a célja, hogy a felhasználók időjárás adatokat tudjanak lekérni egy adott városról. Ezeket az adatokat el is tudják menteni egy listába, ahol kedvük szerint törölhetik is azt. Az egész projekt a **felhő alapú infrastruktúrát / szolgáltatást** használ. Jó ötletnek találtuk, hogy a stílus is picit NJE-s legyen :)

## 🧩 Előkészítés (API)
 - Létrehozni egy **virtuális** környezetet -> `python -m venv .venv`
 - Ezt a környezetet aktiváli kell (pl. PowerShell-be) -> `.\.venv\Scripts\activate`
 - Majd telepíteni a Flasket -> `pip install flask`
 - Végül elindítani az alkalmazást -> `python app.py`

## 🧱 Felépítés
 - **Frontend (UI):** Webes felhasználói felület PHP-ben, NJE stílusban
 - **Backend (API):** Python (Flask) API, amely az időjárás adatokat biztosítja
 - **Felhő infrastruktúra:** AWS használata
 - **Adatbázis:** RDS (Relációs Adatbázis Szolgáltatás)

## 💡 Tulajdonságok
 - 🐍 **Python** (Flask) + 🐘 **PHP** alapú

 - 🌐 **VPC** használata `->` A rendszer teljesen izolált hálózaton fut, biztonságos adatkezeléssel

 - 🗄️ **RDS** használata `->` Az időjárás adatokat és a felhasználói beállításokat az Amazon RDS-ben tároljuk

 - 💻 **2 darab EC2** szolgáltatás használata `->` A backend és frontend különböző EC2 instanciákon futnak a nagyobb teljesítmény és biztonság érdekében

 - ⚖️ **Load Balancer** használata `->` A terhelés elosztásához az AWS Load Balancer biztosítja az optimális teljesítményt

 - 📈 **Auto Scaling Group** használata `->` Az alkalmazás képes automatikusan skálázódni a változó igényekhez

## 👤 Hogyan tudom megnézni az oldalt?
Az egész projekt elérhető és kipróbálható online a **`...`** oldalon.
 
### ℹ️ 2025/2026 - Felhőalapú szolgáltatások
 - © 2025 Baranyai András `AEN3WU` — Szabó Adrián Csaba `BZ8PAM` — Molnár Gergely `JMWZAL`