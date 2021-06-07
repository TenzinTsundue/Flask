# Flask
Flask the python web framework<br>
[tutorial point link](https://www.tutorialspoint.com/flask/flask_templates.htm)<br>
[another link](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3)<br>
```
>pip install virtualenv
>virtualenv venv
>venv\scripts\activate
```
**Http methods**

GET: Sends data in unencrypted form to the server. Most common method<br>
HEAD: Same as GET, but without response body<br>
POST: Used to send HTML form dat to sercer. Data received by POST method is not cached by server<br>
PUT: Replaces all current representations of the target resource with the uploaded content<br>
DELETE: Removes all current representations of the target resource given by a URL<br>


```
Directory structure
__Application folder
	|__main.py
	|__templates
		|__home.html
	|__static
		|__style.css
		|__action.js
```
**Jinja2 template engine**
- {%...%} for Statements
- {{...}} for Expressions to print to the template output
- {#...#} for Comments not included in the template output
- #...## for line Statements	

**Static Files**
- static files such as javascript files or a CSS file are served from static folder.

**Request Object**
- Form: It is a dictonary object containig key and value pairs of form parameters and their values.
- args: parsed contents of query string which is part of URL after questin mark(?)
- Cookies: dictonary object holding Cookie names and values
- files: data pertaining to upload file
- method: current request method
