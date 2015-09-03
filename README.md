# passme
Storage-less password manager
  
This portable webpage allows you create a different password for all your accounts using only a single master password. generate seperate passwords for all your accounts using only your secret master password. 

### Usage
All you have to do is open the .html file or surf to this site (.....), type in the domain (e.g. Google), master password and press Copy password. Then Ctrl+v wherever you need your account password.

### How it works
The web page uses the SHA256 HMAC hashing algorithm to generate a password from the domain and the master password. Since SHA256 is a cryptographic hash function it is practically impossible to recreate the master password from the domain-specific. 
Also the output is converted a more readable format where dots split up groups of 4 characters.

### Credits
- SHA256 HMAC script from Brian Turek 2008-2015 (http://caligatio.github.com/jsSHA/)
- Seedrandom script from David Bau 2015 (https://github.com/davidbau/seedrandom)
- Shuffle script from Jonas Raoni Soares Silva (http://jsfromhell.com/array/shuffle [rev. #1])
- Randint script from pc035860 (https://gist.github.com/pc035860/6546661)
- Change classes of html script from kjy112 (http://stackoverflow.com/questions/5169017/how-to-remove-class-attribute-from-div)
