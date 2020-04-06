# Covid-19 Argentina, Data Analysis

The object of the analysis is to show some relevant info about the pandemic disease, focusing Argentina as country.
The data is collected daily from [Argentina official web page](https://www.argentina.gob.ar/coronavirus/informe-diario) and with the collab of another [repo](https://github.com/Wolffoner/COVID19_Argentina/blob/master/COVID19-Argentina/)

## Visualization

For the globally analysis you can enter to [Whole country analysis.ipynb](https://github.com/Fluzko/Covid-19-Argentina/blob/master/Whole%20country%20analysis.ipynb) file at the root of the repo

## Installation
Feel free to download the repo and use it for your own analysis or anything else, "you know... it's free!"

Use the package manager [pip3](https://pip.pypa.io/en/stable/) and [venv](https://pypi.org/project/virtualenv/) to install all the requirements that the proyect needs.

```bash
cd Covid-19-Argentina
python3 -m venv ./venv
source venv/bin/activate
pip3 install -r requirements.txt
```

## Usage
Just run the following command to run jupyter notebook locally

```bash
cd Covid-19-Argentina
jupyter notebook
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Changelog
- Dislikes the ones who has no photo

## Fixings
- sleeps replaced for implicit waits
- fixed the "find_element_by_xpath" by custom xpath

