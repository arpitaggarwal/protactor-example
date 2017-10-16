# Protactor

 - Protractor is a Node.js program.
 - By default, Protractor uses the Jasmine test framework for its testing interface.


# Setup

Use npm to install Protractor globally with:

```npm install -g protractor```

This will install two command line tools, `protractor` and `webdriver-manager`.

The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with:

```
webdriver-manager update
```

Now start up a server with:

```
webdriver-manager start
```

This will start up a Selenium Server and will output a bunch of info logs. Your Protractor test will send requests to this server to control a local browser.

Leave this server running and we can see status of the server at http://localhost:4444/wd/hub.


# Reference

1. http://www.protractortest.org/#/tutorial
