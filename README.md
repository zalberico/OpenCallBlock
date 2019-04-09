# Fork README
I forked this with the intent to make a whitelist for iOS that would send any non-contact incoming phone call to voicemail.  Unfortunately it seems that Apple's CallKit doesn't allow you to do this.  The API requires you to query a blacklist in order to block a call (and adding all possible numbers except for contacts to this blacklist would make the list too big).

It's not too surprising this is the case since I'd expect a whitelist app to exist already if it wasn't, but it's too bad since an iOS whitelist would immediately solve the call spam problem.

I'd have two features in addition to the whitelist:
 - Option to allow any incoming call for the next 20min (for uber, doordash etc.)
 - Option to allow the second call from the same number to ring through.
 
 This would solve 99% of issues where you need an unknown number to ring your phone.

# OpenCallBlock
### License

MPL 2.0 [FAQ](https://www.mozilla.org/en-US/MPL/2.0/FAQ/)
