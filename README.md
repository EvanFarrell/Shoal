
- Migrate: `DATABASE_URL=postgres:///... python manage.py migrate`
- If you use [heroku local](https://devcenter.heroku.com/articles/heroku-local), or [foreman](https://github.com/ddollar/foreman)/[forego](https://github.com/ddollar/forego), edit `.env` to add `DATABASE_URL` and `REDIS_URL`, then start `heroku local`/`foreman`/`forego`.
- Or, to run locally with `runserver`, set `DATABASE_URL` and `REDIS_URL` in your environ, then run `python manage.py runserver`.
