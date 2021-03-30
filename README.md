# DRF OAuth Backend

- [ ] clone or download 'backend' directory
- [ ] cd backend
- [ ] create a virtual environment (I used pipenv)
- [ ] run pip install -r requirements.txt if not using pipenv
- [ ] create a new project at Google Developers Console, or use an existing one
- [ ] in Google project, follow steps for 'Oauth consent screen'
- [ ] in 'Credentials' create a new 'OAuth client id'
- [ ] add to 'Authorized redirect URIs: http://localhost:3000/api/auth/callback/google
- [ ] note Client ID/Secret and save
- [ ] in django admin, add a new 'Social application'; ensure to add 'example.com' to available sites
- [ ] run python manage.py runserver and visit localhost:8000
- [ ] sign in link on localhost:300 should allow you to sign in via Google