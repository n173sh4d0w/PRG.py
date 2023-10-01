# Pentesting Report Generator(PRG.py)
This Python script generates penetration testing reports in PDF format from collected data and encrypts them for secure storage. 
## Features
Collect penetration testing data.
Analyze collected data.
Gen report in PDF&Encrypted w/user-provided password for security.
## Usage
```
git clone https://github.com/your_username/penetration-test-report-generator.git
cd penetration-test-report-generator
pip install -r requirements.txt
python report_generator.py
```
Follow the prompts to specify the output PDF file name (e.g., report.pdf) and the encryption password.

## Customization
Replace the collect_data and analyze_data functions with your actual data collection and analysis logic.
Modify the HTML template in the generate_html_report function to customize the report's content and styling.
## Dependencies
pdfkit: For PDF generation from HTML.
cryptography: For file encryption.
## License
MIT License
