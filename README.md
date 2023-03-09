# LinuxPalvelimet-h13-Hello-world
    Kirjoittanut: Jesse Reunamo
    Kurssi:       Linux-palvelimet
    Linkki:       https://terokarvinen.com/2023/linux-palvelimet-2023-alkukevat/
    
## a)

### Bash
Bash on asennettuna linuxille automaattisesti, koska linuxin komentorivi toimii bash- kielellä. Lähdin kokeilemaan kirjoittamalla ensiksi tekstitiedoston.

    micro skripte.sh
    Hei Maailma!

![image](https://user-images.githubusercontent.com/112503770/223875277-b6cc2919-f625-4655-8572-917035bd02c9.png)

Seuraavaksi kokeilin ajaa luotua skripte.sh tiedostoa komennolla: `bash skripte.sh`, mutta sain virheilmoituksen ks. kuva 3. Tein korjaukset tekstitiedostoon.

    micro skripte.sh
    echo "Hei Maailma!"

![image](https://user-images.githubusercontent.com/112503770/223875438-dd935b5b-66e2-4113-b951-12b99fe4be69.png)

Ajan vielä luodun skriptin komennolla: `bash skripte.sh`.

![image](https://user-images.githubusercontent.com/112503770/223876209-33cf5363-406c-46fd-b850-2fa313179554.png)

### Python
Aloitin prosessin kokeilemalla, mikä version pythonia on koneessa asennettenu komennolla:

    python3 --version
    
![image](https://user-images.githubusercontent.com/112503770/223876910-1cdc985c-4fc4-4872-9dd1-b5377327a244.png)

Yllätyin, että se olikin jo valmiiksi asennetuna, joten siirryin luomaan tekstitiedostoa.

    micro skirpterino.py
    
Lunttasin tässä vaiheessa Teron sivuilta oikeata syntaksia: `print("Hello Tero")`.

![image](https://user-images.githubusercontent.com/112503770/223877282-3c75dd50-a023-47e9-b59f-a67e0dc39f3c.png)

Kokeilin ajaa tiedoston komennolla `python3 skripteri.py`.

![image](https://user-images.githubusercontent.com/112503770/223877449-06260e71-4fe3-4ec9-929d-cd0276858818.png)

### Ruby
Asennetaan ruby ohjelmointi kieli komenolla:

    sudo apt-get install ruby-full
    
Kirjoitetaan ruby tiedosto microlla. Meni hetki etsiessä miten kirjoitetaan `\` merkki. Sen voi kirjoittaa painamalla `altgr` + `+` suomalaisella näppäimistöllä. Jos `\n` unohtuu niin rivinvaihto jää pois. 

    micro skripperino.rb

![image](https://user-images.githubusercontent.com/112503770/223880315-d53a20f8-78ac-4cb8-8922-8bac43c1b1ea.png)

Ajetaan luotu skripti.

    ruby skripperino.rb
    
![image](https://user-images.githubusercontent.com/112503770/223880674-aa41fdbe-6a8c-4976-8ba2-719a1d98f368.png)

Käytetty aika: ~1h
## Lähteet:

    https://terokarvinen.com/2023/linux-palvelimet-2023-alkukevat/
    https://terokarvinen.com/2018/hello-python3-bash-c-c-go-lua-ruby-java-programming-languages-on-ubuntu-18-04/
    https://www.ruby-lang.org/en/documentation/installation/
