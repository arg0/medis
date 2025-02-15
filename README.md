# Medis

![Medis](http://getmedis.com/screen.png)

Medis is a beautiful, easy-to-use Redis management application built on the modern web with [Electron](https://github.com/atom/electron), [React](https://facebook.github.io/react/), and [Redux](https://github.com/rackt/redux). It's powered by many awesome Node.js modules, especially [ioredis](https://github.com/luin/ioredis) and [ssh2](https://github.com/mscdex/ssh2).

[![Join the chat at https://gitter.im/luin/medis](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/luin/medis?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Medis starts with all the basic features you need:

* Keys viewing/editing
* SSH Tunnel for connecting with remote servers
* Terminal for executing custom commands
* Config viewing/editing

It also supports many advanced features:

* JSON/MessagePack format viewing/editing and built-in highlighting/validator
* Working with millions keys and key members without blocking the redis server
* Pattern manager for easy selecting a sub group of keys.

## Download Medis

You can download compiled versions of Medis for Mac OS X from [the release page](https://github.com/luin/medis/releases). Support for Windows and Linux is coming soon.

## Running Locally

```shell
$ npm install
$ npm run dev
$ npm start
```

## Build Medis

```shell
$ npm run deploy
$ ./Medis.app
```

## I Love This. How do I Help?

* Simply star this repository :-)
* Help us spread the world on Facebook and Twitter
* Contribute Code! We're developers! (See Roadmap below)
* Medis is available on the Mac App Store as a paid software. I'll be very grateful if you'd like to buy it to encourage me to continue maintaining Medis. There are no additional features comparing with the open-sourced version, except the fact that you can enjoy auto updating that brought by the Mac App Store. <br> [![Download on the App Store](http://getmedis.com/download.svg)](https://itunes.apple.com/app/medis-gui-for-redis/id1063631769)

## Roadmap

* Lua script editor
* Cluster management
* GEO keys supporting

## License

MIT
