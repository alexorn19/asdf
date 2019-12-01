### Setup and Installation

```Bash
$ pipenv install
$ pipenv run app.py
```
### Google Maps Configuration
Find the base.html file and locate the script tag that import Google's Js plotting library
and replace the key={XXXXXX}  with your Google API Key to ensure the maps dont show
the development watermark overlay in production. Find this line
```html
<script async defer type="text/javascript"
src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCZdM-ACn_CuHkIRk4TT1oI4UBPYkhmoks&callback=initialize">
</script>
```

## Scripts Herein.

* [app.py](https://github.com/TralahM/petrolapiflask/blob/master/app.py)

* [templates](https://github.com/TralahM/petrolapiflask/blob/master/templates)

* [static](https://github.com/TralahM/petrolapiflask/blob/master/static)

* [api_utils.py](https://github.com/TralahM/petrolapiflask/blob/master/api_utils.py)

* [flask_assign.txt](https://github.com/TralahM/petrolapiflask/blob/master/flask_assign.txt)

* [Pipfile](https://github.com/TralahM/petrolapiflask/blob/master/Pipfile)

* [Pipfile.lock](https://github.com/TralahM/petrolapiflask/blob/master/Pipfile.lock)

