# JavaEmailApp
___Important  Classes and Interfaces___

java.util.Properties:
The Properties class represents a persistent set of properties. The properties can be saved to stream or loaded from a stream.
load property we can be call with this Class.
next class we are using

javax.mail.Message:
This class models an email message. To send a message, subclass of Message (e.g MimeMessage) is instantiated, the attributes and content are filled in, and message is sent using the Transport.send method.

java.mail.MessagingException:
This is base class for all exceptions thrown by the Messaging classes. 

import javax.mail.PasswordAuthentication:
This class is simply a repository for a user name and a password.

javax.mail.Session:
Session class represents a mail session. (Note: First of all this is most important for us to make our the session then we can be compose any mail.)

javax.mail.Transport:
This is abstract class that models a message transport.
(e.g. Transport.send(message));.

javax.mail.internet.InternetAddress:
This class represents and Internet email address using the syntax of RFC822. 
(when we pass the maill that time. We create the object InternetAddress in the RFC822)

import javax.mail.internet.MimeMessage:
This class represents a MIME style email message. It implements the Message abstract class and the MimePart interface. 

So the steps 1st
1. GET THE SESSION
2. COMPOSE THE MESSAGE
3. SEND THE MESSAGE
___Required dependency___
<!-- https://mvnrepository.com/artifact/com.sun.mail/javax.mail -->
<dependency>
    <groupId>com.sun.mail</groupId>
    <artifactId>javax.mail</artifactId>
    <version>1.6.2</version>
</dependency>
__Email password__
App passwords
App passwords let you sign in to your Google Account from apps on devices that don't support 2-Step Verification. You'll only need to enter it once so you don't need to remember it. Learn more
