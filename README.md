# ZENMAP-Multi-Scan-Without-Graphical-Interface

🛡️ Zenmap Scan Automation Tool (Python Skripti)
Bu Python skripti, Zenmap/Nmap alətini istifadə edərək fərqli skan metodlarını tez və rahat şəkildə icra etməyə imkan verir. Skript terminal üzərindən interaktiv seçimlərlə işləyir və nmap əmrlərini avtomatik olaraq yerinə yetirir.

📌 Tələblər
Linux/MacOS və ya Nmap quraşdırılmış Windows

nmap aləti (sudo apt install nmap ilə quraşdırıla bilər)

Python 3

⚙️ İstifadə Qaydası
Terminalı açın və skriptin olduğu qovluğa keçin.

Aşağıdakı əmrlə skripti işə salın:

bash
Copy
Edit
python3 zenmap_script.py
Skan rejimlərindən birini seçin:

--quick – Sürətli skan

--intense – Ətraflı və intensiv skan

--intense-all – Bütün portlar üzrə intensiv skan

--ping-scan – Şəbəkədə aktiv hostların yoxlanması

--quick-plus – Sürətli + versiya + OS skanı

IP ünvanı daxil edin və nəticələri izləyin.

⚠️ Qeyd
Əgər nmap sisteminizdə quraşdırılmayıbsa, əvvəlcə onu quraşdırmalısınız.

Əmrlər sisteminizdə sudo icazəsi tələb edə bilər.

🇬🇧 English Version
🛡️ Zenmap Scan Automation Tool (Python Script)
This Python script helps you automate various Zenmap/Nmap scan operations via terminal. It provides an interactive CLI for launching different types of scans quickly.

📌 Requirements
Linux/MacOS or Windows with Nmap installed

nmap tool (install with sudo apt install nmap)

Python 3

⚙️ How to Use
Open terminal and navigate to the folder containing the script.

Run the script with:

bash
Copy
Edit
python3 zenmap_script.py
Choose a scan mode:

--quick – Quick scan

--intense – Intense scan

--intense-all – All ports intense scan

--ping-scan – Ping scan to detect live hosts

--quick-plus – Quick + version + OS detection scan

Enter the target IP address when prompted.

⚠️ Notes
If nmap is not installed, please install it before running the script.

Some scan commands may require sudo privileges depending on your OS and configuration.

