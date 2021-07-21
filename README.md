# zimbra-cestina

Toto repozitory obsahuje **českou lokalizaci pro open source verzi Zimbra server**.

Aktuálně pro verzi 8.8.x (měla by fungovat i na 8.7.x)

## obsah repozitory

* adresář ansible - instalace balíčku s lokalizací pomocí Ansible (restartuje Zimbra server)
  * ansible-playbook -l z.example.com -C ./plays/zcestina.yml
* adresář source/zimbra - zdrojové soubory překladu
* skript zcestina-apt - pro výrobu DEB balíčku
* DEB balíček
  * dpkg -i zimbra-cestina.deb

