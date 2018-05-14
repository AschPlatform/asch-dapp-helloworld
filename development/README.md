# asch-dapp-helloworld

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install
# serve with hot reload at localhost:8080
npm run dev
# build for production with minification
npm run build
# build for production and view the bundle analyzer report
npm run build --report
# run unit tests
npm run unit
# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

__INFO__
For a better developer experience install the Vue-Devtools for [Chrome](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/) or the standalone [Electron App](https://github.com/vuejs/vue-devtools/blob/master/shells/electron/README.md) that works in every environmen.
 

TODO
- Enable login only for BIP39 complient secrets
- log out button
- Form validation for
 - password
 - set nickname
 - withdrawal
 - trasfer
- Show message when navigating to extern website (e.g. mainnet)
- Enable forwarding in `<dapp id>/public/index.html`
- It should be only possible to register addresses, and set IP-Address when the user is logged in
- Is it possible to set ip of Address that was not registered by me?
- Add new interface to paged
- Use pathify instead of pure vuex
- Style header items
- Registerdomain.vue component must be created every time
  - ui of registerdomain/setip is not finished!
- set Magic on http PUT verb
- style notfound component
- Refresh user balance after transfer and withdrawal
- show senderId in grey out input-text-box when transfering tokens in /transfer
- BUG: Enter in form makes dropdown open, instead
- Rewrite readme of (not this on), from asch-dapp-hello
- add paging for lists
- refresh amount after transactions, withdrawals
- On first start: show message if environment varialble ENDPOINT is correctly set (maybe console.log) 

BUG
- mainnet-wallet doesn't show dapp-withdraw transactions (e.g. sending XAS from dapp -> mainnet)
