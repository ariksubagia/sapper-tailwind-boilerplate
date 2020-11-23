### Running the project

Once you have created the project, install dependencies and run the project in development mode:

```bash
npm run dev
```

### Editing css file

you can edit `./src/assets/global.css` to add custom css, it will be compiled to `./static/global.css`

### Importing component from `components` folder

You can now import component from components folder without ascending the folder first.
for example if you are in `routes` folder, to import component from `components` folder simply just use path like the following code
```javascript
import ComponentName from 'components/ComponentName.svelte'
```