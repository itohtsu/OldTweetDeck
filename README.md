# OldTweetDeck
Returns old TweetDeck, for free!
Currently no easy way to install, but you can download this repo and load it as unpacked extension in Chrome/Edge/Opera/any Chromium browser.  
  
If you're interested in getting 2015 Twitter back, you can also check out [OldTwitter](https://github.com/dimdenGD/OldTwitter) extension.  
  
![Screenshot](https://lune.dimden.dev/9713d947d56.png)  

## Installation
DOESN'T WORK ON FIREFOX  
1. Download ZIP  
![s1](https://lune.dimden.dev/f84408d6b66.png)  
2. Unzip the archive
3. Go to `chrome://extensions`
4. Enable developer mode (there should be switch somewhere on that page)
5. Press "Load unpacked" button
6. Select folder with unzipped archive 
7. Go to tweetdeck.twitter.com and enjoy old TweetDeck
8. [Donate to encourage continued support](https://www.patreon.com/dimdendev)

## Transparent disclaimer
This extension will use files hosted on my own server. This technically grants me access to add anything I want to TweetDeck code any time I want. I don't have any interest in doing anything malicious, but still, use at your own risk.  
You might be asking, why not just include all files within extension itself (like [OldTwitter](https://github.com/dimdenGD/OldTwitter) does), well I [tried](https://github.com/dimdenGD/OldTweetDeck/commit/043529289ce85d5017bcc158d0e26a7df0ed4de3) and it's impossible due to use of `eval` / `new Function` in TweetDeck code. Manifest v3 extensions are not allowed to use `eval` / `new Function` because of stupid new policies.