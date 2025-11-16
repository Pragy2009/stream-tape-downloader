# Streamtape Direct Download Link Scraper

## Overview

This Python script extracts direct download links from [Streamtape](https://streamtape.com/) video URLs. It automates the retrieval of hidden download links and tokens, making downloads from Streamtape easier for personal use.

---

## Features

- Automatically converts `/e/` URLs to `/v/` format.
- Scrapes and parses hidden download link and token from the Streamtape video page.
- Returns an easy-to-use direct download URL.

---

## Requirements

**Python 3.x** and the following packages:

- `requests`
- `beautifulsoup4`

Install them using:

pip install requests beautifulsoup4

---

## Usage

1. **Copy the script** to your Python environment.
2. **Replace** the value of `video_url` with your desired Streamtape video link.
3. **Run:**

python streamtape_scraper.py

4. The script prints the direct download link if successfully extracted.

---

## Example

video_url = "https://streamtape.com/v/abc123xyz" # Your Streamtape video URL

download_link = steamtape_get_dl_link(video_url)

if download_link:
print("Download link:", download_link)
else:
print("Failed to retrieve the download link.")


---

## Notes

- Script is for educational/personal use.
- May break if Streamtape site changes its structure or protection mechanisms.
- Does **not** bypass CAPTCHA or anti-bot features.

---

## License

MIT License

---

## Disclaimer

This project is not affiliated with Streamtape. Do not use it for infringement or against Streamtape's policies.
