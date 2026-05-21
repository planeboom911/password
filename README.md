# Custom password generator - @planeboom911
Visit link : [password generator](https://planeboom911.github.io/password)

### Parameters
* Master password
* App name / login phrase
* Length of password

### Output
* password of given length
* NOTE :  the last two letters are always the first and last letter of app name / login phrase

### How it works
It works by assembling all parameters and hashing with SHA256 which generates a non-reversible
random-like hexdigest which is then stripped upto given length and added constraints like a symbol ( @ )
and capitalizing the first alphabet that appears.
