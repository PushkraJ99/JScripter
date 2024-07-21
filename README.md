## JScripter - A Noob-Friendly JavaScript Scraper!
JScripter is a Python script designed to scrape and save unique JavaScript files from a list of URLs or a single URL.

## Disclaimer

> This tool is intended only for educational purposes and for testing in corporate environments. https://twitter.com/nav1n0x/ and https://github.com/ifconfig-me take no responsibility for the misuse of this code. Use it at your own risk. Do not attack a target you don't have permission to engage with.

Feelfee to fork and make this script your own :)
 

## Features

- Scrape JavaScript files from multiple URLs concurrently using threading.
- Save unique JavaScript files to a specified directory and - Print confirmation.
- Removed duplicate JSFiles
- Display detailed progress information, including the number of URLs processed, elapsed time, and approximate remaining time.
- Silent mode for minimal output.

## Screenshots
### Single URL Mode:
![image](https://github.com/user-attachments/assets/adc50477-0352-4208-9b9c-22f617859faf)

### Multi-urls Mode
![image](https://github.com/user-attachments/assets/0a35f788-3e9b-40d8-bf54-7a926df3d776)

### Deduplicates Automativally:
![image](https://github.com/user-attachments/assets/df056d65-7384-4b8c-aa9c-d78e422cef85)

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `colorama` library
- `tqdm` library

You can install the required libraries using pip:

```
pip install requests beautifulsoup4 colorama tqdm
```

## 📥 Installation
To Install `JScripter`, Follow These Steps:

```sh
git clone https://github.com/PushkraJ99/JScripter
cd JScripter
pip3 install requirements.txt
python3 JScripter.py -h
```

2. Ensure that gaulus, hakrawler, and ffuf are installed and accessible from the command line.
To Install `gaulus, hakrawler, and ffuf`, Follow These Steps:
```sh
go install github.com/bp0lr/gauplus@latest
```

```sh
go install github.com/hakluke/hakrawler@latest
```

```sh
go install github.com/ffuf/ffuf@latest
```

## Usage

### From a List of URLs
1. Create a file containing the list of target URLs (e.g., urls.txt).
2. Run the script:

```python3 JScripter.py -f urls.txt -d saved_js_files -t 10```

### From a Single URL
1. Run the script with a single URL:
```python3 JScripter.py -u https://example.com -d saved_js_files -t 10```

## Command-Line Arguments
* -f, --file: File containing list of target URLs.
* -u, --url: Single target URL.
* -d, --directory: Directory to save unique JavaScript files (required).
* -s, --silent: Silent mode. No banner, no progress, only URLs.
* -t, --threads: Number of threads to use for concurrent processing (default is 5).

## 🤝 Contributing
Contributions are Welcome! If you'd like to Contribute to `JScripter` Please Follow These Steps

1. Fork the Repository.
2. Create a New Branch.
3. Make Your Changes and Commit them.
4. Submit a Pull Request.

---

### 🫣 Author 
[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ifconfig-me)

---

### 🥷🏻 UPGRADED BY :) 
[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PushkraJ99)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/follow?screen_name=PushkraJ99) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pushkaraj-dhuri/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/you_are_not_goodlooking_but_he)

---
### 🤗 JUST 4 FUN
### ✨ Stargazers
[![Stargazers repo roster for @PushkraJ99/JScripter](https://reporoster.com/stars/dark/notext/PushkraJ99/JScripter)](https://github.com/PushkraJ99/JScripter/stargazers)

### ☢️ Forkers 
[![Forkers repo roster for @PushkraJ99/JScripter](https://reporoster.com/forks/dark/notext/PushkraJ99/JScripter)](https://github.com/PushkraJ99/JScripter/network/members)

## 🐍 [Snake4Readme](https://github.com/PushkraJ99/Snake4Readme)

<p align="center">
<img src="https://github.com/PushkraJ99/Snake4Readme/blob/main/Snake4Readme/grid-snake.svg">
</p><br>

[![](https://visitcount.itsvg.in/api?id=PushkraJ99&icon=8&color=12)](https://visitcount.itsvg.in)

<p align="center"> 
  <b> Visitor Count </b><br>
  <img src="https://profile-counter.glitch.me/PushkraJ99/count.svg" />
</p><br>
