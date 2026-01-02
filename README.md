# **Geogramint - инструмент геолокации OSINT для Telegram**
<p align="center">
<img src="https://github.com/Alb-310/Geogramint/blob/master/appfiles/Geogramint.png" width="300"/>
</p>

<p align="center"> <img src="https://img.shields.io/badge/version-1.4-orange" /> <img src="https://img.shields.io/badge/PYTHON-03b1fc?style=for-the-badge&logo=python"/> <a href="https://github.com/Alb-310"> <img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/><a/> <a href="https://twitter.com/Alb_310"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/by-alb310.svg"/><a/> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg"/>
<p align="center"> <a href="https://projetfox.com/"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/fox%20badge.png" width="200"/> <a/>

## The End : 06/09/2025


Павел Дуров, основатель и генеральный директор Telegram, объявил о прекращении работы функции "Люди рядом". Функция не работала в течение недели.

<p align="center"> <img src="https://github.com/user-attachments/assets/6315894f-7e31-4599-83e9-2e0f70f86ee5" width="400"/>

# [Telegram](https://t.me/fradyrad)
# [SOFT на PYTHON](https://t.me/python_softs)
# [КВОРК-KWORK](https://kwork.ru/user/sleadgenrator)
# [НАПИСАТЬ МНЕ В TELEGRAM](https://t.me/fradyrad)


Удаление этой функции означает, что Geogramint и другие инструменты OSINT, использующие API, больше не работают. С сегодняшнего дня этот репозиторий на GitHub будет заархивирован.

