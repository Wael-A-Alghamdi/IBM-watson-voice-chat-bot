* # مقدمة - Introduction

**في هذا المشروع قمت بإنشاء محادثة صوتية مع الروبوت**

*In this project I created a voice chat with a bot*


**(txt) اولا:التحدث الى الروبوت والتحويل من صوت الى نص وحفظ النص في ملف**

*First: Talk to the robot and convert from voice to text and save the text in a file (txt)*


**(mp3)ثانيا:الرد من الروبوت بالتحويل من نص الى صوت وحفظ الصوت ك**

*Second: Reply from the robot by converting from text to voice and saving the voice in (mp3)*



## 1.من خطاب إلى نص - From Speech to Text


**(Visual Studio Code) و (Python) و لغة (IBM Watson Speech to Text) قمت بإستعمال**

*I used (IBM Watson Speech to Text), (Python) and (Visual Studio Code)*



**في البداية يقوم الشخص بالتحدث و يقوم الكود بتحويل الصوت الى نص ثم بعد انتهاء الحديث**

**(output)اسم الملف(txt) يقوم بحفظ ما قاله الشخص في ملف**

*In the beginning, the person speaks and the code converts the audio into text, and then after the end of the conversation, it saves what the person said in a file (txt) file name (output)*


**ثم التحدث لمدة 10 ثواني و تستطيع تعديلها لأكثر او اقل (python transcribe.py -t 10) تقوم بكتابة**

*You type(python transcribe.py -t 10) and then speak for 10 seconds and you can edit it for more or less*


**ثم يقوم الكود بعد الانتهاء من الحديث في حفظه**

*Then the code after the completion of the conversation to save it*


**(txt) صور لتوضيح كود حفظ النص في ملف**

*Pictures to show the code to save the text in a file (txt)*


![](https://github.com/S0oos/IBM-watson-voice-chat-bot-internet-of-things-project-4/blob/main/Images/Screenshot_4.png)
****
![](https://github.com/S0oos/IBM-watson-voice-chat-bot-internet-of-things-project-4/blob/main/Images/Screenshot_3.png)
****
![](https://github.com/S0oos/IBM-watson-voice-chat-bot-internet-of-things-project-4/blob/main/Images/Screenshot_2.png)
****
![](https://github.com/S0oos/IBM-watson-voice-chat-bot-internet-of-things-project-4/blob/main/Images/Screenshot_1.png)

## 2.من نص إلى خطاب - From Text to Speech

**(Python)ولغة(IBM Watson Text to Speech)قمت بإستعمال**

**لسهولة عمل هذا الجزء عليه(Jupyter python)ولكن هنا قمت بإستعمال**

*I used (IBM Watson Text to Speech) and (Python) but here I used (Jupyter python) to make this part easier to work on*


**(winston) اسم ملف الصوت(mp3)يقوم الكود بتحويل النص (الرد على الشخص) الى صوت وحفظه ك**

*The code converts the text (responding to the person) to audio and saves it as (mp3) Audio file name (winston)*


**مكتوب داخل الكود وتحويله الى صوت كمثال بسيط (hello world) يقوم الكود في البداية في قراءة نص**

*The code initially reads a text (hello world) written inside the code and converts it to sound as a simple example*


**وتحويله الى صوت (example) هنا يقوم الكود في قراءة النص من ملف**

*Here the code reads the text from a file (example) and converts it to audio*







