# Currency-converter

![apps 22865 9007199266252124 f8447bb2-5880-4665-a0ff-e4384c0b5327](https://user-images.githubusercontent.com/75733364/107473973-875a2e00-6b97-11eb-813d-8618e6b8b3f8.jpg)


This currency converter is built in Python using exchange rates from Fixer.io API, in order to get updated currency rates.

Prerequisities :

- Python 3

- pip

Run instructions :

- Clone the repository

- pip install -r requirements.txt

- python currency_converter.py --amount (VALUE) --input_currency (VALUE) --output_currency (VALUE)

BASIC INSTRUCTIONS REGARDING THE RUNNING OF APPLICATION :

- The amount is the amount which we want to convert (float)

- The input and the output currencies are the currencies currently supported by the Fixer API. (AUD,BGN,BRL,CAD,CHF,CNY,CZK,DKK,GBP,HKD,HRK,HUF,IDR,ILS,INR,JPY,KRW,MXN,MYR,NOK,NZD,PHP,PLN,RON,RUB,SEK,SGD,THB,TRY,USD,ZAR)


Moreover, you can use the following symbols as input or output currencies :

  '€': 'EUR',
  'A$': 'AUD',
  'R$': 'BRL',
  'C$': 'CAD',
  'C¥': 'CNY',
  'Kč': 'CZK',
  'dkr': 'DKK',
  '£': 'GBP',
  'HK$': 'HKD',
  'kn': 'HRK',
  'Ft': 'HUF',
  'Rp': 'IDR',
  '₪': 'ILS',
  '₹': 'INR',
  'J¥': 'JPY',
  '₩': 'KRW',
  'Mex$': 'MXN',
  'RM': 'MYR',
  'NZ$': 'NZD',
  '₱': 'PHP',
  'zł': 'PLN',
  'lei': 'RON',
  '₽': 'RUB',
  'skr': 'SEK',
  'S$': 'SGD',
  '฿': 'THB',
  '₺': 'TRY',
  '$': 'USD',
  'R': 'ZAR',

THESE ARE THE COUNTRY CODES AND THEIR CURRENCY RATES :


        "AUD": 1.48949267,
        "BGN": 2.01843811,
        "BRL": 3.4990323299999995,
        "CAD": 1.44882945,
        "CHF": 1.10685932,
        "CNY": 7.5599074,
        "CZK": 27.8861244,
        "DKK": 7.6720818,
        "EUR": 1.0320044800000001,
        "GBP": 0.8839126999999999,
        "HKD": 8.4750995,
        "HRK": 7.8203892999999995,
        "HUF": 317.07604200000003,
        "IDR": 14605.3226,
        "ILS": 4.191817110000001,
        "INR": 74.29936099999999,
        "JPY": 126.76246499999999,
        "KRW": 1301.76234,
        "MXN": 23.2503016,
        "MYR": 4.88751411,
        "NOK": 9.2743421,
        "NZD": 1.5555569200000001,
        "PLN": 4.49463406,
        "RON": 4.6454223400000005,
        "RUB": 64.759144,
        "SEK": 9.8573254,
        "SGD": 1.5654800400000002,
        "THB": 38.9687394,
        "TRY": 3.95312293,
        "USD": 1.09278359,
        "ZAR": 14.8798263
   
