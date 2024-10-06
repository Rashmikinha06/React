React Project Notes - 

1. Create index.html
2. Create a src folder
3. Create App.js and App.css in src folder
4. npm init command to install package.json
5. npm install -D parcel command to install package-lock.json
6. Ignite our App - start our app - npx parcel index.html
7. Build our App - npx parcel build index.html
8. npm install react command to install react
9. npm install react-dom  command to install React-dom
* npm install react-router-dom command to install router
1. If there is any key content error - rm -rf .parcel-cache  this command is used it may be due to cache
2. Component - functional component name start with uppercase letter
3. Export the component before Import 
4. There are two type of export - name and default
5. Hooks - useState and UseEffect
6. Never create a useSate object outside component , not in loop , not in if else conditions
7. useEffect can be used in three ways - in all ways it calls on render but there are some differences after that
8. useEffect ( () => {}, [] )
9. In this inline function is important but not the condition which is written in []
10. If [] is blank then it renders once when the component loads only
11. If [] this is not used in useEffect then it render when component renders
12. If there is condition  that is object it call on render and when object changes.