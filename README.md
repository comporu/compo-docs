# CompoSymfonyCms Docs

See http://docs.compo-symfony-cms.ru

## Build

```bash
sudo apt-get install python-sphinx

cd docs
pip install -r requirements.txt --user 
sphinx-build -W -b html -d _build/doctrees . _build/html 
```

