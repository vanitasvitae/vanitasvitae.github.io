## Welcome

My name is Paul Schaub, I am a free software developer and computer science student from Germany.

## Projects

I'm working on some free software projects in my spare time. In my opinion free software is very important to a free society, since only free software give the user freedom and control over the machine.

### **smack-omemo**

[<img src="https://github.com/vanitasvitae/vanitasvitae.github.io/blob/master/git.png?raw=true" data-canonical-src="https://github.com/vanitasvitae/vanitasvitae.github.io/blob/master/git.png?raw=true" width="60" height="60" />](https://github.com/vanitasvitae/smack-omemo)

This project started as part of my [bachelors thesis](https://github.com/vanitasvitae/vanitasvitae.github.io/raw/master/bachelorthesis.pdf).
smack-omemo is an implementation of [OMEMO](https://conversations.im/omemo/) encryption for the XMPP library [Smack](https://igniterealtime.org/projects/smack/index.jsp). I chose this as the topic of my bachelors thesis, since I'm very interested in cryptography and I believe, that using strong encryption is necessary for a functional democracy. Implementing this functionality is my political activism against the growing surveillance state.

The project is split into two parts. First there is [smack-omemo](https://github.com/vanitasvitae/smack-omemo), which encapsulates the XMPP logic and stanza elements. This module does not contain any code related to the double ratchet algorithm as used in the Signal protocol, which OMEMO is based on. Instead it defines some interfaces and abstract methods.

The second part is [smack-omemo-signal](https://github.com/vanitasvitae/smack-omemo-signal), which is a concrete implementation of smack-omemo. It contains libsignal-protocol-java, which implements the double ratchet algorithm.

I had to split the project, since libsignal-protocol-java is licensed under the GPL, Smack on the other hand is Apache licensed. Also the modularization makes it easy to port the module to another double ratchet library at a later point in time.

Here you can find the code. Contributors are welcome :)

[smack-omemo](https://github.com/vanitasvitae/smack-omemo), [smack-omemo-signal](https://github.com/vanitasvitae/smack-omemo-signal).

### **HomeMadeOMEMO**

As a reaction to the german interior ministers decision to allow government spying on popular messengers, I wrote a tutorial in which I show, how easy it is, to create an OMEMO encrypted messenger in 
less than 200 lines of Java code. This is my political resistance against a dangerous decision made out of either malice or plain stupidity. The tutorial can be found 
[here](https://blogs.fsfe.org/vanitasvitae/2017/06/14/homemo/), while the source code is hosted [here (FSFE)](https://git.fsfe.org/vanitasvitae/HomeMadeOmemo) or [here 
(Github)](https://github.com/vanitasvitae/HomeMadeOMEMO).

When the government fails (or refuses) to protect your communications, you'll have to take action yourselves.

### **smack-openpgp**

As part of my [Google Summer of Code 2018 project](https://vanitasvitae.github.io/GSOC2018), I created an implementation of [XEP-0373](https://xmpp.org/extensions/xep-0373.html) and [XEP-0374](https://xmpp.org/extensions/xep-0374.html) *OpenPGP for XMPP: Instant Messaging* for Smack. Together with smack-omemo, this is the second end-to-end encryption implementation I wrote and the second one included in Smack.

The code for smack-openpgp can be found [here](https://github.com/vanitasvitae/Smack/tree/openpgp).

### **PGPainless**

Since I needed an easy to use OpenPGP library for java and Android for my GSoC 2018 project, I created PGPainless ([https://pgpainless.org](https://www.pgpainless.org)).

PGPainless aims to be as simple to use as possible, while offering all functionality that is needed when dealing with OpenPGP encryption.

The projects repository is found [here](https://github.com/pgpainless/pgpainless).

### **dandelion\***

[![F-Droid](https://f-droid.org/wiki/images/0/06/F-Droid-button_get-it-on.png)](https://f-droid.org/repository/browse/?fdid=com.github.dfa.diaspora_android) 
[<img src="https://github.com/vanitasvitae/vanitasvitae.github.io/blob/master/git.png?raw=true" data-canonical-src="https://github.com/vanitasvitae/vanitasvitae.github.io/blob/master/git.png?raw=true" width="60" height="60" />](https://github.com/Diaspora-for-Android/dandelion/)

For quite some time I was maintainig the dandelion\* (inofficial) Android app for the social network [diaspora\*](https://diasporafoundation.org/) together with 
[@gsantner](https://gsantner.github.io/).
I spent many hours enhancing the overall experience of the app by adding features like proxy support and sharing functionalities.
Also I spiced up the UI by implementing customizable color themes and animated fragments!

[Here](https://github.com/Diaspora-for-Android/dandelion/) you can find the project. We are always looking for new contributors and translators!

### **EnigmAndroid**

[![F-Droid](https://f-droid.org/wiki/images/0/06/F-Droid-button_get-it-on.png)](https://f-droid.org/repository/browse/?fdid=de.vanitasvitae.enigmandroid) 
[<img src="https://github.com/vanitasvitae/vanitasvitae.github.io/blob/master/git.png?raw=true" data-canonical-src="https://github.com/vanitasvitae/vanitasvitae.github.io/blob/master/git.png?raw=true" width="60" height="60" />](https://github.com/vanitasvitae/EnigmAndroid)

A simulation of the Enigma machine for Android. I reverse engineered the mechanics of the cipher machine from Wikipedia articles and tested the interoperability using an online simulator.
The app is written in java as most of my projects are.

EnigmAndroid is available on FDroid only, since I want to support free software and do not agree with Googles politics.

If you are interested, please feel free to [check it out](https://github.com/vanitasvitae/EnigmAndroid) :)

## Other work

### Bachelors Thesis

I wrote my bachelors thesis about OMEMO encryption (in German). Here you can take a look for yourselves.

[Bachelors thesis - OMEMO encryption](https://github.com/vanitasvitae/vanitasvitae.github.io/raw/master/bachelorthesis.pdf)

### Summer of Code 2017

I participated in the Google Summer of Code as a student for the XMPP Standards Foundation. I contributed to Ignite Realtime's Smack project to implement Jingle File Transfer (XEP-0234) combined with end-to-end encryption.

My work resulted amongst other things in two XMPP Extension Protocols, [XEP-0391](https://xmpp.org/extensions/xep-0391.html) and [XEP-0396](https://xmpp.org/extensions/xep-0396.html).

The project page with an overview of my work can be found [here](https://vanitasvitae.github.io/GSOC2017), all related blog posts can be found [here](https://blogs.fsfe.org/vanitasvitae/category/gsoc-2017/).

### Summer of Code 2018

This year I got another opportunity to work full time on Smack for 3 months. This time my project is an implementation of OpenPGP for XMPP ([XEP-0373](https://xmpp.org/extensions/xep-0373.html) and [XEP-0374](https://xmpp.org/extensions/xep-0374.html)) for Smack.
As you can see, I really like cryptography ;)

The project page can be found [here](https://vanitasvitae.github.io/GSOC2018), all related blog posts are found [here](https://blogs.fsfe.org/vanitasvitae/category/gsoc-2018/).

## My Blog

I'm very actively blogging about my free software advantures. If you want to follow my work, take a look at [my blog](https://blog.jabberhead.tk).

## Contact me

If you want to get in touch with me, you can find me on [mastodon](https://fosstodon.org/@vanitasvitae).
I'm also a supporter of the FSFE, so if you want to send me a mail, feel free to [do so](mailto:vanitasvitae@fsfe.org). Here you can find my 
[PGP-Key](https://raw.githubusercontent.com/vanitasvitae/vanitasvitae.github.io/master/vanitasvitae.asc). 

You can also reach out to me via XMPP: 
[vanitasvitae@jabberhead.tk](xmpp:vanitasvitae@jabberhead.tk?omemo-sid-1057050797=c758975a5960aace88d6c3353630da8c553281f3871b181b06d7eb55478a9155;omemo-sid-1035840782=c51e7aaa59c82758fcb96e2421d8fcd0af5661341bee1212f09db4cd97008019) 
([QR-Code](https://raw.githubusercontent.com/vanitasvitae/vanitasvitae.github.io/master/xmpp.png)).

Occasionally I do post stuff on [Movim](https://de.movim.eu/?contact/vanitasvitae%40jabberhead.tk), 
a federated social network based on XMPP. You should really [check it out](https://movim.eu/)!


If you want, you can support my work by donating [bitcoins](bitcoin:17Ecq3uymY9HryCnZcX6Z3jAvwgt3mFJxm) ;).

