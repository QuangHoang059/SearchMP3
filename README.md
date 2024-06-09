# DemoMP3

## Install Environment

1. Install Nodejs.
2. Install Python
3. Install ffmpeg
4. Install Mysql or use Mysql in Azure for database.

## Run app

1. Git clone

```
git clone https://github.com/QuangHoang059/SearchMP3
```

2. Config connect database in fingerprinting\dejavu.cnf.SAMPLE
3. Install lib of python

```
pip install -r requirements.txt
```

4. Initial Database

```
python fingerprinting\\dejavu.py  --fingerprint ..\\public\\music mp3
```

5. Install lib of nodejs

```
npm install
```

6. Start

```
npm start
```
