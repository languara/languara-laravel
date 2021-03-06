Languara Plugin for Laravel 4.x
========================

<h3>Install</h3>

Add languara plugin information to your composer.json file:

<pre><code>
"require": {
  "languara/laravel": "~1.0"
}
</code></pre>

Use composer to install this package.

<pre><code>
$ composer update
</code></pre>

<h3>Register the package</h3>

Add the package to the autoload array in app/config/app.php:

<pre><code>
'providers' => array(
    // .....
    'Languara\Laravel\LaravelServiceProvider'
)
</pre></code>

<h3>Configure the Package</h3>

.....

<h3>Usage</h3>

Execute this command to see a list of available commands in your commandline:

<pre><code>
$ php artisan
</code></pre>

--------------------

Or you can check the commands and their usage here:

<pre><code>
$ php artisan languara:translate [options]
</code></pre>

to translate the texts you already have in your lang directory. You can also select the type of translation you want to perform, Machine or Human. It's set to machine by default.

<pre><code>
$ php artisan languara:connect [project-private-key]
</code></pre>

to connect your plugin with a project on languara.com

<pre><code>
$ php artisan languara:pull
</code></pre>

to download your content from Languara to your app.

<pre><code>
$ php artisan languara:push
</code></pre>

to upload your content from your app to Languara.


<pre><code>
$ php artisan languara:register
</code></pre>

to register a new user on languara.com
