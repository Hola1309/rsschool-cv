# rsschool-cv
Andrey Somov
# Contact Info
email: hola131098@gmail.com
# Skills 
Python; Flask; HTML; CSS; Mercurial; JavaScript; PostgreSQL; SQL; SQLAlchemy; PHP; 1С-Битрикс
# Code examples
    @login_manager.user_loader
    def load_user(user_id):
      return User.query.get(int(user_id))

    class LoginForm(FlaskForm):
      username = StringField('username', validators=[InputRequired(), Length(min=4, max=15)])
      password = PasswordField('password', validators=[InputRequired(), Length(min=8, max=80)])
      remember = BooleanField('remember me')

    class RegisterForm(FlaskForm):
      email = StringField('email', validators=[InputRequired(), Email(message='Invalid email'), Length(max=50)])
      username = StringField('username', validators=[InputRequired(), Length(min=4, max=15)])
      password = PasswordField('password', validators=[InputRequired(), Length(min=8, max=80)])

# Experience 
Manufacturing practice: development of web applications, databases
# Education
Samara State Technical University, Samara
# English
English courses on Duolingo
