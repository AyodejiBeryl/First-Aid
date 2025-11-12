# First-Aid
## 🧩 Local Setup

```bash
# clone the repo
git clone https://github.com/AyodejiBeryl/First-Aid.git
cd First-Aid

# create and activate environment
python -m venv my_env
source my_env/Scripts/activate  # or my_env\Scripts\activate on Windows CMD

# install dependencies
pip install -r requirements.txt

# set up environment variables
cp .env.example .env
# edit .env to add your real API keys

# create local data folder
mkdir data

# run app or scripts
python app.py