Популярность Geogramint началась с [этой статьи на Projet FOX] (https://projetfox.com/en/2022/08/geogramint-an-osint-geolocalization-tool-for-telegram/), в которой возможности этого инструмента были продемонстрированы в действии. Это также было продемонстрировано на Международном форуме по кибербезопасности (FIC) в Лилле, Франция, в 2023 году, что привело к появлению этой статьи [на Projet FOX](https://projetfox.com/en/2023/07/osint-russian-military-presence-in-belarus/).

Geogramint использовали многие журналисты, исследователи, практики OSINT и другие. Я лично хочу поблагодарить всех, кто пользовался этим инструментом, и надеюсь, что Geogramint был полезен в ваших расследованиях!

<p align="right">
<b>- Alb310
</b></p>

<p align="center">
<a href="https://twitter.com/Alb_310">Twitter @Alb_310</a> | 
<a href="https://projetfox.com/">Projet FOX's Website</a> | 
<a href="https://twitter.com/ProjetFOX">Twitter @ProjetFOX</a> | 
<a href="https://discord.com/invite/nxffsWBNRK">Projet FOX's Discord</a> | 
<a href="https://www.linkedin.com/company/projetfox">Projet FOX's LinkedIn</a>
</p>

## **О программе**

Geogramint - это инструмент OSINT, который использует API Telegram для поиска близлежащих пользователей и групп. Он создан на основе [Карты близлежащих пользователей Telegram от Tejado] (https://github.com/tejado/telegram-nearby-map), которая больше не поддерживается, и призван предоставить более удобную альтернативу.

Geogramint находит только тех пользователей и группы Telegram, у которых активирована функция поиска поблизости. По умолчанию она отключена.

Инструмент полностью поддерживается в Windows и частично в дистрибутивах Mac OS и Linux.

<p align="center"> <img src="https://github.com/user-attachments/assets/9b06b204-b23e-4014-a84c-e4188e4d38cb" />

## 🛠️ Installation

**Requirements:** [Python 3.9, 3.10 or 3.11](https://www.python.org/downloads/release/python-3112/)<br>

### On Windows [![Windows](https://img.shields.io/badge/Windows-03b1fc?style=for-the-badge&logo=windows)](https://svgshare.com/i/ZhY.svg)

+ #### With the installer: Click [here!](https://github.com/Alb-310/Geogramint/releases)
+ #### With Github:
```bash
git clone https://github.com/Alb-310/Geogramint.git
cd Geogramint/
pip3 install -r requirements.txt

python3 geogramint.py # for GUI mode
python3 geogramint.py --help # for CLI mode
```
Or depending on your installation :
```bash
git clone https://github.com/Alb-310/Geogramint.git
cd Geogramint/
pip install -r requirements.txt

python geogramint.py # for GUI mode
python geogramint.py --help # for CLI mode
```

### On Mac OS  ![macOS](https://img.shields.io/badge/Mac_OS-abbfc7?style=for-the-badge&logo=apple) and Linux ![Linux](https://img.shields.io/badge/Linux-ffffff?style=for-the-badge&logo=linux)

+ #### With Github:
```bash
git clone https://github.com/Alb-310/Geogramint.git
cd Geogramint/
pip3 install -r requirements.txt

python3 geogramint.py # for GUI mode
python3 geogramint.py --help # for CLI mode
```
Or depending on your installation :
```bash
git clone https://github.com/Alb-310/Geogramint.git
cd Geogramint/
pip install -r requirements.txt

python geogramint.py # for GUI mode
python geogramint.py --help # for CLI mode
```

More details in the [Wiki](https://github.com/Alb-310/Geogramint/wiki/Installation-Guide).


## 📡 Example: GUI

1. Start by creating an API key for your Telegram account [here](https://my.telegram.org). You will also need to put a profile picture on your account and, in your `Privacy and Security` settings, enable the profile picture for everyone.

<p align="center"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/privacy_settings.jpg" width="300"/>

2. Launch **Geogramint**
3. In the settings, write your information (api_id, api_hash and phone number), report preference and then `save`

<p align="center"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/Geogramint_settings_1.png" width="500"/> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/Geogramint_settings_2.png" width="500"/>

4. Choose the location where you want to search, either by moving around the map or by using the search feature with coordinates in `lat, lon` format

<p align="center"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/Geogramint_search.png" width="700"/>

5. Telegram will send you a verification code, write it in the pop-up window (+ your two-step verification password if you have one)

<p align="center"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/Geogramint_code.png" width="700"/>

6. Then click `Start Search`
7. All results will be displayed following: 
+ green for 500m
+ yellow for 1000m
+ orange for 2000m
+ red for >3000m

(NB: results can also be found in `Geogramint/cache_telegram/` in `json` and `csv` format + profiles pictures)

<p align="center"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/Geogramint_results.png" width="700"/>

8. `Reset` will clear the results and erase the `cache_telegram`

More details in the [Wiki](https://github.com/Alb-310/Geogramint/wiki/Demonstration:-GUI).

## 📡 Example: CLI

1. Start by creating an API key for your Telegram account [here](https://my.telegram.org). You will also need to put a profile picture on your account and, in your `Privacy and Security` settings, enable the profile picture for everyone.

<p align="center"> <img src="https://github.com/Alb-310/Geogramint/blob/master/.github/privacy_settings.jpg" width="300"/>

2. Launch **Geogramint**

![image](https://user-images.githubusercontent.com/52386954/210659094-506e3018-6784-4602-bf4e-e446534f6f15.png)

3. Start with the config, with the command `set-config` set your information (api_id, api_hash and phone number)

![image](https://user-images.githubusercontent.com/52386954/210659472-dbb1804e-dd8a-468e-b0a1-bfcd77652113.png)

4. Start the search feature by using coordinates in `lat lon` format with the command `start-scan` :

![image](https://user-images.githubusercontent.com/52386954/210659762-4fffc2ac-957d-4377-9615-d339dcb17aef.png)

 <p align="center"> <img src="https://user-images.githubusercontent.com/52386954/210661716-9a3db8c7-4627-447e-b18b-dcf2c8c54a36.png" width="500"/>
  <p align="center"> ⬇ </p>
  
<p align="center"> <img src="https://user-images.githubusercontent.com/52386954/210661742-7e7a6242-5915-4b0e-a52d-38d4dd779eff.png" width="500"/>
 
5. All results will be displayed following: 
+ green for 500m
+ yellow for 1000m
+ orange for 2000m
+ red for >3000m

(NB: results can be exported depending options used with `start-scan`, by default profile pictures and results in `json` format are present in `Geogramint/cache_telegram/`)

6. `reset-scan` will clear `cache_telegram`

More details in the [Wiki](https://github.com/Alb-310/Geogramint/wiki/Demonstration:-CLI).
  
## 📖 Wiki

Remember to check the [Wiki](https://github.com/Alb-310/Geogramint/wiki) before posting an issue or asking a question.

## 📝 License

[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.fr.html)

## 🙏 Thanks to:
+ My teammates at Projet FOX
+ # [Telegram](https://t.me/fradyrad)
# [SOFT на PYTHON](https://t.me/python_softs)
# [КВОРК-KWORK](https://kwork.ru/user/sleadgenrator)
# [НАПИСАТЬ МНЕ В TELEGRAM](https://t.me/fradyrad)

