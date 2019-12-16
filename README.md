# Ελληνικό αριθμητικό πληκτρολόγιο, τελεία αντί για κόμμα σε Linux
# Greek Layout Dot instead of Comma on Numerical Keypad Linux

Οδηγίες Εγκατάστασης:

Κατεβάζουμε και αποσυμπιέζουμε το αρχείο με όποιο πρόγραμμα θέλουμε.

Στην συνέχεια ανοίγουμε ένα τερματικό και εκτελούμε την εντολή:
 

* *sudo cp gr /usr/share/X11/xkb/symbols/* 

όπως φαίνεται και στην εικόνα 

![Screenshot](https://i.imgur.com/74FBGUW.png)

Κάνουμε επανεκκίνηση και μετά είμαστε έτοιμοι!

-------------------------------------------------------------------------------

Για Arch & Manjaro κατεβάζουμε το PKGBUILD από την διεύθυνση [https://gitlab.com/psposito/greek-layout-dot-instead-of-comma-on-keypad/-/tags/1.0](url)

και εκτελούμε στο τερματικό:


* *makepkg --syncdeps* 

και μετά:


* *makepkg install* 

Στην συνέχεια κάνουμε επανεκκίνηση στο σύστημά μας και είμαστε έτοιμοι.
