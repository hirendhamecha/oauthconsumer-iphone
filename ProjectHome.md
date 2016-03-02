This project contains a makefile which will extract the Objective-C component of OAuthConsumer so that it is amenable for iPhone app development.

An example Twitter client using the OAuth flow is provided.

QUICK START:

  1. Download oauthconsumer-iphone.
  1. At the command line, run `make` which will download the Objective-C component of OAuthConsumer and create a new directory _OAuthConsumer_.
```
    $ make
```
  1. The directory _examples/oauthTwitterApp_ contains an iPhone XCode project which can be built. Replace `kConsumerKey` and `kConsumerSecret` in _oauthTwitterAppViewController.h_ with your Twitter app settings.

INTEGRATION:

  1. Copy (directly or by reference) the _OAuthConsumer_ folder into your iPhone XCode project.
  1. In the build settings (project -> get info -> build) set the parent path of _OAuthConsumer_ in **Header Search Paths** (HEADER\_SEARCH\_PATHS).
  1. In your source code, `import "OAuthConsumer.h"` as appropriate.
  1. Add the Security framework to your project.

Many thanks to the OAuthConsumer team.




