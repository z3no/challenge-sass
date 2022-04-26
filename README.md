# challenge-sass
Learning challenge about sass

Project page:

	https://z3no.github.io/challenge-sass/



- Make PHPStorm write .css file to different directory
	
	-> Preferences -> Tools -> File Watchers
	Arguments: $FileName$:$ProjectFileDir$/css/$FileNameWithoutExtension$.css
	Output: $ProjectFileDir$/css/$FileNameWithoutExtension$.css:$ProjectFileDir$/css/$FileNameWithoutExtension$.css.map


- Minify (I did not get it to work through PHPStorm, love my Mac even more now) with the help of terminal

	sass --watch --style=compressed scss/style.scss css/style.min.css