# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

```mermaid
sequenceDiagram
ServiceFunction ->> connectDocuSign: Invokes with function itself
connectDocuSign ->> checkToken: Invokes
checkToken ->> checkToken: Decides the token in global is invalid
checkToken ->> getToken: Invokes
getToken ->> DocuSign API: Invokes
DocuSign API ->> DocuSign API: Generates a token
DocuSign API ->> getToken: Sends access token token
getToken ->> checkToken: Passes the token
checkToken ->> checkToken: Sets the token to global variable with expiration time
checkToken ->> connectDocuSign: Returns back
connectDocuSign ->> connectDocuSign: Sets the token to DocuSign client
connectDocuSign ->> ServiceFunction: Returns the function itself
```
