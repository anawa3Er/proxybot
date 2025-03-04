#Proxy List Grabber

Description

This Python script automates the process of scraping proxy lists from the internet using Selenium and Firefox. It collects fresh proxy IPs that can be used for various purposes, such as web scraping, security testing, and anonymity.

Requirements

To run this script, ensure you have the following dependencies installed:

Python 3.x

Selenium (pip install selenium)

Firefox Web Browser

GeckoDriver (Download from Mozilla GeckoDriver and add it to your system PATH)

Installation

Clone the repository:

git clone https://github.com/anawa3Er/proxybot/
cd pproxybot

Install required Python dependencies:

pip install -r requirements.txt

Ensure that Firefox and GeckoDriver are properly installed and accessible from the system's PATH.

Usage

Run the script using the following command:

python proxy_scraper.py

The script will scrape proxies and save them to a file or display them in the terminal (depending on your implementation).

Output

The grabbed proxy list will be saved in a file named proxies.txt (or as specified in your script).

Notes

Ensure that your GeckoDriver version matches your Firefox browser version.

If running on a server, make sure you use a headless browser mode to avoid UI-related issues.

Some websites may block scraping activities, so consider implementing proxy rotation if needed.

License

This project is open-source and available under the MIT License.

Author

Created by benayad
Contributions

Feel free to submit pull requests or report issues to improve the project!
