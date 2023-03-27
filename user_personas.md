### Alice

*Freelance software developer and hacker, 35 years' old, lives in Berlin, Germany.*

Alice uses Qubes OS as her main work machine. She separates projects for various clients into separate qubes, 
and within a project uses a set of code/build/test/production qubes.

**Needs and goals**: Security with regards to work and private life. Strong separation of work done for different clients. Privacy: maintaining a strong separation of private/personal identities and public/work identities.

**Qubes OS setup and usage**: Alice needs a flexible Qubes OS installation with multiple templates (for various projects and tests she needs different distributions and even a Windows qube). She often switches between qubes for different purposes. She needs a lot of qubes, although not that many running at the same time.

**Frustrations**: RAM and disk space woes. Lack of GPU acceleration support means she cannot easily use her Qubes machine for occassional gaming. Easy to make misclicks in tools like Qube Manager and Domains/Devices Widgets.

**Activities related to device management**:
- quickly connect her webcam and microphone to different qubes from a set of 'communications/social' qubes
- connect a thumb drive to a selected qube
- use her u2f authentication token in different qubes
- connect an untrusted customer device to a single qube, make sure it has no contact with other qubes
- occassionally connect usb mouse and keyboard when she works in 'docked' mode

### Bob

*Investigative journalist, 30 years' old, lives in Poznań, Poland.*

Bob uses Qubes OS as a supplementary system for work. He is potentially exposed to malware and malicious attacks 
from sources and people who could pose as journalistic sources.

**Needs and goals**: Strong security, maintaining of privacy, separation of work and private communications.

**Qubes OS setup and usage**: Fairly simple setup, with a bunch of non-networked qubes for things like writing, a 
vpn-ed qube for work communication, a bunch of communication qubes for Signal and personal email, and a Whonix qube to 
access the Internet via Tor. He also uses disposable qubes extensively to open all sorts of attachments and browse the Internet.

**Frustrations**: Complicated UX for tasks such as updating templates. Copying and pasting is annoying (even if he understands why).
Finds connecting a pen drive complicated (why are there multiple devices there?). Afraid of accidentaly copying/connecting something 
to a wrong qube. Annoyed when he has to use CLI because he is very uncomfortable with it.


**Activities related to device management**:
- connect a pen drive to a disposable qube to see its contents
- connect a trusted/familiar pen drive to one of selected qubes
- connect microphone and camera to one of the social qubes
- connect a portable drive to make backups

### Carol

*An investor, 45 years' old, lives in small-town US.*

Carol uses Qubes OS as a method of protecting herself and her investments.

**Needs and goals**: Very strong security

**Qubes OS setup and usage**: Multi-qube setup with very extensive compartmentalization; a lot of qubes that can only access their banking company's website, a bunch of vault qubes for offline data storage and password management. Custom minimal templates.

**Frustrations**: Memory consumption. Configuration is difficult without GUI tools (Carol is not a programmer, although she is fairly technically savvy; she can write SQL queries, interact with DBs, and so using CLI is not completely foreign to her, but she would prefer not to use it).

**Activities related to device management**:
- connect a card reader she uses to access her corporate ID
- connect a trusted/familiar pen drive to one of selected qubes
- connect a portable drive to make backups
- connect and use her hardware crypto wallet


