# The new API

## Getting started

The new API has a UI tool that can be used called GraphiQL. 
This shows documentation about the models that can get returned and allows you to make requests.
For the URL and login details we refer to the smash.gg Discord, these will not be included in this repo.
You can join the smash.gg discord using [this url](https://bit.ly/smashggdiscord).

There is a useful tutorial on how to use GraphQL [found here](https://graphql.org/learn/) credit goes to [Keef](https://github.com/keithrobichaud) for supplying this information.

## Bug reports and feedback

Bug reports and feedback should be done in the Trello board made by [Keef](https://github.com/keithrobichaud). This can be found in the `api-alpha` Discord channel of the smash.gg Discord.

## FAQ

### How to do request based on URL?

There are 2 ways that URL requests can be done.
- In a **GET** putting the parameters and variables in the URL.
- Using a **POST** and supplying the parameters and variables as a JSON body.

Personally (Bart de Bever), I would use the POST option to not make your GET URL over complicated and unreadable.
A basic tutorial on how to use URL requests can be [found on their website](https://graphql.github.io/learn/serving-over-http/)

[JsFiddle showing how to POST](https://jsfiddle.net/swyvafL4/) [by Gaiwecoor](https://github.com/Gaiwecoor).
Note that the URL is missing from this fiddle. This is done to not expose the API to the public early.

### What is up with authentication?
Quoting [Keef](https://github.com/keithrobichaud) from what was said on the Discord:
```
The api itself currently has auth turned off
So only publicly available data will be accessible for now
```

### Are there plans for first party SDK/Libraries/Wrappers?
Quoting [Keef](https://github.com/keithrobichaud) from what was said on the Discord:
```
We definitely don't have the manpower currently to work on an official SDK
We're more than happy to feature anything made by y'all on our future developer portal 
```
