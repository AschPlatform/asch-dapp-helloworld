# Asch Dapp Helloworld

To install this Dapp on your localnet follow the instructions in [Chinese](https://github.com/AschPlatform/asch/blob/master/docs/dapp_docs/1_hello.md) or [English](https://github.com/AschPlatform/asch/blob/master/docs/dapp_docs/1_hello_en.md).

Genesis Dapp account
```
    address: AHMCKebuL2nRYDgszf9J2KjVZzAw95WUyB
    secret: sentence weasel match weather apple onion release keen lens deal fruit matrix
    publicKey: a7cfd49d25ce247568d39b17fca221d9b2ff8402a9f6eb6346d2291a5c81374c
```


## Configure environment

#### Install Dapp
Be sure to have the asch-dapp installed in your localnet ([tutorial](https://github.com/AschPlatform/asch/blob/master/docs/dapp_docs/1_hello_en.md)). Normally the localnet is running on `http://localhost:4096`. If the this Dapp was successfully installed, then you should see a directory with a long name in `asch/dapps/<long name>`.
Open your browser and type `http://localhost:4096/api/dapps/a7ef9cd0707fe94f583334d434e39570113a43e3647c8ee730bf21ec2fe08c97/transactions`, now you should get some JSON response. First step is done. The Dapp functions as our backend. Now we need something we can respond to, a webapp. Now let's start the local development server and get the web application up and running.

#### Start local development server
In the `asch/dapps/<dapp Id>/development` folder is a demo Vue.js project. The Vue.js runs usually on `http://localhost:8080` it access our dapp on `http://localhost:4096/api/dapps/<dappId>/`.

Change directory to the development folder. `cd development`
To start the web server run `npm run dev`. You need to set your `<dapp Id>` in  `development/config/dev.env.js` so that the web app can access the sidechain.

## Run your first Dapp
Now open your browser and type `http://localhost:8080` to access the webapp.


#### Help
If something is not working for you. Don't hesitate, create a issue on [aschplatform/asch-dapp-helloworld](https://github.com/aschplatform/asch-dapp-helloworld) and we will very soon help you.
