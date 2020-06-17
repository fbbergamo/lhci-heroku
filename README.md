This repository was extract from https://github.com/GoogleChrome/lighthouse-ci/tree/master/docs/recipes/heroku-server to create the Heroku Deploy Button


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://github.com/fbbergamo/lhci-heroku)


## Updating LHCI

Updates are made to the LHCI server from time to time and you'll want to keep up! You can update your LHCI server on Heroku just by pushing a commit.

Use the Heroku CLI to clone your application locally

```bash
# Update LHCI
npm install --save @lhci/server@latest
# Create a commit with your update
git add -A && git commit -m 'update LHCI'
# Deploy your update to heroku
git push heroku master
```
