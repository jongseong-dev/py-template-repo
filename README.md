# py-template-repo
python 기본 템플릿 레포지토리

# 기본 구성
- python = ^3.11
- django = ^4.1
- pytest.ini: pytest 설정

## git
### actions
- pr-test: pr을 올렸을 때 자동으로 테스트를 돌림

### template
- pr-template: pr template

## poetry

### group lint
- flake8 = "^7.0.0"
- pyright = "^1.1.358"
- ruff = "^0.3.7"
- reorder-python-imports = "^3.12.0"
- pre-commit = "^3.7.0"

### group dev
- django-debug-toolbar

### group test
- pytest = "^8.1.1"
- pytest-cov = "^5.0.0"
- pytest-django

### gitignore
- pycharm
- python
- Django