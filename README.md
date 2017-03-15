# SMSBot
Medical SMS Bot

I am Medical SMS-Bot. I can help you to stay healthy and to reduce the risk of dangerous diseases! I can give you a health tip whenever you want one, I will also provide SMS reminders for regular health checkups for pregnant women, vaccination schedule for children and monthly health checkup reminders for people of all age groups!! So use /start to get started with this amazing journey!

## Requirements

beautifulsoup4==4.5.1
bs4==0.0.1
click==6.6
Flask==0.11.1
freeze==1.0.10
gunicorn==19.6.0
itsdangerous==0.24
Jinja2==2.8
MarkupSafe==0.23
requests==2.11.1
six==1.10.0
telepot==10.1
urllib3==1.19
virtualenv==15.0.3
Werkzeug==0.11.11
wikipedia==1.4.0
twilio==5.7.0
nexmo==1.4.0

## Build Setup

1. install requirements

  ```bash
  pip install -r requirements.txt
  ```
  ```bash
  pip insatll nexmo
  ```
  
2. run

  ```bash
  gunicorn app:app  
  # server at http://127.0.0.1:8000

## License

Medical SMS_Bot is licensed under [MIT](http://opensource.org/licenses/MIT)