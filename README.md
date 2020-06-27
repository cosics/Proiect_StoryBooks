# Proiect_StoryBooks
<b>Node.js app with Google OAuth. </b>
<p>Autentificare cu contul Google, creeaza story-uri private sau publice, mai multi utilizatori pot creea story-uri, toate story-urile ( sau numai cele ale unui anumit utilizator ) pot fi vizualizate, editate, sterse.</p>


<p>Aplicatia foloseste Node.js/Express/MongoDB cu autentificare prin Google OAuth .
Adaugati credentialele proprii ptr mongoDB URI and Google OAuth in fisierul config.env
</p>

Include:

* [express]
  * server
* [mongoDB]
  * baza de date unde vor fi stocate datele utilizatorilor Google, sesiunile de logare
* [mongoose]
  * work with the database, models
* [connect-mongo]
  * pentru a stoca sesiunile de logare in DB
* [express-sessions]
  * sessions & cookies
* [express-handlebars]
  * template engine
* [morgan]
  * HTTP request logger middleware pentru node.js
* [dotenv]
  * module that loads environment variables from a `.env` file into `process.env`
* [method-override]
  * put & delete requests from templates 
* [moment]
  * formatare data
* [passport]
  * authentication
* [materialize]
  * framework  
* [font-awesome]
  * icon library  

Development utilities:

* [nodemon](https://www.npmjs.com/package/nodemon)
  * supravegheaza continuu serverul pentru a nu restarta dupa fiecare schimbare
* [cross-env]




# Install dependencies
npm install

# Run in develpment
npm run dev

# Run in production
npm start

<h1>poze parcurs/</h1>

<h3>Leads Manager</h3>

<ul>
<li>[x] Database Setup</li>
<li>[x] Install Dependencies </li>
<li>[x] Initial Express Setup</li>
<li>[x] Connect Database</li>
<li>[x] Morgan Logger</li>
<li>[x] Template Engine & Layouts </li>
<li>[x] Index Routes & Views </li>
<li>[x] Materialize & Font Awesome  </li>
<li>[x] Static Folder  </li>
<li>[x] Login Layout </li>
<li>[x] Login Page Template </li>
<li>[x] Start Google Login </li>
<li>[x] Passport Config & Sessions </li>
<li>[x] User Model </li>
<li>[x] Passport Google Strategy </li>
<li>[x] Auth Routes </li>
<li>[x] Save Google Profile Data</li>
<li>[x] Logout </li>
<li>[x] Navigation </li>
<li>[x] Auth Middleware</li>
<li>[x] Store Sessions In Database </li>
<li>[x] Story Model </li>
<li>[x] Dashboard Stories </li>
<li>[x] Add Story </li>
<li>[x] Format Date Handlebar Helper </li>
<li>[x] Public Stories </li>
<li>[x] Truncate & StripTags Helpers </li>
<li>[x] Edit Icon Helper </li>
<li>[x] Edit Story </li>
<li>[x] Method Override pt PUT Requests</li>
<li>[x] Method Override pt DELETE Requests </li>
<li>[x] Single Story Page </li>
<li>[x] User Stories </li>
</ul>

