# projeto_jhow.web
Projeto Sicad faculdade Faisp 2019  Daniel Carvalho Jhow
git init
git add .
git commit -m "primeiro commit"
git remote add origin https://github.com/projeto_jhow.web
git puch -u origin master






<from action="/upload">
    <input type="file" name="fileupload" value="fileupload"id
    <label type for="fileupload"> Select a file to upload</label>
    <input type="submit" value="klik">
    
    usando Python IDLE (Python 3.6 64-bit)
    
from flask import Flask
app = Flask(__name__)

    @app.route('/user/<username>')
    def show_user_profile (username):
        # show the user profile for that user
        return  ' user %s ' % username
    if __name__ == '__main__':
        app.run(debug = True)
