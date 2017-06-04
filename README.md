# Hungry Enough

A demo iOS app for using Yelp API to get nearby restaurants. I'm so hungryyyy!

`SwiftLint` must be installed for code style checking.

#### Credentials ####

As this app use Google Maps API and Yelp API, it requires Google Maps API Key and Yelp Access Token/Secret Key to be modified. Feel free to update those configurations inside `Config.swift`.

#### Installation ####

The source code is built using Swift 3.1 and above, XCode 8.2 and above with Carthage 0.22 and above. Please do:
```
carthage bootstrap --platform ios --cache-builds
```

after checked out.

If you need to add any new dependency, please add to `Cartfile` then do:
```
carthage update --platform ios --cache-builds
```

If you encounter any problem with cached artifacts between multiple machines, you can consider adding ` --no-use-binaries` flag to above commands.

#### Contributors ####

* Diep, Nguyen Hoang

Copyright 2017, AwpSpace