# Flask Blog

> A simple Blog made in Flask.

This project is a simple blog where the users can post articles and edit or delete them.

## Building

>Note that depending on your machine you may have to use **pip3** instead of **pip** and **python3** instead of **python**.


>Its best to use the `virtualenv` tool to build locally. Install virtualenv by running `pip install virtualenv`

>Then create a virtual environment by `virtualenv <your env name>`

>Activate the virtual environment by `source <your env name>/bin/activate`

>Deativate the virtual environment by running `deactivate` in your terminal.

 * First install the required modules by running `pip install -r requirements.txt`

 * Then run `python flaskblog.py`

 Go to `localhost:5000` and the site should be live!

 ## Usage



## Contributing

This project is in its early stage of development and will certainly break into some point. Please open an issue if you have spotted a bug or create a pull request if you have added a cool feature! 

Please follow certain guidelines to make the code more readable for other contributors.

### Making a pull request

Please open a **new issue** before making any pull request. **Every pull request should have a reference to an issue**.

* First, fork this repository.

* Clone it using `git clone https://github.com/[username]/Flask-Blog.git`

* It is always recommended to make your changes in a new branch rather than master. So create a new branch using `git branch mybug`.

* Checkout into your new branch using `git checkout mybug`.

* Hack the code, kill the bug or introduce the new feature you had in mind, do all kinds of awesome stuff.

* After you are done add your changes using `git add --all`

* Commit your changes using git commit and provide a commit message: `git commit -m "<commit message>" `.

* After you have committed your changes push your changes to your forked repository using `git push origin mybug`.

* Finally create a pull request from github.

* If everything is alright then soon your changes will get merged or else you will be asked to make changes.

There should be **only one commit per pull request**.

Please try to make sure that your commit message and body follows the guidelines below.

* Commit message should be of the form : `fixes issue #[issue_number] - what you solved in one line`

* After Commit message there should follow a commit body where you can mention what you did in short or in detail.

Please try to follow this format as it will be helpful for maintainers as well as co-developers/contributors to stay aligned.

## Resources
This project uses Flask 1.0. Corresponding resources maybe found at [Flask Docs](http://flask.pocoo.org/docs/1.0/).




