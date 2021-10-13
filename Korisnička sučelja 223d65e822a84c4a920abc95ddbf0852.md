# Korisnička sučelja

## FESB, 2021/22

*Pripremili: Ivan Kuliš i Mario Čagalj*

Osnovni cilj kolegija je upoznati studente sa važnim aspekatima procesa dizajna (sučelja) usmjerenog krajnjim korisnicima. Studenti će realizirati praktičan projekt u okviru kojeg će primjeniti odgovarajuće principe *dobrog dizajna*. Također imati priliku upoznati koristiti moderne tehnologije/alate za dizajn i implementaciju *front-end* (i *back-end*) aplikacija ([React.js](https://reactjs.org/), [Next.js](https://nextjs.org/), [Figma](https://www.figma.com/), [Jamstack](https://jamstack.org/), headless CMS, Git i druge).

U ovom repozitoriju ćemo objavljivati upute, *code snippet*-e, konfiguracijske skripte, i razne sugestije s ciljem povećanja produktvnosti studenta tijekom rada na projektu.

## Uvod

Izrada projekta odvijati će se u nekoliko faza kako je to prikazano na slici u nastavku. Kako možemo vidjeti na slici, dizajn je iterativni postupak u kojem iteriramo faze *dizajna*, *implementacije* i *evaluacije*.

![interface_design_process.png](Korisnička%20sučelja%20223d65e822a84c4a920abc95ddbf0852/interface_design_process.png)

Iterative design process (source: [Saul Greenberg](http://saul.cpsc.ucalgary.ca/pmwiki.php/HCIResources/HCILectures))

Ugrubo, razlikujemo sljedeće faze u ovom procesu:

1. **Razumijevanje zadaća i korisnika koje sustav/aplikacija treba podržati**
    
    > Vi niste tipičan korisnik. Ne znate koje zadaće su važne korisnicima. Da bi bili sigurni da imate dobar opis zadaća trebate ih evaluirati zajedno s korisnicima.
    
    *Features* nisu zadaće koje korisnik treba obaviti. Gomilanjem *feature*-a vaša aplikacija neće biti bolja već upravo suprotno. Razumijevanje stvarnih potreba korisnika i stvarnih zadaća koje korisnik treba izvršiti ključ je uspjeha.
    > 
2. **Izrada *low-fidelity* i *high-fidelity* prototipa i njihova evaluacija**
    
    > Pokušajte odoljeti programerskom porivu da u ovoj fazi otvorite vaš preferirani editor i započnete programirati. U ovoj fazi razvoja projekta vaš dobar prijatelj su olovka i papir, razni grafički editori (npr. [Excalidraw](https://excalidraw.com/)), te alati za brzu izradu prototipa (npr. [Figma](https://www.figma.com), [Balsamiq](https://balsamiq.com/wireframes/), [Sketch](https://www.sketch.com/), [inVision](https://www.invisionapp.com/), [Draw.io](https://drawio-app.com/)).
    > 
    > 
    > Provedite evaluaciju vašeg prototipa s kolegama ili profesorom i popravite uočene *usability bug*-ove.
    > 
3. **Implementacija prototipa i njegova evaluacija**
    
    U ovoj fazi konačno možete otvoriti svoj preferirani editor i započeti s implementacijom.
    
    > Nemojte zaboraviti na evaluaciju u ovoj fazi (provedite heurističku evaluaciju vašeg produkta i/ili *usability testing* sa stvarnim korisnicima).
    > 

## Što se očekuje od studenta

Student će razviti odgovarajuću web aplikaciju korištenjem prethodno navedenih alata. Student će na projektu raditi u grupi sa još jednim kolegom ili samostalno. Od gore navedene tri faze iterativnog procesa dizajna, student će realizirati sljedeće dvije:

- **Fazu 2**: izrada i evaluacija *low-fidelity* i *high-fidelity* prototipa
    - Olovka i papir i/ili [Figma](https://www.figma.com/) (za *high-fidelity*)
- **Fazu 3**: implementacija sustava i njegova evaluacija
    - [Next.js](https://nextjs.org/)

## Zadaće i korisnici koje aplikacija treba podržati

### Zahtjevi i zadaće

- Vaša aplikacija će se koristiti iz web preglednika
- Aplikacija će se koristiti na uređajima razičite veličine (*smartphones*, tableti, laptopi i desktop računala)
- Korisnik može pretraživati/filtrirati produkte ili usluge
- Broj produkata/usluga koje nudite putem web aplikacije veći je od 20
- Korisnik će koristiti aplikaciju kao gost ili će se logirati u vlastiti profil
- Broj *javnih* stranica (one stranice koje ne zahtjevaju logiranje u sustav) je 5
- Jedna od javnih stranica je blog (blog mora sadržavati minimalno 20 *postova* koje mogu uključivati slike, videa, *code snippet*e)

### Korisnici

- Vaša aplikacija namjenjena je širokom krugu korisnika
- Baza korisnika uključuje i osobe čija informatička pismenost ne mora nužno biti na vašoj razini
- Korisnici tako mogu biti i *osobe starije životne dobi* (60 i više godina) koje sporo tipkaju, imaju slabiji vid, imaju slab sluh

## Demonstracija projekta - tehnički zahtjevi

- Studenti će pokazati optimiziranu produkcijsku verziju projekta.
- Produkcijska verzija projekta treba biti postavljena *online* na odgovarajuću *cloud* platformu ([Netlify](https://www.netlify.com/) ili [Vercel](https://vercel.com))
- Studenti će analizirati performanse aplikacije korištenjem sljedećeg Googleovog servisa: [https://web.dev/measure](https://web.dev/measure/)

## Praktične vježbe i smjernice

U svrhu upoznavanja sa navedenim tehnologijama, u uvodnom dijelu labova student će izraditi jednostavnu demo stranicu pri čemu će koristiti navede tehnologije.

### Za samostalan rad

[Uvod u Git protokol](https://github.com/kula124/HCi_2020_Fresh/blob/master/git-workflow.md)

[JavaScript za rad s React-om](./Korisnička%20sučelja%20223d65e822a84c4a920abc95ddbf0852/Lab%201%20-%20Setting%20up%20GitHub%20repository%207edde9826f744c9da4aff17ac321e5d4.md)

### Za rad u laboratoriju

[Lab 1 - Setting up GitHub repository](Korisnic%CC%8Cka%20suc%CC%8Celja%20223d65e822a84c4a920abc95ddbf0852/Lab%201%20-%20Setting%20up%20GitHub%20repository%207edde9826f744c9da4aff17ac321e5d4.md)