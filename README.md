# Portfolio Asistant

### FastAPI Setup
* fastapi
* poetry
* uvicorn
* pydantic (v1.10.8)
* sqlalchemy
* Postgresql


### Python Library
* financedatareader
* pandas
* yfinance

### Run Frontend - Streamlit
* streamlit
* st-pages (streamlit-multiapps)
* streamlit-pydantic
* streamlit-searchbox
* plotly

```
streamlit run main_app.py
```

### Run Backend - FastAPI
```
uvicorn main:app --reload
```



### Commands

`poetry shell` : run poetry virtual env

`poetry add` : add package to pyproject.toml

`poetry install` : install packages

`uvicorn main:app --reload` : start server


### Additional Commands
`poetry add <package-name>`

### Env variable
```
brew install direnv
```