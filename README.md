# headless_chrome_demo

run ```npm install``` before anything else.

usage: node index.js https://apple.com > apple.html

you can pass in any url you want. 

It should take a screenshot and save the html page that potentially could be streamed to the original user requesting it. We can put an express infront of it to mimic the whole flow. 

Part of this pricess we wouldn't expose the actual URL of the payment provider.

Things that I've considered but haven't built into the demo:
- working with sessions and issuing redirects in a session friendly way.
- locking down access to where this is deployed to limit PCI exposure.
- 
