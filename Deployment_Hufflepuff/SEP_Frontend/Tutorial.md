# SEP-Hufflepuff-Botschmiede

## Tutorial (Was muss ich tun?)
1. Ordner für das neue Repo erstellen
2. Repo clonen
3. SOFORT <code>git checkout branch</code> (branch ist euer Feature-Branch, muss nicht vorhanden sein) <br/>
  3.1 TIPP: Wie erwähnt muss der branch nicht schon bestehen. Ihr könnt auch als Beispiel <code>git branch ChristianBackendServer</code> machen und kommt so auf den neuen Branch (bzw legt diesen an) <br/>
  3.2 Bitte nehmt für eure Branches eindeutige Namen wie in 3.1, also <code>EuerName"Front-/Backend"Feature</code>, damit man ihn auch einfach und eindeutig mergen kann<br/>
  3.3 Kurzen testpush machen mit einer Test.txt, siehe Punkt 5.<br/>
  3.4 Falls es nicht funktioniert (sollte auch in der Bash dann stehen) <code>git push --set-upstream origin asdf</code>
4. CODEN
5. Pushen <br/>
  5.1 <code>git add -A</code> <br/>
  5.2 <code>git commit -m "Notiz"</code> (Notiz muss in "") <br/>
  5.3 <code>git push</code> <br/>
6. In Discord im <code>Haus Hufflepuff</code> bescheid geben mit <code>@Hufflepuff</code> oder <code>@freakdran</code>
  Um mergen etc. kümmere ich mich

## Wie arbeiten wir?
1. Jeder arbeitet immer nur auf seinem Feature-Branch
2. Das Feature wird getestet wenn es läuft
3. Das Feature wird in die nächst höheren Branch (Front/Backend gemerged)
4. Es wird erneut das komplette Front/Backend (Branch auf dem gemerged wurde) getestet um sicher zu sein, dass das Feature richtig integriert wurde und nichts im bereits vorhandenen und funktionierenden Branch zerstört hat.
5. Alles wird komplett zusammen gemerged
6. Alles wird getestet um Front-Backend-Interaktion zu testen


## Notiz an mich
Versionierung mit <code>git tag TAG -a "Notiz"</code>

## um einen verlorengegangenen Prozess zu beenden:

netstat -ano

=> PID aus lesen

taskkill /F /PID XXXXX

Dockerstore: 
docker pull philipoe/vue-template

