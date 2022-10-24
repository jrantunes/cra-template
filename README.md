# CRA-TEMPLATE

<p align="center">A initial template to React projects using <b>Create React App</b></p>

## Installing

1. Use this template with the cra command

	Using npm:

	```bash
	$ npx create-react-app my-app --template @jrantunes/cra-template
	```

	Using yarn:

	```bash
	$ yarn create react-app my-app --template @jrantunes/cra-template
	```

2. Run the **prepare** script to setup husky pre-commit

	Using npm:

	```bash
	$ npm run prepare
	```

	Using yarn:

	```bash
	$ yarn prepare
	```
	
	_Lint-staged is configured to run the **linting**(with **--max-warnings=0**) and **test** scripts if one of these two fails the changes wont be commited_

3. Start your app

	Using npm:

	```bash
	$ npm run start
	```

	Using yarn:

	```bash
	$ yarn start
	```

4. To automatically create your component folder you can use the **generate** script

	Using npm:

	```bash
	$ npm run generate ComponentName
	```

	Using yarn:

	```bash
	$ yarn generate ComponentName
	```

	The generated folder will contain the following files:
	- **index.tsx** - `The component file`
	
	- **{{ component_name }}.spec.tsx** - `The tests of the component`
	
	- **stories.tsx** - `The stories of the component`
	
	- **styles.ts** - `The styles of the component`

##### This template uses the following dependencies:
- [Husky](https://typicode.github.io/husky/#/)
- [Lint Staged](https://github.com/okonet/lint-staged)
- [Storybook](https://storybook.js.org/docs/react/get-started/introduction)
- [Eslint](https://eslint.org/docs/latest/)
- [Prettier](https://prettier.io/docs/en/index.html)
- [Styled Components](https://styled-components.com/docs)
- [Plop js](https://plopjs.com/documentation/#getting-started)
- [TypeScript](https://www.typescriptlang.org/docs/)