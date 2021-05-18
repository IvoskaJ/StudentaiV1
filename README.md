    Ankstesnės atliktos užduoties pagrindu susikurti naują repoziciją, t.y., visa git istorija iki v1.0 turi išlikti. Įprastinė procedūra būtų:
        Nusikopijuoti lokaliai (kompiuteryje) visą antrosios užduoties repoziciją (katalogą);
        Susikurti naują repoziciją GitHub'e.
        Pasikeiskite nusikopijuotos repozicijos nuotolinį adresą panaudojant git remote set-url origin komandą terminale:

    git remote set-url origin https://github.com/USERNAME/NAUJA_REPOZICIJA.git

        Nupushinkite nusikopijuotą repoziciją į GitHub'ą:

    git push -u origin master

    Realizuokite programą pagal rekomendacijas ir reikalavimus pateiktus aprašė. Manau suprantate, kad parėjus iš struktūros į klasę, reikės atlikti atitinkamus pakeitimus visame kode!

    Palyginkite abiejų Jūsų programų: naudojančios struct iš ankstesniojo darbo ir naudojančio class tipo Studentus iš dabartinės realizacijos spartą (veikimo laiką), naudojant vieną fiksuotą konteinerį, pvz. vektorių, pačią greičiausią dalijimo strategiją ir 100000 ir 1000000 dydžio failus. Gautus rezultatus aprašykite README.md faile.

    Atlikite eksperimentinę analizę priklausomai nuo kompiliatoriaus optimizavimo lygio, nurodomo per flag'us: O1, O2, O3 ir papildykite README.md failą gautais rezultatais su optimizavimo flag'ais.

    Padarykite v1.1 releasą pagal ankstesniame darbe aprašytus reikalavimus.
    
    tyrimų rezultatai:
    
    Vector class su -01 flag'u: 
   ![vectorClassflag1](https://user-images.githubusercontent.com/78845735/118675265-216aeb80-b803-11eb-96c4-b7d1ccbda3f2.png)
   
    Vector structure su -O1 flag'u:
   ![vectorStructFlag1](https://user-images.githubusercontent.com/78845735/118675335-33e52500-b803-11eb-8c95-ed08d8973d64.png)

    Vector class su -O2 flag'u
   ![vectorClassflag2](https://user-images.githubusercontent.com/78845735/118675565-5b3bf200-b803-11eb-8060-328be77aa986.png)

    
    Vector structure su -O2 flag'u
   ![vectorStructFlag2](https://user-images.githubusercontent.com/78845735/118675552-58410180-b803-11eb-86c2-fc1a5a2e00c3.png)
   
    Vector class su -O3 flag'u
   ![vectorClassflag3](https://user-images.githubusercontent.com/78845735/118675625-68f17780-b803-11eb-8de1-800d1c6b8b89.png)
   
    Vector structure su -O3 flag'u
   ![vectorStructFlag3](https://user-images.githubusercontent.com/78845735/118675672-71e24900-b803-11eb-9795-ed96508ce634.png)
    
    Tyrimuose galima matyti, kad studentai class greičiausiai veikė su -O3 flag'u, o struktura su -O1 flag'u


