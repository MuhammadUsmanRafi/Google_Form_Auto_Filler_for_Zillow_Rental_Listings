# Google_Form_Auto_Filler_for_Zillow_Rental_Listings

## 🏠 Google Form Auto-Filler for Zillow Rental Listings 📝

![GitHub](https://img.shields.io/github/license/USERNAME/REPO-NAME)
![Python](https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue)

Automate the process of filling a Google Form with rental property information scraped from Zillow. This Python script utilizes Selenium and BeautifulSoup to extract property details from Zillow's rental listings and then automatically populates a Google Form with the data. 🚀

### Features ✨

- **Effortless Data Collection**: Automatically gathers rental property details from Zillow with the help of Selenium and BeautifulSoup.
- **Customizable Search**: Easily modify the Zillow search URL to filter properties based on your preferences.
- **Seamless Integration**: Works with any Google Form, making it flexible for various use cases.
- **Fast and Efficient**: Automates the form-filling process for multiple listings with minimal user intervention.

### Prerequisites 📋

- Python 3.6 or above 🐍
- Chrome WebDriver (compatible with your Chrome browser version) 🌐
- Google Form link to be filled with scraped data (insert your Google Form link) 🔗

### Getting Started 🚀

1. Clone the repository to your local machine. 🔄
2. Install the required dependencies using `pip install -r requirements.txt`. 📦
3. Set the `GOOGLE_FORM_LINK` variable with your Google Form link. 🔗
4. Execute the script using `python main.py`. ▶️
5. Sit back and watch as the script collects data and fills the Google Form for you! 🍿

### How It Works 🛠️

1. The script fetches the Zillow rental listings page and extracts the HTML content. 🌐
2. BeautifulSoup is used to parse the HTML and extract property details such as addresses, prices, and links. 🕵️
3. The Chrome WebDriver is launched to open the Google Form and fill it with the scraped data. 🖥️
4. The process repeats for each property found on the Zillow page. 🔁

### Adding LinkedIn Video URL 📹

To see the entire working of this code and how it automates the form-filling process, check out the video on LinkedIn [here](INSERT_LINKEDIN_VIDEO_URL). 🎥

### Customize the Search 🔍

To customize the Zillow search, modify the `URL` variable in the script to match your preferred search criteria. The current URL filters rentals in Los Angeles, CA, with a maximum price of $872,627 and a maximum monthly payment of $3,000. 💡

### Legal Notice 📜

Please ensure you comply with Zillow's Terms of Service and Google Forms usage policies while using this script.

#### Disclaimer ⚠️

This project is intended for educational and personal use only. The developer is not responsible for any misuse or violation of third-party terms of service.

**Enjoy automating your Zillow rental property search with this convenient Google Form Auto-Filler!** 🏘️🔎
