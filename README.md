# Express Fileserver
Simple Node + Express server for serving static files

* Currently deployed at [rbrt-sln.com](https://www.rbrt-sln.com)
* Initial file served at [rbrt-sln.com/ctod](https://www.rbrt-sln.com/ctod)
* To test on your device, install with `yarn install` and then serve with `yarn start`
  * If yarn is not installed, see [yarn installation](https://yarnpkg.com/lang/en/docs/install) for details

## To deploy on Google App Engine:
* Open shell for your app engine instance
* Clone your project, example: `git clone https://github.com/rbrt-sln/express-fileserver`
* Go to project folder by typing `cd express-fileserver`
* Set port to 8080 with `PORT=8080`
* Finally, deploy with `gcloud app deploy`
