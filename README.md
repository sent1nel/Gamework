Gamework
========

Don't use this. It's terrible. But if you want to use it, it uses browserify for front-end includes. And I doubt you're going to find a compatible version of jquery-browserify unless you use mine, and I haven't added it to this project's package.json

Requirements
------------

You'll need browserify to build gamework. You'll also need a version of jquery-browserify. I'm going to add vendor libraries to package.json whenever I get around to it. I should probably stop wasting my time writing READMEs.
```
zipp@zeratul:~$ sudo npm -g install browserify
```

Installation
------------

It's pretty easy to install. Clone the repository, and in the root directory..
```
zipp@zeratul:~/gamework$ npm install
zipp@zertaul:~/gamework$ make build
./bin/build.sh
zipp@zeratul:~/gamework$ npm start

> gamework@0.0.1 start /home/zipp/gamework
> node app

```

Browse to localhost:8080 and you should be up and running!

License
-------

License: MIT

* Copyright (C) 2012 Joshua K. Farrar (http://www.uber1337hax.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
