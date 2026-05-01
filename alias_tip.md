## Aliasten käyttö komentorivillä

Voit muokata terminaalin asetustiedostoa hakemistossa `~/.bashrc` lisäten sinne omasta mielestäsi hyödyllisiä pikakomentoja muodossa `alias <name>='<command>'` kuten esimerkiksi:

```bash
alias upgrade='sudo apt update && sudo apt upgrade -y && sudo apt autoclean'
alias install='sudo apt update && sudo apt install'
alias myip='curl ifconfig.me && echo ""'
alias gerp='grep'
alias bashrc='nano ~/.bashrc'
alias bashupd='source ~/.bashrc'
```

Yhtäsuuruusmerkin kummallakaan puolella ei saa olla välilyöntiä.

Tiedoston muokkaamisen jälkeen tulee ajaa komento `source ~/.bashrc`, jotta muutokset astuvat voimaan.
