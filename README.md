# weather-module

## installation

### install via composer

```
composer require abberadhi/weather-module
```


## configuration


### move over files

stand in root

```
rsync -av ./vendor/abberadhi/weather-module/config/ ./config/

rsync -av ./vendor/abberadhi/weather-module/src/ ./src/

rsync -av ./vendor/abberadhi/weather-module/view/ ./view/

rsync -av ./vendor/abberadhi/weather-module/view/ ./view/

rsync -av ./vendor/abberadhi/weather-module/test/ ./test/

rsync -av ./vendor/abberadhi/weather-module/htdocs/css ./htdocs

```


### api keys
* Make a copy of ``.weatherapi-example.json`` and name it ``.weatherapi.json``, put in your personal api key
* Make a copy of ``.api-example.json`` and name it ``.api.json``, put in your personal api key.


### style

in your ``config/page.php``, insert this line under ``stylesheets``

```
"css/weather.css"
```

### test

run
```
sudo make test
```