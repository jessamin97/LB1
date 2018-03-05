# LB1 Modul 300
Author: David Vauthey
Datum: 05.03.2018


MultiVM:

1. Am Anfang erstelle ich einen Ordner im Home Laufwerk mit der Bezeichnung lb1.
2. In diesem Ordner erstellte ich ein Vagrantfile, mit dem Befehl "vagrant init bento/ubuntu-16.04".
3. Danach bearbeitete ich das Vagrantfile mit den nötigen Commandozeilen.
4. Nun startete ich mit "vagrant up" die VM´s.
5. Zum testen verbindete ich mich, mit dem Befehl "vagrant ssh client1", auf eine erstellte VM und machte einen Ping auf den client2.
6. Nun zerstörte ich die VM´s wieder mit "vagrant destroy -f".
