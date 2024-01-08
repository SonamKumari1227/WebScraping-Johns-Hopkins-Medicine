# WebScraping-Johns-Hopkins-Medicine

## Overview

This project involves web scraping data from [Johns Hopkins Medicine](https://www.hopkinsmedicine.org/) website to collect details of approximately 3000 doctors. The data is stored in a CSV file for further analysis.

## Features

- Web scraped data from [Johns Hopkins Medicine](https://www.hopkinsmedicine.org/) website.
- Collected details of approximately 3000 doctors.
- Stored data in a CSV file.

## Technologies Used

- Python
- BeautifulSoup
- Pandas
- Other relevant technologies

## Getting Started

Clone the repository:

\`\`\`bash
git clone https://github.com/SonamKumari1227/WebScraping-Johns-Hopkins-Medicine.git
cd WebScraping-Johns-Hopkins-Medicine
\`\`\`

Install dependencies:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

## Usage

Run the web scraping script:

\`\`\`bash
python scrape_data.py
\`\`\`

## Data Structure

The data collected is stored in the CSV file with the following structure:

\`\`\`plaintext
doctor_id, name, specialty, ... (other fields)
1, Dr. John Doe, Cardiology, ...
2, Dr. Jane Smith, Neurology, ...
\`\`\`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
EOF

# Create a new LICENSE file
cat <<EOF > LICENSE
MIT License
Copyright (c) [2024] [Sonam Kumari]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
EOF




