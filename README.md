#ДАННЫЙ РЕПОЗИТОРИЙ ЯВЛЯЕТСЯ ФОРКОМ ДРУГОГО РЕПОЗИТОРИЯ!
#THIS REPOSITORY IS A FORK OF ANOTHER REPOSITORY!
# log4jminecraft
EN/ENG: This code *DOES NOT* promote or encourage any illegal activities!
The content in this document is provided solely for educational purposes and to create awareness!

Watch a video showing the process here: https://youtu.be/efnluUK_w_U

This PDF shows you how to setup a Minecraft server for this demonstration: https://davidbombal.wiki/minecraftw11log4j

To run this project follow the following steps:
1. Clone the repository: 
```git clone https://github.com/davidbombal/log4jminecraft.git```
3. Run the script log4j.py (```python3 log4j.py <ip_address>``` i.e. ```python3 log4j.py 192.168.1.132```). This installs the prerequisite software, and also starts up the LDAP server.
4. Run the script jcomp_pyserv.py (```python3 jcomp_pyserv.py```). This compiles the Java payload to be ran, and also starts a python3 http.server. 
#RU/RU: Этот код и репозиторий *НЕ* пропагандирует и не поощряет незаконную деятельность!
Содержимое этого документа предоставлено исключительно в образовательных целях и для повышения осведомленности!

Посмотрите видео, показывающее процесс здесь: https://youtu.be/efnluUK_w_U

В этом PDF-файле показано, как настроить сервер Minecraft для этой демонстрации: https://davidbombal.wiki/minecraftw11log4j.

Чтобы запустить этот проект, выполните следующие шаги:
1. Клонируйте репозиторий:
```Клон git https://github.com/davidbombal/log4jminecraft.git```
3. Запустите скрипт log4j.py (```python3 log4j.py <ip_address>```, т.е. ```python3 log4j.py 192.168.1.132```). При этом будет установлено необходимое программное обеспечение, а также запущен сервер LDAP.
4. Запустите сценарий jcomp_pyserv.py (```python3 jcomp_pyserv.py```). При этом компилируются полезные данные Java для запуска, а также запускается http.server python3.
# Acknowledgement for contributions: 
* John Hammond : https://youtu.be/7qoPDq41xhQ
* Moritz Bechler (For creating the Java Unmarshaller Security - MarshalSec) : https://github.com/mbechler/marshalsec
* xiajun325 for clear instruction on how to use the MarshalSec tool : https://github.com/xiajun325/apache-log4j-rce-poc
