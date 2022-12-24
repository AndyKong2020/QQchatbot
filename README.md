# QQchatbot
chatbot for QQ with openai api
# Requirements  
1. a linux host server
2. network which can visit worldwide internet
3. an openai api key
4. an extra qq acount
5. python3
# Quik Start  
1. Clone the code from github  
```git clone https://github.com/AndyKong2020/QQchatbot.git```
2. Install python requirements  
```cd ~/QQchatbot/py```  
```pip3 install -r requirements.txt```
3. Install cqhttp environment
```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```  
When be ask to choose, input 1.
4. Parameter Configurations  
In ```QQchatbot/py/config.json```, fill in your api-key, bot's qq id and your qq id.  
In ```QQchatbot/QBot/config.yml```, fill in bot's qq id and password.
5. Launch the program  
Input ```python py/QBot.py```in one terminal.  
Input ```cd QBot``` ```./go-cqhttp```in another terminal. When asked to choose, input 2, then scan the QRcode with bot's qq.
