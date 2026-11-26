# Digitalni muzej retro računara

Projekat iz predmeta **Multimediji** (FON, 2026/27): animirani, responzivni sajt u obliku digitalnog muzeja retro računara, igara i uređaja. Svaki eksponat ima obrađenu fotografiju ili ilustraciju, kratak video i audio opis, a navigacija kroz izložbu je animirana.

## Tim i uloge

| Član | Ime i prezime | Uloga |
|---|---|---|
| 1 | Vuk Laketić | Razvoj sajta i animacija (React/Next.js, GSAP), testiranje na mobilnom, objava na internetu |
| 2 | Dana Obradović | Obrada fotografija eksponata (Photoshop), tekstovi o eksponatima |
| 3 | Katarina Pajdaković | Audio opisi eksponata, zvučni efekti i muzika (Audacity), voiceover |
| 4 | Andrija Zečević | Dizajn u Figmi, vizuelni identitet muzeja i logo (Illustrator), paleta boja i tipografija |
| 5 | Filip Popović | Kratki video prilozi o eksponatima i uvodni video (Premiere Pro / CapCut) |

## Struktura repozitorijuma

| Folder | Šta ide unutra | Ko |
|---|---|---|
| dizajn/ | Logo, paleta, tipografija, izvozi iz Figme (SVG/PNG) | Andrija |
| fotografije/ | Obrađene fotografije eksponata (optimizovane za web) | Dana |
| audio/ | Audio opisi, zvučni efekti, muzika (MP3/OGG) | Katarina |
| video/ | Kratki video prilozi i uvodni video (MP4/WebM) | Filip |
| sajt/ | Izvorni kod sajta | Vuk |

Nazive fajlova pišite malim slovima, bez razmaka i srpskih slova (npr. commodore-64.jpg), da bi ih sajt mogao direktno da koristi.

## Kako se radi

**Korak 1.** Prihvatite poziv za saradnju (stiže na mejl vezan za GitHub nalog) i klonirajte repozitorijum: git clone https://github.com/vuklaketic/multimediji-digitalni-muzej.git

**Korak 2.** Svako radi u svom folderu, da ne bi dolazilo do konflikata.

**Korak 3.** Pre rada povucite izmene (git pull), a posle rada ih pošaljite (git add ., git commit -m "kratak opis", git push).

**Korak 4.** Velike fajlove (sirovi video, PSD, projekti iz Premiere-a) ne stavljajte u repozitorijum. Čuvajte ih na zajedničkom drajvu, a ovde samo finalne, izvezene verzije.
