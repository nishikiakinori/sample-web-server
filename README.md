# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
Last login: Fri Jun 14 09:53:49 on ttys001
(base) nishikiakirasokunoMacBook-Pro:~ nisikiakinori$ cd ~/fujiwara
(base) nishikiakirasokunoMacBook-Pro:fujiwara nisikiakinori$ cd sample-web-server
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
^[[AError: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
^[[AError: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ sudo chown -R $(whoami) /usr/local/lib/pkgconfig
Password:
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ brew install jq
==> Installing dependencies for jq: oniguruma
==> Installing jq dependency: oniguruma
==> Downloading https://homebrew.bintray.com/bottles/oniguruma-6.9.2.mojave.bottle.tar.gz
==> Downloading from https://akamai.bintray.com/c6/c613befafe81da48913ebd1a7eb036a7d8a147516fae32e2fbf4278efdb34056?__gda__=exp=1560478491~hmac=6013e63f4b0c7c2a583b60a4cb76a07a378cb22e6959e2cfcf4b5bf3a85b
######################################################################## 100.0%
==> Pouring oniguruma-6.9.2.mojave.bottle.tar.gz
🍺  /usr/local/Cellar/oniguruma/6.9.2: 17 files, 1.3MB
==> Installing jq
==> Downloading https://homebrew.bintray.com/bottles/jq-1.6.mojave.bottle.1.tar.gz
==> Downloading from https://akamai.bintray.com/71/71f0e76c5b22e5088426c971d5e795fe67abee7af6c2c4ae0cf4c0eb98ed21ff?__gda__=exp=1560478494~hmac=c5a369203952dd726ed9edfc471e1782c81bec21ef0486cff6de98788499
######################################################################## 100.0%
==> Pouring jq-1.6.mojave.bottle.1.tar.gz
🍺  /usr/local/Cellar/jq/1.6: 18 files, 1MB
==> `brew cleanup` has not been run in 30 days, running now...
Pruned 2 symbolic links from /usr/local
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
[
  {
    "breeds": [],
    "id": "8bf",
    "url": "https://cdn2.thecatapi.com/images/8bf.jpg",
    "width": 420,
    "height": 315
  },
  {
    "breeds": [
      {
        "weight": {
          "imperial": "12 - 18",
          "metric": "5 - 8"
        },
        "id": "mcoo",
        "name": "Maine Coon",
        "cfa_url": "http://cfa.org/Breeds/BreedsKthruR/MaineCoon.aspx",
        "vetstreet_url": "http://www.vetstreet.com/cats/maine-coon",
        "vcahospitals_url": "https://vcahospitals.com/know-your-pet/cat-breeds/maine-coon",
        "temperament": "Adaptable, Intelligent, Loving, Gentle, Independent",
        "origin": "United States",
        "country_codes": "US",
        "country_code": "US",
        "description": "They are known for their size and luxurious long coat Maine Coons are considered a gentle giant. The good-natured and affable Maine Coon adapts well to many lifestyles and personalities. She likes being with people and has the habit of following them around, but isn’t needy. Most Maine Coons love water and they can be quite good swimmers.",
        "life_span": "12 - 15",
        "indoor": 0,
        "lap": 1,
        "alt_names": "Coon Cat, Maine Cat, Maine Shag, Snowshoe Cat, American Longhair, The Gentle Giants",
        "adaptability": 5,
        "affection_level": 5,
        "child_friendly": 4,
        "dog_friendly": 5,
        "energy_level": 3,
        "grooming": 3,
        "health_issues": 3,
        "intelligence": 5,
        "shedding_level": 3,
        "social_needs": 3,
        "stranger_friendly": 5,
        "vocalisation": 1,
        "experimental": 0,
        "hairless": 0,
        "natural": 1,
        "rare": 0,
        "rex": 0,
        "suppressed_tail": 0,
        "short_legs": 0,
        "wikipedia_url": "https://en.wikipedia.org/wiki/Maine_Coon",
        "hypoallergenic": 0
      }
    ],
    "id": "LIQSvUemz",
    "url": "https://cdn2.thecatapi.com/images/LIQSvUemz.jpg",
    "width": 2000,
    "height": 2000
  },
  {
    "breeds": [],
    "id": "hAQpmY_eg",
    "url": "https://cdn2.thecatapi.com/images/hAQpmY_eg.jpg",
    "width": 1022,
    "height": 1024
  }
]
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ mkdir mywebapi
(base) nishikiakirasokunoMacBook-Pro:sample-web-server nisikiakinori$ cd mywebapi
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ npm init
-bash: npm: command not found
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ npm install --save express
-bash: npm: command not found
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ cat ~/.bash_profile

# Setting PATH for Python 3.7
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.7/bin:${PATH}"
export PATH
# added by Anaconda3 2019.03 installer
# >>> conda init >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$(CONDA_REPORT_ERRORS=false '/Users/nisikiakinori/anaconda3/bin/conda' shell.bash hook 2> /dev/null)"
if [ $? -eq 0 ]; then
    \eval "$__conda_setup"
else
    if [ -f "/Users/nisikiakinori/anaconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/nisikiakinori/anaconda3/etc/profile.d/conda.sh"
        CONDA_CHANGEPS1=false conda activate base
    else
        \export PATH="/Users/nisikiakinori/anaconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda init <<<
if [ -f ~/.bashrc ]; then
  . ~/.bashrc
fi
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ cat ~/.bash_profile

# Setting PATH for Python 3.7
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.7/bin:${PATH}"
export PATH
# added by Anaconda3 2019.03 installer
# >>> conda init >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$(CONDA_REPORT_ERRORS=false '/Users/nisikiakinori/anaconda3/bin/conda' shell.bash hook 2> /dev/null)"
if [ $? -eq 0 ]; then
    \eval "$__conda_setup"
else
    if [ -f "/Users/nisikiakinori/anaconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/nisikiakinori/anaconda3/etc/profile.d/conda.sh"
        CONDA_CHANGEPS1=false conda activate base
    else
        \export PATH="/Users/nisikiakinori/anaconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda init <<<
if [ -f ~/.bashrc ]; then
  . ~/.bashrc
fi
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ curl -L git.io/nodebrew | perl - setup
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0
100 24634  100 24634    0     0  15454      0  0:00:01  0:00:01 --:--:-- 15454
Fetching nodebrew...
Installed nodebrew in $HOME/.nodebrew

========================================
Export a path to nodebrew:

export PATH=$HOME/.nodebrew/current/bin:$PATH
========================================
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ export PATH=$HOME/.nodebrew/current/bin:$PATH >> ~/.bashrc
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ source ~/.bashrc
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ nodebrew
nodebrew 1.0.1

Usage:
    nodebrew help                         Show this message
    nodebrew install <version>            Download and install <version> (from binary)
    nodebrew compile <version>            Download and install <version> (from source)
    nodebrew install-binary <version>     Alias of `install` (For backward compatibility)
    nodebrew uninstall <version>          Uninstall <version>
    nodebrew use <version>                Use <version>
    nodebrew list                         List installed versions
    nodebrew ls                           Alias for `list`
    nodebrew ls-remote                    List remote versions
    nodebrew ls-all                       List remote and installed versions
    nodebrew alias <key> <value>          Set alias
    nodebrew unalias <key>                Remove alias
    nodebrew clean <version> | all        Remove source file
    nodebrew selfupdate                   Update nodebrew
    nodebrew migrate-package <version>    Install global NPM packages contained in <version> to current version
    nodebrew exec <version> -- <command>  Execute <command> using specified <version>

Example:
    # install
    nodebrew install v8.9.4

    # use a specific version number
    nodebrew use v8.9.4
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ nodebrew install-binary latest
v12.4.0 is already installed
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ nodebrew ls
v12.4.0

current: v12.4.0
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ nodebrew use latest
use v12.4.0
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ node -v
v12.4.0
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi) 
version: (1.0.0) 
description: 
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: 
license: (ISC) 
About to write to /Users/nisikiakinori/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}


Is this OK? (yes) no
Aborted.


(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi) 
version: (1.0.0) 
description: 
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: 
license: (ISC) 
About to write to /Users/nisikiakinori/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}


Is this OK? (yes) 
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi) 
version: (1.0.0) 
description: 
git repository: 
keywords: 
author: 
license: (ISC) 
About to write to /Users/nisikiakinori/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC",
  "description": ""
}


Is this OK? (yes) yes
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ npm install --save express
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ express@4.17.1
added 50 packages from 37 contributors and audited 126 packages in 3.21s
found 0 vulnerabilities

(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.js
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ node index.js
Listening on port 3000
  
exit
^C
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.js
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ node index.js
Listening on port 3000
^C
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ mkdir web
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ cd mkdir
-bash: cd: mkdir: No such file or directory
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ cd web
(base) nishikiakirasokunoMacBook-Pro:web nisikiakinori$ vi index.html
(base) nishikiakirasokunoMacBook-Pro:web nisikiakinori$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/Users/nisikiakinori/Documents/fujiwara/sample-web-server/mywebapi/web/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
(base) nishikiakirasokunoMacBook-Pro:web nisikiakinori$ cd .
(base) nishikiakirasokunoMacBook-Pro:web nisikiakinori$ ls
(base) nishikiakirasokunoMacBook-Pro:web nisikiakinori$ cd ../
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ ls
index.js		node_modules		package-lock.json	package.json		web
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ rmdir web
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ ls
index.js		node_modules		package-lock.json	package.json
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ node index.js
Listening on port 3000
^C
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ mkdir web
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ ls
index.js		node_modules		package-lock.json	package.json		web
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.html
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.html
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.html
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.html
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.html
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ vi index.js
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ node index.js
Listening on port 3000
^C
(base) nishikiakirasokunoMacBook-Pro:mywebapi nisikiakinori$ node index.js
Listening on port 3000


```
