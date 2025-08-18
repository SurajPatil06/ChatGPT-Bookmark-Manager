# ChatGPT Bookmark Manager

🔗 **Live Demo:** [ChatGPT Bookmark Manager](https://mint-greeneel.onpella.app/) 

ChatGPT Bookmark Manager built with **Flask** lets you save, organize, and manage your ChatGPT conversation links.  
It supports the following actions:

- User authentication (Login/Signup)
- Save and manage ChatGPT conversation/bookmarks
- Add and remove topics/tags
- Clean and simple interface
- Secure password handling with bcrypt
- Database support via SQLAlchemy

---

## Run the project

> You must have **Python 3.10+** installed on your system before running  
> (This project was developed using **Python 3.12**)

---

### Create virtual environment and activate it

```bash
# bash
python3 -m venv venv
source venv/bin/activate

# windows
python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

# bash
(env) $ export SECRET_KEY="your_secret_key"
(env) $ export DATABASE_URL="sqlite:///bookmarks.db"

flask run
