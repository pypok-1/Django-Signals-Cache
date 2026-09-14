# Django Subscriptions: Signals + Cache

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHprN3psMzdubzJ2c25qZ2RyMWNzODFraW84ZWEwdndhbW1ueXl2eiZlcD12MV9naWZzX3RyZW5kaW5nJmN0PWc/wZD7RX1fHKsU7FckHH/giphy.gif" width="80" alt="cat-gif">

---

## Features

- **Signals**: `post_save`, `post_delete`, and `m2m_changed` handle data without views
- **Custom Signal**: A custom `topic_changed` signal
- **Caching**: The list of topics is stored in cache
- **HTML**: Design and templates (provided as part of the assignment)

---

## Setup

```bash
# 1. Clone the repository
git clone https://github.com/pypok-1/НОВОЕ_ИМЯ.git
cd NEW_NAME

# 2. Apply migrations
python manage.py migrate

# 3. Run the server
python manage.py runserver
