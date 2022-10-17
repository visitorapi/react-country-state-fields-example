# `react-country-state-fields` Example

This project was is an example of using the react-country-state-fields package to build a country field and a state field that are able to detect user's geolocation and prefill the fields without any popups. It requires a [VisitoraAPI](https://www.visitorapi.com) project ID to function properly. You can create a free project or a paid project and copy the project ID to the following line in the `App.js` file.

```
<VisitorAPIComponents projectId="{your project ID}" handleCountryChange={(countryObj) => setCountry(countryObj)} handleStateChange={(stateObj) => setState(stateObj)}>
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

You will see a page with the country field and the state field. The fields will set to your country and state by default if the VisitorAPI project ID is valid. You can also manually change your country and state if you would like to.

## `react-country-state-fields` Package

The npm package location: [https://www.npmjs.com/package/react-country-state-fields](https://www.npmjs.com/package/react-country-state-fields)

The source code repo location: [https://github.com/visitorapi/react-country-state-fields](https://github.com/visitorapi/react-country-state-fields)
