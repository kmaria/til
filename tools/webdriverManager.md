# Webdriver Manager

Webdriver manager started in protractor as a binary manager for selenium server and browser drivers. It was originally part of the Protractor project and has been extracted as its own node module.

## Goals of webdriver manager

Download the selenium server jar and browser drivers
Run the selenium server for end to end tests
Manage downloaded versions

## Getting started

To install:
```
npm install -g webdriver-manager
```

Setting up a Selenium server:
```
webdriver-manager update
```

## Troubleshooting

In case of EACCES error try:
```
sudo npm c get user
```

## Useful commands:
```
webdriver-manager clean
webdriver-manager status
webdriver-manager update
webdriver-manager start
```
