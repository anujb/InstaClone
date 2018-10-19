# InstaClone + Azure Hackathon

Instagram Clone built with React Native.

<br/>

![screenshot](./screenshot.gif)

## Get Started

```sh

# Follow react-native install instructions here – 
# https://facebook.github.io/react-native/docs/getting-started.html#installing-dependencies
# brew install node
# brew install watchman
# npm install -g react-native-cli

#Then clone and run InstaClone

$ git clone https://github.com/anujb/InstaClone.git
$ cd InstaClone
$ yarn install
$ react-native run-ios
```

## Azure Storage

This project uses Azure storage to store and retrieve media with a container wide SAS token.

```
const data = [{
  key: 1,
  username: 'james',
  type: 'video',
  source: "https://nikeakshackfeststorage.blob.core.windows.net/nikeakshackfestblobcontainer/drive.mov..."
}, 
```

## Build a Node.js backend with Docker + Kubernetes

We will use the following hands-on-lab to create a node.js backend with Docker + Kubernetes in AKS

https://github.com/Azure/blackbelt-aks-hackfest/

You will use the following javascript code to return a model object down to the react-native client.

https://gist.github.com/anujb/9d1b3e42d4a0e8645624011011085ef6

## Integrate Azure Vision API

TBD

## License

MIT
