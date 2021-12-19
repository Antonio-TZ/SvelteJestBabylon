# SvelteJestBabylon
Currently a zero code project with just the bare bones instructions of setting up a Svelte and Babylon project. The setup also includes the setup of the Jest testing framework.

# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
```npm init svelte@next my-app```
Note: the @next is temporary <BR>
 <BR>
```npm init svelte@next sveltekit
cd sveltekit/ 
npm install 
npm run dev -- --open 
npm install --save-dev jest ts-jest  
            @testing-library/svelte @testing-library/jest-dom svelte-jester  
            @types/jest babel-jest @babel/preset-env

npm install babylonjs plus config
```
 <BR>
changes from here: https://daveceddia.com/svelte-typescript-jest/ <BR>
 <BR>

# Developing
Once you've created a project and installed dependencies with npm install (or pnpm install or yarn), start a development server:

npm run dev <BR>

# or start the server and open the app in a new browser tab
npm run dev -- --open <BR>
Look here for inspiration: <BR>
 <BR>
https://github.com/topics/svelte-components <BR>
https://svelte.dev/ <BR>
https://github.com/sveltejs/svelte/issues/2118 <BR>
https://kit.svelte.dev/docs <BR>
http://using-babylonjs.com <BR>
https://doc.babylonjs.com <BR>
https://forum.babylonjs.com <BR>
https://github.com/htmlx-org/HTMLx <BR>


# Building
Before creating a production version of your app, install an adapter for your target environment. Then: 

npm run build <BR>
 <BR>
You can preview the built app with npm run preview, regardless of whether you installed an adapter. This should not be used to serve your app in production. <BR>
