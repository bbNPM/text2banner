# text2banner
This project is a Strapi v5 plugin that provides functionality to generate a simple banner using customizable text and color codes.


### Initial Setup
Put below source code to `WORKDIR/config/plugins.ts`
```
export default () => ({
	'text2banner': {
		enabled: true,
		resolve: './src/plugins/text2banner'
	},
});
```