# Welcome to Meanvironment!
##### Meanvironment is a boilerplate environment to begin development with the MEAN stack!

<p>Just run these steps in your terminal:</p>

<pre>
	<code>
		$ git clone https://github.com/garoian82/meanvironment
		$ cd meanvironment
		$ npm install (in some cases may have to run $ sudo npm install)
		$ gulp
	</code>
</pre>

<p>Then, redirect your browser to:</p>

<pre>
	<code>
		localhost:3000
	</code>
</pre>

### Meanvironment includes the following stuff pre-loaded:
<ul>
	<li>Angular Js</li>
	<li>Bootstrap</li>
	<li>Angular Bootstrap</li>
	<li>Angular UI Router</li>
	<li>mongoose</li>
	<li>gulp packages (checkout your <code>node_modules/</code> folder. There are a few different gulp packages included.</li>
</ul>

### What else is included? Well, I'll tell you!
<ul>
	<li><code>gulpfile.js</code> that creates a <code>build/</code> folder (already ignored in <code>.gitignore</code>)</li>
	<li><code>angular ui router</code> for maping the states of your application. 
		<ul>
			<li>predefined <code>angular.module</code> along with a <code>/home</code> state in <code>public/javascripts/app.module.js</code></li>
			<li>predefined <code>controller</code> and <code>index.html</code> in <code>public/javascripts/home</code></li>
		</ul></li>
	<li>LESS!!! there is a <code>less</code> file already set up for you in <code>public/less</code> It is also included in the <code>gulpfile.js</code> for your build!</li>
</ul>

### Disclaimer:

<p>Please feel free to tweak this clone to your own specifications. This is just to get you started on your MEAN development journey! Happy coding!</p>