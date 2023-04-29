# Exécution du projet

Légende:
- 0 = tâche en cours ou non exécutée
- 1 = tâche exécutée

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
|N°|Tâche|responsable|Status|
|---|---|---|---|
|1|Compléter la liste des noms avec des noms de famille usuels|djomo-moungoue|0|
|2|Kùkū renommer par Kùkū'|djomo-moungoue|1|
|2|Ndǔ'nzɑ̄ renommer par Ndʉ̌'nzɑ̄|djomo-moungoue|1|

Remarques:
- pourquoi Ngǎmeni et non Ngǎmɑ̄ni comme dans Njōmɑ̄lʉ̄ɑ̄' (12/04). Pareil Cāmēnī, 
- Cāmgúé ce n'est pas plutôt Cāmgwê ? (29/04)
- Doublons:
    - Cīēncə̄ə̄ 3 fois (5/01 et 7/05, 13)
    - Njə̀ə̄mōō (28/01 et 14/06)
    - Mɑ̂ntû'kām (11 et 12/07)
    - Sīèwèn (18/02 et 4/09)
    - Ca᷅mnà' (31/03 et 12/09)
- Kùkū ca devrεt etre avec le cout de glottes Kùkū'
- Ndǔ'nzɑ̄ ca drevrεt etre Ndʉ̌'nzɑ̄

# Getting Started with Create React App

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


----

# Dépannage d'erreurs

## Problème
~~~js
$ npm start

> calendrier-nufi@0.1.0 start
> react-scripts start

'react-scripts' is not recognized as an internal or external command,
operable program or batch file.
~~~

## Solution
"It is an error about react-scripts file missing in your node modules directory at the time of installation. Now, you can add manually this via the command:"
~~~js
$ npm install react-scripts
~~~
