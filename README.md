
How quick, simple, and cheap can the web2 stack be in 2023?
Part of the larger experiment organized at [coldstart](https://github.com/zootella/coldstart).

This is 🍺 [cold1.cc](https://cold1.cc/) on [AWS Amplify](https://aws.amazon.com/amplify/)

Commands to make

```
$ npx create-react-app cold1
$ cd cold1

$ git remote add origin git@github.com:zootella/cold1.git
$ git branch -M main
$ git push -u origin main
```

Commands to use, standard webpack from create react app. Pushing to GitHub starts AWS build and deploy.

```
$ npm run start (to have webpack compile, complain, and serve)
$ npm run build (to have webpack compile and complain like aws will)
$ serve -s build (to serve the build folder of compiled static assets)
```

Locations

 * https://main.d13xw9ps78zjky.amplifyapp.com/
 * https://www.cold1.cc/
