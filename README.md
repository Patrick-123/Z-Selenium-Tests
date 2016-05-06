# Z-Selenium-Tests

These instructions are for an Mac OS X El Capitan environment. 

It uses the terminal heavily and when I put a command for the terminal I will prepend the command with a "$" therefore to run the command copy everything after the dollar sign and paste it into your terminal.

You will need Node and Java installed to run these tests locally.

- Check if you have node installed

    $ node -v

- If not then download it with homebrew

    $ brew install node

- If you don't have homebrew installed, first smack yourself. Then run this

    $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

- Next check if you have Java installed

    $ java -version

- If not you can install it with homebrew

    $ brew install Caskroom/cask/java

- To run the test locally first install se-interperter

    $ npm isntall -g se-interpreter

- Then you have to run the local Selenium server

    $ java -jar selenium-server-standalone-2.53.0.jar

- Then you can run a single test with the command of 

    $ se-interpreter Tests/<your test file>

- Or you can run the full suite with this command

    $ se-interpreter Tests/*