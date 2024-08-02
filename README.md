# faust-getting-started

Welcome to the experimental Faust getting started example.

## getting started - dev mode

1. Create WP instance using Local WP or use existing instance on server

2. Install required plugins
    - Faust JS https://wordpress.org/plugins/faustwp/  (add http//:localhost:3000 or other port under Faust plugin settings)
    - WPGraphQL https://wordpress.org/plugins/wp-graphql/ 
    - WPGraphQL content blocks https://github.com/wpengine/wp-graphql-content-blocks  (only needed for custom block dev)

3. Setup required a primary menu and frontpage set to be set
   - create a menu and asign to primary menu
   - set the Homepage to a page under settings > reading

4. Clone this repo https://github.com/rudiwebworx/Faust-wordcamp
   or use Faust getting started here https://faustjs.org/tutorial/get-started-with-faust

5. Create .env.local file (sample is included in repo, rename to env.local)
   add WP url & Faust secret key from WP instance > settings >  Faust

6.Open project in code Editor
  ‘npm install’ or ‘yarn install’ if using yarn  (requires node and npm)

7. Run on local host
   ‘npm run dev’ or ‘yarn run dev’  
    (setup required a primary menu and frontpage set)
    Dev server will start and run on http://localhost:3000/

8. Build your pages / posts etc with Gutenberg blocks

9. Style blocks in frontend components / build custom blocks in the frontend as required

## Production mode

Run Build / Start server
- npm run build / yarn run build
- npm start / yarn start