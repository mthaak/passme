# Pass me
This web tool allows you create a different password for all your accounts using only a single master password.

**It is hosted here: [https://mthaak.github.io/passme/](https://mthaak.github.io/passme/)**  
but it can also be downloaded and used locally since it is only a single html file.

### Usage
All you have to do is type in the domain (e.g. Github) and your master password and press 'Copy to clipboard' or 'Show password'. When copied, Ctrl+V can be used anywhere to paste your account-specific password.

### How it works
The tool uses the non-invertible SHA256 hashing algorithm to generate a password from the domain and the master password. This means that it is practically impossible to recreate your master password from the account-specific password if it would be compromised. Also since everything is done client-side your passwords can not be intercepted. The generated passwords are strong, short and reasonably memorable. 

### Credits
- SHA256 HMAC script from Brian Turek 2008-2015 (http://caligatio.github.com/jsSHA/)
- Seedrandom script from David Bau 2015 (https://github.com/davidbau/seedrandom)
- Shuffle script from Jonas Raoni Soares Silva (http://jsfromhell.com/array/shuffle [rev. #1])
- Randint script from pc035860 (https://gist.github.com/pc035860/6546661)
- Change classes script from kjy112 (http://stackoverflow.com/questions/5169017/how-to-remove-class-attribute-from-div)
- Bootstrap (http://getbootstrap.com/)
