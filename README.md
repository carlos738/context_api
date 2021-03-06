# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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


"
Contexto (context) disponibiliza uma forma de passar dados entre a ??rvore de componentes sem precisar passar props manualmente em cada n??vel.

Em uma aplica????o t??pica do React, os dados s??o passados de cima para baixo (de pai para filho) via props, mas esse uso pode ser complicado para certos tipos de props (como prefer??ncias locais ou tema de UI), que s??o utilizadas por muitos componentes dentro da aplica????o. Contexto (context) fornece a forma de compartilhar dados como esses, entre todos componentes da mesma ??rvore de componentes, sem precisar passar explicitamente props entre cada n??vel.


QUANDO USAR O CONTEXTO?
Contexto (context) ?? indicado para compartilhar dados que podem ser considerados ???globais??? para a ??rvore de componentes do React. Usu??rio autenticado ou o idioma preferido, s??o alguns casos comuns. No exemplo do c??digo a seguir, n??s passamos um tema a fim de estilizar o componente Button.

ANTES DE USAR O CONTEXTO VOC??  DEVE SABER?

Contexto (context) ?? usado principalmente quando algum dado precisa ser acessado por muitos componentes em diferentes n??veis. Use contexto moderadamente uma vez que isto pode dificultar a reutiliza????o de componentes.

Se voc?? apenas quer evitar passar algumas props por muitos n??veis, composi????o de componente geralmente ?? uma solu????o mais simples que Contexto (context).

Considere por exemplo o componente Page que passa as props user e avatarSize por v??rios n??veis abaixo de modo que os componentes Link e Avatar profundamente aninhados, podem ler essas props.
"

