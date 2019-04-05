## My first Flask App

Based on the [this](https://programminghistorian.org/en/lessons/creating-apis-with-python-and-flask) article about creating your first flask app.
You can find the app [here](https://nachiket-first-flask-app.herokuapp.com/
)

### Usage
- `https://nachiket-first-flask-app.herokuapp.com/` will give you a basic homepage
- `https://nachiket-first-flask-app.herokuapp.com/api/v1/resources/books?id=0` will give you info about a book with id=0
    * Similarly, there are books until id=2
    * For id=3, it'll return a message about how the resource wasn't found

#### Future Scope
- Add support for database

#### Things I did differently
- Used pipenv instead of the usual pip (although pipenv is based on pip)
- Deployed the app on heroku

#### Challenges I faced
The article was pretty informative and in depth. However, these are the challenges I faced:
- Generating a requirements.txt using pipenv
    * [This](https://pipenv.readthedocs.io/en/latest/advanced/) in-depth article about pipenv had the solution 
- Deploying the app on Heroku
    * [This](https://pybit.es/deploy-flask-heroku.html) article had my back
- Since my app resides in a folder called 'api', I was unable to specify the folder in my Procfile
    * [This](https://stackoverflow.com/questions/16416172/how-can-i-modify-procfile-to-run-gunicorn-process-in-a-non-standard-folder-on-he/16430579) stackoverflow thead was helpful


##### Resources I used
- [This](https://gist.github.com/bradtraversy/c70a93d6536ed63786c434707b898d55) pipenv cheat sheet
- [This](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links) markdown cheat sheet
