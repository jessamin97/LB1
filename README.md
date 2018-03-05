# LB1 Modul 300
Author: David Vauthey
Datum: 05.03.2018


Umgebung (Multi VM) funktionsfähig auf eigenem Notebook:

1. Am Anfang erstelle ich einen Ordner im Home Laufwerk mit der Bezeichnung lb1.
2. In diesem Ordner erstellte ich ein Vagrantfile, mit dem Befehl "vagrant init bento/ubuntu-16.04".
3. Danach bearbeitete ich das Vagrantfile mit den nötigen Commandozeilen.
4. Nun startete ich mit "vagrant up" die VM´s.
5. Zum testen verbindete ich mich, mit dem Befehl "vagrant ssh client1", auf eine erstellte VM und machte einen Ping auf den client2.
6. Nun zerstörte ich die VM´s wieder mit "vagrant destroy -f".


Bestehende VM aus Vagrant Cloud zum laufen bringen:

1. Im Vagrantfile ein neues Box_image hinzufügen "debian/wheezy64".
2. Box-image1 wird beim Master verwendet und Box_image2 beim client.
3. Danch "vagrant up" und die VM´s werden erstellt.
4. Zum Schluss wieder "vagrant destroy -f"
