# Trivia OCR
A bot to help answer questions on trivia apps like HQ and CashShow. This bot takes screenshot of the game on the phone and uses googles tesseract OCR to read the questions and options. It automates the process of googling of the answers and gives the most likely answer! It is 70%+ accurate!

Since it is against the policy of HQ-trivia i do not encourage anyone to use this during a live game and this is purely for educational purposes.

# Packages Used
Use python 3.6. In particular the packages/libraries used are...

* JSON - Data Storage
* Pillow - Image manipulation
* Google-Search-API - Google searching
* wikipediaapi - Wikipedia searches
* pytesseract - Google's free/open source OCR (requires seperate installtion)
* beautifulsoup4 - Parse google searches/html
* lxml - Beautifulsoup parser
* opencv2 - Image maniplulation
* pyscreenshot - Take screenshot of the game 
* wxPython - GUI interface

# Usage
Make sure all packages above are installed. For android phones use Vysor and for iOS use quicktime player. The code expects the phone to be on the left side of the screen. If you want to change the screenshot co-ordinates change the values inside the ImageGrab in the screen_grab() function. To use the script :
<pre>
$ git clone https://github.com/mrnoob69/trivia-ocr
$ cd trvia-ocr
$ pip3 install -r requirements.txt
$ python3 answer_bot.py
Press s to screenshot live game, sampq to run against sample questions or q to quit:
</pre>

# Useful links
* [Wikipedia-API](https://pypi.python.org/pypi/wikipedia)
* [Google-Search-API](https://github.com/abenassi/Google-Search-API)
* [Tesseract](https://github.com/tesseract-ocr/tesseract/wiki)

# License
The MIT License (MIT)
