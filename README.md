🕷️ Web Email Scraper

A powerful Python-based web scraper that automatically extracts email addresses from websites through recursive crawling.
✨ Features

    🔍 Recursive Crawling - Automatically discovers and scrapes all pages within a domain

    📧 Email Extraction - Uses regex patterns to find email addresses in page content

    🎨 Colorful Output - Real-time colored console feedback with progress tracking

    ⚡ Multi-threaded - Concurrent scraping for improved performance (configurable)

    💾 Auto-save - Results automatically saved to file, with interrupt protection

    🛡️ Error Handling - Robust error handling with timeout and connection management

🚀 Quick Start

# Clone and install
git clone https://github.com/yourusername/web-email-scraper.git
cd web-email-scraper
pip install -r requirements.txt

# Run the scraper
python scraper.py

📋 Usage

# Basic usage
python scraper.py

# With custom parameters (modify code)
# - Change max_urls for limit
# - Adjust threading workers
# - Modify rate limiting

⚙️ Configuration

Easy to customize:

    Maximum URLs to scrape

    Thread workers count

    Request timeouts

    Rate limiting delays

    User agents and headers

🛡️ Ethical Usage

Important: This tool is intended for:

    ✅ Security research

    ✅ Penetration testing (with permission)

    ✅ Educational purposes

    ✅ Personal contact gathering from your own sites

Always:

    Respect robots.txt

    Get proper authorization

    Follow website terms of service

    Use reasonable rate limits

📁 Output

    Extracted emails saved to emails__.txt

    Real-time console progress updates

    Detailed logging of scraped URLs

🛠️ Requirements

requests
beautifulsoup4
colorama

⚠️ Disclaimer

This tool is for educational and authorized testing purposes only. Users are responsible for ensuring they have proper authorization before scanning any websites. The developers are not liable for misuse.
