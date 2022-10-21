# rtc-cluster
A Example Implementation build from @rtc-cluster/tasks imported as module build with Stealify on Linux which are using diffrent other stealify sys tasks and combine them into rtc-cluster/tasks which are more high level. If You are wondering what Stealify is that is a Unlicensed ECMAScript supporting Runtime like NodeJS but designed for servers similar to cloudflare workers but Stealify adds a nice framework around that and a Capability Based Protocol as also various levels of Isolation and Containerisation it builds whole Isolated Optimized VM's it also is able to build Cloud Images without Operating System Overhead so called Unikernals or Cloud Kernals. 

## Use the WebUI
This demo Ships with a WebUI it installs NodeJS and also Puppeteer To Run It's Presentation via Browser Automation
Parts of this demo are used to build the DIREKTSPEED Cloud Ui mostly the web-components are reused. 

### If you got NodeJS Already Running

```
npx @stealify/stealify fetch component+github:rtc-cluster/rtc-cluster/ui https://github.com/rtc-cluster/rtc-cluster/ui
npx @stealify/stealify build component:rtc-cluster-ui
npx @stealify/stealify run component:rtc-cluster-ui # executes fetch/build if needed. and a url is supplyed. 
```

or install stealify global
```
npm i -g @stealify/stealify
stealify build
stealify run
```

### Use Stealify

Obtain a copy some how.
```

stealify build component:rtc-cluster-ui
stealify run component:rtc-cluster-ui # executes build if needed.
```
