## Welcome

I am a free software developer and computer science student from Germany.

## Projects

I'm working on some free software projects in my spare time. In my opinion free software is very important to a free society, since only free software give the user freedom and control over the machine.

### **smack-omemo**

[<img src="http://vectorlogofree.com/wp-content/uploads/2014/04/24233-github-logo-in-a-rounded-square-icon-vector-icon-vector-eps.png" data-canonical-src="http://vectorlogofree.com/wp-content/uploads/2014/04/24233-github-logo-in-a-rounded-square-icon-vector-icon-vector-eps.png" width="60" height="60" />](https://github.com/vanitasvitae/smack-omemo)

This is my most recent project that started as part of my bachelors thesis.
smack-omemo is an implementation of [OMEMO](https://conversations.im/omemo/) encryption for the XMPP library [Smack](https://igniterealtime.org/projects/smack/index.jsp). I chose this as the topic of my bachelors thesis, since I'm very interested in cryptography and I believe, that using strong encryption is necessary for a functional democracy. Implementing this functionality is my political activism against the growing surveillance state.

The project is split into two parts. First there is [smack-omemo](https://github.com/vanitasvitae/smack-omemo), which encapsulates the XMPP logic and stanza elements. This module does not contain any code related to the double ratchet algorithm as used in the Signal protocol, which OMEMO is based on. Instead it defines some interfaces and abstract methods.

The second part is [smack-omemo-signal](https://github.com/vanitasvitae/smack-omemo-signal), which is a concrete implementation of smack-omemo. It contains libsignal-protocol-java, which implements the double ratchet algorithm.

I had to split the project, since libsignal-protocol-java is licensed under the GPL, Smack on the other hand is Apache licensed. Also the modularization makes it easy to port the module to another double ratchet library at a later point in time.

Here you can find the code. Contributors are welcome :)

[smack-omemo](https://github.com/vanitasvitae/smack-omemo), [smack-omemo-signal](https://github.com/vanitasvitae/smack-omemo-signal).

Later I'll add my bachelors thesis here as well.

### **dandelion\***

[![F-Droid](https://f-droid.org/wiki/images/0/06/F-Droid-button_get-it-on.png)](https://f-droid.org/repository/browse/?fdid=com.github.dfa.diaspora_android) 
[<img src="http://vectorlogofree.com/wp-content/uploads/2014/04/24233-github-logo-in-a-rounded-square-icon-vector-icon-vector-eps.png" data-canonical-src="http://vectorlogofree.com/wp-content/uploads/2014/04/24233-github-logo-in-a-rounded-square-icon-vector-icon-vector-eps.png" width="60" height="60" />](https://github.com/Diaspora-for-Android/dandelion/)

Currently I'm maintainig the dandelion\* (inofficial) Android app for the social network [diaspora\*](https://diasporafoundation.org/) together with [@gsantner](https://gsantner.github.io/).
I spend many hours in enhancing the overall experience of the app by adding features like proxy support and sharing functionalities.
Also I spiced up the UI by implementing customizable color themes and animated fragments!

[Here](https://github.com/Diaspora-for-Android/dandelion/) you can find the project. We are always looking for new contributors and translators!

### **EnigmAndroid**

[![F-Droid](https://f-droid.org/wiki/images/0/06/F-Droid-button_get-it-on.png)](https://f-droid.org/repository/browse/?fdid=de.vanitasvitae.enigmandroid) 
[<img src="http://vectorlogofree.com/wp-content/uploads/2014/04/24233-github-logo-in-a-rounded-square-icon-vector-icon-vector-eps.png" data-canonical-src="http://vectorlogofree.com/wp-content/uploads/2014/04/24233-github-logo-in-a-rounded-square-icon-vector-icon-vector-eps.png" width="60" height="60" />](https://github.com/vanitasvitae/EnigmAndroid)

A simulation of the Enigma machine for Android. I reverse engineered the mechanics of the cipher machine from Wikipedia articles and tested the interoperability using an online simulator.
The app is written in java as most of my projects are.

EnigmAndroid is available on FDroid only, since I want to support free software and do not agree with Googles politics.

If you are interested, please feel free to [check it out](https://github.com/vanitasvitae/EnigmAndroid) :)

## Contact me

If you want to get in touch with me, you can find me on [diaspora\*](https://pod.geraspora.de/people/bbd7af90fbec013213e34860008dbc6c) or [GNU Social](https://gnusocial.de/vanitasvitae).
I'm also a member of the FSFE, so if you want to send me a mail, feel free to [do so](mailto:vanitasvitae@fsfe.org). Here you can find my [PGP-Key](https://raw.githubusercontent.com/vanitasvitae/vanitasvitae.github.io/master/vanitasvitae.asc). 

You can also reach out to me via [XMPP](xmpp:vanitasvitae@jabberhead.tk?otr-fingerprint=811b9618014cdd1e610c63dc33a02560cd0e9215;omemo-sid-1057050797=c758975a5960aace88d6c3353630da8c553281f3871b181b06d7eb55478a9155;omemo-sid-1953869954=4092df9c2cca9c9fe8fd567794be1838b4c16e17449f36b1bfd6ed866f819f73;omemo-sid-868104676=abb94daf3c443ad505bf9c368494bf853cbac9e888bb66cc322c7cbe4afc2559) ([QR-Code](https://raw.githubusercontent.com/vanitasvitae/vanitasvitae.github.io/master/xmpp.jpg)). 


If you want, you can support my work by donating [bitcoins](bitcoin:17Ecq3uymY9HryCnZcX6Z3jAvwgt3mFJxm) ;).

