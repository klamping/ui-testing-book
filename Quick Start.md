```
npm init wdio@latest ./wdio-quick-start -- --yes
cd wdio-quick-start
npx wdio
```

WebdriverIO will install the proper chrome browser if needed, load it up, and run your test
Mention the test that was run in the reporter output
Open up `test/specs/test.e2e.js`

Add two `await browser.pause(2000)` lines, so we can see what's going on a little more
