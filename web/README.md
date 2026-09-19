# 웹 통합

담당: **dwkang (@KDW1007)** · 브랜치: `web/dwkang`

Django 기본 사이트 (기능 없음).

## 실행

```bash
cd web
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

브라우저: http://127.0.0.1:8000/
