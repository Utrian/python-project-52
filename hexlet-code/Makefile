install:
	poetry install

build:
	poetry build

publish:
	poetry publish --dry-run

lint:
	poetry run flake8 page_analyzer

pytest:
	poetry run pytest
	poetry run pytest --cov=page_analyzer --cov-report xml
	poetry run pytest --cov-report term-missing --cov=page_analyzer

dev:
	python3 manage.py runserver
