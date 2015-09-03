# Pass me
This webpage allows you create a different password for all your accounts using only a single master password.

It is hosted here: [Pass me] (https://dl.dropboxusercontent.com/u/102424383/passme.html)
but it can also be downloaded and opened locally since it is only a single html file.

### Usage
All you have to do is type in the domain (e.g. Github), your master password and press 'Copy to clipboard' or Show password'. When copied, Ctrl+v can be used anywhere to paste your domain-specific password.

### How it works
The web page uses the non-invertible SHA256 HMAC hashing algorithm to generate a password from the domain and the master password. This means that it is practically impossible to recreate your master password from the domain-specific password if it would be compromised. The generated passwords are strong, short and reasonably memorable.

### Credits
- SHA256 HMAC script from Brian Turek 2008-2015 (http://caligatio.github.com/jsSHA/)
- Seedrandom script from David Bau 2015 (https://github.com/davidbau/seedrandom)
- Shuffle script from Jonas Raoni Soares Silva (http://jsfromhell.com/array/shuffle [rev. #1])
- Randint script from pc035860 (https://gist.github.com/pc035860/6546661)
- Change classes script from kjy112 (http://stackoverflow.com/questions/5169017/how-to-remove-class-attribute-from-div)
