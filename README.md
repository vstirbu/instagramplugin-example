This is a very basic Cordova application that uses the [InstagramPlugin](https://github.com/vstirbu/InstagramPlugin.git).

Clone this repo:

```
git clone https://github.com/vstirbu/instagramplugin-example.git
```

Switch to the directory where you cloned the repo and create plugins and platforms directories:

```
cd instagramplugin-example
mkdir platforms
mkdir plugins
```

Add platforms:

```
cordova platform add ios android
```

Add InstagramPlugin:

```
cordova plugin add https://github.com/vstirbu/InstagramPlugin.git
```

Prepare your project:

```
cordova prepare
```

You are set!
