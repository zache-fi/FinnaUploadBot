python3 -m venv venv
source venv/bin/activate
cd venv
git clone https://github.com/zache-fi/FinnaUploadBot.git
cd FinnaUploadBot
pip install -r requirements.txt

python upload_mfa_to_commons.py
