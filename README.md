# SSH-Key

### SSH Keys erstellen um sich ohne Passwordeingabe anzumelden.
___
RSA Schlüssel erstellen<br>
`ssh-keygen -t rsa`

Den Privaten Schlüssel auf den Server pushen<br>
`ssh-copy-id janne@janne-test-01.cloud.rto.de`

Remote Shell öffnen<br>
`ssh janne@janne-test-01.cloud.rto.de`

Neues Konsolenfenster öffnen um wieder auf den Home rechner zu sein
Dann ssh key zum zweiten server pushen<br>
`ssh-copy-id janne@janne-test-02.cloud.rto.de`

Anschließend kann man sich verbinden<br>
`ssh janne@janne-test-02.cloud.rto.de`
