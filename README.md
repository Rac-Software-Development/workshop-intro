# Workshop Intro
Welkom bij de Introductieweek voor software development! In dit document kan je een makkelijk overzicht vinden hoe je alles kan installeren en klaar kan zetten voor de lessen die volgen. Alles wat in dit document behandeld wordt, wordt uitgebreider uitgelegd tijdens de lessen en werkplaats.

## Short list
* Installeer Python (https://python.org)
* Vraag de Jetbrains Student Pack aan (https://www.jetbrains.com/academy/student-pack/)
* Installeer PyCharm (https://www.jetbrains.com/pycharm/)
* Maak een GitHub account aan (https://github.com/)
* Installeer Git
* Maak een SSH key aan
* Voeg SSH key toe aan GitHub

---

## Python installeren
1. Ga naar [python.org/downloads](https://python.org/downloads).
2. Klik op de grote gele `Download Python 3.x.x`

![image](https://github.com/user-attachments/assets/bc1060ed-3f92-4aa6-b060-2d0ba9bc48e5)
De versie die jij ziet in de knop kan anders zijn dan die in de screenshot. Dat maakt niks uit.

3. Start de installer<br>
Op Windows: dubbelklik op het gedownloade .exe-bestand.
Op macOS: open het .pkg-bestand.

4. **ALLEEN WINDOWS** Voeg Python toe aan je PATH en doorloop de installer
Als je de installer opent krijg je dit scherm te zien. Zorg dat de PATH checkbox aangevinkt is.<br>
![image](https://github.com/user-attachments/assets/94cd9a72-ae5f-492b-b07e-eb06ec7700ba)

Klik daarna op "Install Now", en accepteer alles met de standaard opties totdat je installatie voltooid is.

5. Check of Python werkt in de terminal<br>
Voor Windows: Typ `Powershell` in je zoekbalk en open deze.<br>
Voor MacOS: Klik `CMD+Spatie` en typ dan vervolgens `Terminal` en open deze.

Als je al een Terminal open hebt staan, open die dan opnieuw.

Typ vervolgens `python`, `py`, of voor MacOS `python3` in je terminal en klik op Enter. Je zal de versie van Python die je ingestalleerd heb staan moeten zien:
![image](https://github.com/user-attachments/assets/fa4e1604-87e9-4f55-b9a9-07406cb74ad4)

Dit is een teken dat Python werkt! Je kan nu je terminal sluiten.

---

## JetBrains Educational Pack (gratis licentie) aanvragen 
Voor de lessen gebruiken we een programmeer omgeving (IDE) genaamd PyCharm. PyCharm is van het bedrijf JetBrains en de volledige versie van deze omgeving kost normaal gesproken geld. Gelukkig kan je gratis toegang krijgen door de Jetbrains educational pack aan te vragen.

1. **Open** je browser en ga naar <https://www.jetbrains.com/academy/student-pack/>  
2. Klik op de grote **Request Now** knop  
3. Vul het formulier in – zo kan het eruitzien:  

   * **Country:** Netherlands  
   * **Level of study:** Undergraduate  
   * **Field of study:** Computer Science  
   * **e‑mail address:** je HR‑mailadres  
   * **Personal e‑mail:** je privémail  

4. Klik op **Apply for free products** en wacht even  
5. Je ontvangt een e‑mail op je HR‑mail. Klik op de link in die mail  
   ![Email van Jetbrains](https://github.com/user-attachments/assets/738bad74-de73-467c-bfc1-5f621febfad9)  
6. Log in of maak een JetBrains‑account aan  
7. In je profiel (via <https://account.jetbrains.com/licenses>) zie je nu dat de **JetBrains Educational Pack** actief is:  
   ![Student Pack staat actief in je account](https://github.com/user-attachments/assets/185e0b19-bbc3-44d8-9f7a-474a2865c5ee)

---

## PyCharm installeren

1. Terwijl je bent ingelogd bij JetBrains, ga naar <https://account.jetbrains.com/licenses>  
2. Zoek onder **Educational Pack** naar **PyCharm** (zie rechts in het screenshot)  
   ![PyCharm Professional in de licentielijst](https://github.com/user-attachments/assets/7a2e7750-611e-4f11-9f00-b7e5c1291d31)
3. Klik op de Pycharm pagina op de **Download** knop

4. Kies de juiste installer voor jouw besturingssysteem (Windows, macOS of Linux) en download deze  
5. Start de installer:  
   * **Windows:** dubbelklik op het `.exe`‑bestand  
   * **macOS:** open het `.dmg`‑bestand en sleep PyCharm naar **Applications**  
   * **Linux:** pak het `.tar.gz`‑archief uit en volg de README  

6. **ALLEEN WINDOWS** Bij installatie opties vink de PATH checkbox aan. Zie hiervoor de screenshot.
    Optioneel: 
   * Bureaublad‑icoon nodig? Vink **Create Desktop Shortcut** aan  
   * Altijd Python‑bestanden in PyCharm openen? Vink **Create Association** aan

   ![Installatie­opties – vinkjes kun je aanvinken maar hoeft niet](https://github.com/user-attachments/assets/03bf70a7-96f3-456f-b7eb-3c8a7bae3d0f)  

8. Doorloop de rest van de installer en wacht tot de installatie klaar is  
9. Zoek *PyCharm* via je start‑ of launcherscherm en open het. Zie je het welkomstscherm? Top! PyCharm is klaar voor gebruik.
   <img width="1519" height="1102" alt="PyCharm start­scherm – installatie gelukt" src="https://github.com/user-attachments/assets/b1ab2c0f-1e16-4157-88e8-98153010f1aa" />

---
## GitHub Account aanmaken
GitHub is het platform waar wij jullie code gaan nakijken, maar ook waar jullie gaan samenwerken aan code. Het is ook waar je nu deze README op bekijkt.

Sommige van jullie hebben waarschijnlijk al een account. Kies hieronder wat geldt voor jou:

<details>
<summary><strong>Ik heb al een account</strong></summary>

Als je al een account hebt zijn er 2 opties:

1. Pas je gebruikersnaam aan naar `voornaam-studentnummer` (bijv. `jan-1234567`).  
   Ga naar **Settings ▸ Account** en klik op **Change username**.

2. Maak een nieuw GitHub‑account aan en volg het kopje **Ik heb nog geen GitHub‑account** hieronder.

Dit helpt ons voorkomen dat we straks moeten uitzoeken wie `hetekaastosti301` is op GitHub tijdens het nakijken. 😅

</details>

<details>
<summary><strong>Ik heb nog geen GitHub-account</strong></summary>

1. **Open** <https://github.com/signup>  
2. Maak een **gebruikersnaam** aan dat het volgende patroon volgt: `voornaam-studentnummer`, bijvoorbeeld `jan-1234567`.  
3. Gebruik je **privé‑e‑mail** als hoofdadres en stel een sterk **wachtwoord** in.  
4. Klik op **Create account** en voltooi de CAPTCHA en e‑mail­verificatie.  
5. Na het inloggen:  
   * Klik op je profielfoto rechtsboven in de hoek. Ga naar **Settings** en dan **Emails**.
     * Controleer dat je privé‑e‑mail op **Verified** staat en maak het je **Primary email**.  
     * Voeg je **HR‑e‑mail** toe en verifieer ook deze.  

Dit is nu ook klaar. Je GitHub‑account is actief én blijft van jou nadat je bent afgestudeerd!

</details>

---

## Git Installeren
Git is een versiebeheersysteem dat we gebruiken om code te beheren en samen te werken. Hieronder vind je instructies voor het installeren en configureren van Git.

<details>
<summary><strong>Ik heb nog geen Git geïnstalleerd</strong></summary>

1. **Download Git**:
   * **Windows**: Ga naar [git-scm.com/download/win](https://git-scm.com/download/win) en download de installer.
   * **macOS**: 
     * **Optie 1**: Installeer via [git-scm.com/download/mac](https://git-scm.com/download/mac).
     * **Optie 2**: Als je Homebrew hebt, open Terminal en typ: `brew install git`.
   * **Linux**: Open Terminal en typ (voor Ubuntu/Debian): `sudo apt-get install git`.

2. **Installeer Git**:
   * **Windows**: 
     * Open de gedownloade installer.
     * Accepteer de licentievoorwaarden.
     * Kies de installatielocatie (standaard is prima).
     * Selecteer componenten (standaardselectie is prima).
     * Kies een editor (Vim als standaard is prima).
     * Blijf nu op de **Next** knop klikken totdat je de Install knop ziet.
     * Klik op "Install" en wacht tot de installatie voltooid is.

   * **macOS/Linux**: Volg de instructies in de installer of wacht tot de installatie via de terminal is voltooid.

3. **Controleer de installatie**:
   * Open Terminal (macOS/Linux) of Command Prompt/PowerShell (Windows).
   * Typ `git --version` en druk op Enter.
   * Als je een versienummer ziet (bijv. `git version 2.35.1`), is Git succesvol geïnstalleerd.

4. **Configureer je gebruikersnaam en e-mail**:
   * Open Terminal of Command Prompt/PowerShell.
   * Voer de volgende commando's uit (vervang de gegevens met je eigen informatie):
     ```
     git config --global user.name "GitHub username"
     git config --global user.email "jouw.email@example.com"
     ```
   * Deze informatie wordt gebruikt om je commits te identificeren.

</details>

<details>
<summary><strong>Ik heb Git al geïnstalleerd en heb net mijn gebruikersnaam op GitHub gewijzigd</strong></summary>

Als je net op GitHub je gebruikersnaam hebt gewijzigd moet Git dat wel matchen, anders blijven we je oude username zien.<br>
Doe hiervoor het volgende:

1. **Open Terminal of Command Prompt/PowerShell**.
2. **Controleer je huidige instellingen**:
   ```
   git config --global user.name
   ```
3. **Wijzig je gebruikersnaam en/of e-mail**:
   ```
   git config --global user.name "Nieuwe GitHub Username"
   ```
4. **Controleer of de wijzigingen zijn doorgevoerd**:
   ```
   git config --global user.name
   ```

</details>

---

## SSH Key Aanmaken en Toevoegen aan GitHub

Een SSH key stelt je in staat om veilig te communiceren met GitHub zonder telkens je wachtwoord in te voeren.
Stappen voor het aanmaken van een SSH key:

1. **Open Terminal (macOS/Linux) of Powershell (Windows)**.
2. **Genereer een nieuwe SSH key**:
   ```
   ssh-keygen -t ed25519 -C "jouw.email@example.com"
   ```
   (Vervang het e-mailadres door het e-mailadres dat je voor GitHub gebruikt)
3. **Wanneer je wordt gevraagd om een bestandslocatie**, druk op Enter om de standaardlocatie te accepteren.
4. **Wanneer je wordt gevraagd om een wachtwoord**, kun je een wachtwoord invoeren of op Enter drukken voor geen wachtwoord (een wachtwoord is veiliger).
5. **Start de SSH-agent**:
   * **macOS/Linux**:
     ```
     eval "$(ssh-agent -s)"
     ssh-add ~/.ssh/id_ed25519
     ```
   * **Windows**:
     ```
     Start-Service ssh-agent
     ssh-add $env:USERPROFILE\.ssh\id_ed25519
     ```
6. **Kopieer de SSH key naar je klembord**:
   * **macOS**:
     ```
     pbcopy < ~/.ssh/id_ed25519.pub
     ```
   * **Windows**:
     ```
     Get-Content $env:USERPROFILE\.ssh\id_ed25519.pub | Set-Clipboard
     ```
   * **Linux**:
     ```
     cat ~/.ssh/id_ed25519.pub
     ```
     Kopieer de uitvoer handmatig.

Hierdoor heb je de SSH key gekopieerd en kan je het zometeen makkelijk toevoegen aan GitHub.


## SSH Key Toevoegen aan GitHub 

Stappen voor het toevoegen van je SSH key aan GitHub

1. **Log in op GitHub**.
2. **Klik rechtsboven op je profielfoto** en selecteer **Settings**.
3. **Klik in het zijmenu op "SSH and GPG keys"**.
4. **Klik op "New SSH key"**.
5. **Geef je key een beschrijvende titel** (bijv. "Mijn Laptop" of "School Computer").
6. **Plak je SSH key (Ctrl/CMD + V) in het veld "Key"**.
7. **Klik op "Add SSH key"**.
8. **Bevestig de actie** door je GitHub-wachtwoord in te voeren als daarom wordt gevraagd.
9. **Test je verbinding** door het volgende in je terminal of powershell te typen:
   ```
   ssh -T git@github.com
   ```
   Je krijgt mogelijk een waarschuwing over de authenticiteit van de host. Typ "yes" om door te gaan.
   Als alles goed is geconfigureerd, zie je een bericht zoals: "Hi username! You've successfully authenticated, but GitHub does not provide shell access."



## Gefeliciteerd! Alles staat nu klaar om voorbereid de werkplaats op te gaan
