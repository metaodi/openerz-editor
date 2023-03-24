# entsorgungskalender


Vue + Flask: https://testdriven.io/blog/developing-a-single-page-app-with-flask-and-vuejs/

CSV-Format: https://github.com/metaodi/openerz/tree/main/csv#format

## Datasets

Gemeinden: https://s.zazuko.com/2cdhrjj
Feiertage: 

## Flask application

To run the application:

```
python app.py
```

The vue app is in the `bin-buddy/src` directory.

To run the vue app:

```
cd client
npm run serve
```


# Setup

To setup python run:

```
./python_setup.sh
```

To setup the vue application:

```
cd bin-buddy
npm install
```

The application needs a Persal Access Token of GitHub, please provide it in your `.env` file:

```
cp .env.dist .env
# edit .env
```
