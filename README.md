<div align="center">
  <h1>
    Google Flights CO2 Plugin
  </h1>

  <p>
    <strong>Compare your carbon footprint for your next flight!</strong>
  </p>
</div>

## Features
TODO

## Installation
1. Clone the repository `git clone git@github.com:sharonswli/flight-co2.git`
2. Run `npm install`
3. Run `npm run build`


##### Load the extension in Chrome & Opera
1. Open Chrome/Opera browser and navigate to chrome://extensions
2. Select "Developer Mode" and then click "Load unpacked extension..."
3. From the file browser, choose to `flight-co2/build/chrome` or (`flight-co2/build/opera`)


##### Load the extension in Firefox
1. Open Firefox browser and navigate to about:debugging
2. Click "Load Temporary Add-on" and from the file browser, choose `flight-co2/build/firefox`


## Developing
The following tasks can be used when you want to start developing the extension and want to enable live reload - 

- `npm run chrome-watch`
- `npm run opera-watch`
- `npm run firefox-watch`


## Packaging
Run `npm run dist` to create a zipped, production-ready extension for each browser. You can then upload that to the appstore.


-----------
This project is licensed under the MIT license. 

