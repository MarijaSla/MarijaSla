<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<h1><b>Uvod u statistiku   </b></h1>
<br>
<br>
<h2>Kombinatorika</h2> 
 
<br>
Predmet kombinatorike je raspoređivanje elemenata u konačnim skupovima i određivanje broja takvih raporeda. Koreni kombinatorike leže u drevnoj proslosti, u vremenu početka matematike i nauke uopšte. Tokom istorije, razvijala se sa drugim oblastima matematike. Bliže proučavanje  je počelo u XVII veku kada su se kombinatorna pitanja postavljala u vezi sa igrama na sreću. Danas se koristi u raznim oblastima matematike, kao što su algebra, teorija brojeva, geometrija itd. 
<br>
Pojmovi iz matematike koji se koriste u kombinatorici: 
<br>
<ul> 1. Faktorijel: n! = n*(n-1)*...*1 <br> </ul>
 <ul>2. Binomni koeficijent: <br> <ul> <img style="width:100px; max-width:98%" src="mnmr/1.png"> </ul> </ul>

 
Neke osobine binomnog koeficijenta: <br>
 <ul> <img style="width:150px; max-width:98%" src="mnmr/2.png"> </ul> 
 
Pri rešavanju kombinatornih zadataka gotovo uvek se sreću osnovne kombinatorne konfiguracije kao sto su permutacije, varijacije i kombinacije. 

<br>
<br>
<br>
<b>Permutacije bez ponavljanja</b>
 <br>
Permutacija bez ponavljanja skupa A koji ima n elemenata je svaki niz u kome se tačno po jadanput pojavljuju svi elementi skupa A. Broj takvih permutacija iznosi P(n)=n! 
<br>
<br>
<i>Primer</i>:  Na kolina načina 4 osobe mogu stati u red? 
<br>
Rešenje: Osobe možemo poređati u red na 4!=4*3*2*1=24 načina. 
<br>
<br>
<b>Permutacije sa ponavljanjem</b>
<br>
Neka je dat skup od m elemenata A={a1, a2 ,…, am}. Svaki niz dužine k1+ k2+…+ km=n u kome se element a1 pojavljuje tačno k1 puta, elementar a2 tačno k2 puta itd. se naziva permutacija sa ponavljanjem tipa k1, k2… km i njihov broje je 𝑛!/k1!∗k2!∗..∗km!
<br>
<br> 
<i>Primer</i>: Koliko se različitih šestocifrenih brojeva može sastaviti od cifara iz 1,2,2,2,3,3? 
<br>
Rešenje: Pošto su u pitanju šestocifreni brojevi n=6. Cifra 1 se pojavljuje jednom i zbog toga je  k1=1, cifra 2 se pojavljuje 3 puta što znaci da je je  k2=3, dok je je  k3=2. Iz toga sledi da je ukupan broj jednak  𝑃 = 6! 1!∗3!∗.2! . 
<br>
<br>
<b>Varijacije bez ponavljanja</b>
<br>
Varijacija bez ponavljanja k-te klase skupa A od n elemenata je svaki niz k međusobrno različitih elemenata i broj takvih nizova iznosi 
 <ul> <img style="width:200px; max-width:98%" src="mnmr/3.png"> </ul> 
 

<i>Primer</i>: Koliko ima trocifrenih brojeva koji se mogu obrazovati od cifara iz skupa A={1,2,3,4,5,6,7,8,9} tako da su sve cifre različite? 
<br>
Rešenje: Potrebne su nam 3 cifre i zbog toga je k=3, ukupan broj elemenata skupa je 9, zbog toga je n=9. Potrebno je da izračunamo varijacije bez ponavljanja klase 3 skupa koji ima 9 elemenata i to će iznositi <ul> <img style="width:150px; max-width:98%" src="mnmr/4.png"> </ul> 

<br>
<br>

<b>Varijacije sa ponavljanjem</b>
<br> 
Varijacije k-te klase skupa A od n elemenata pri čemu se elementi mogu ponavljati nazivaju se varijacije sa ponavljanjem i važi <ul> <img style="width:150px; max-width:98%" src="mnmr/5.png"> </ul> 

<i>Primer</i>:  Koliko ima trocifrenih brojeva koji se mogu obrazovati od cifara iz skupa A={1,2,3,4,5,6,7,8,9} ako znamo da se cifre mogu ponavljati? 
<br>
Rešenje: Potrebne su nam 3 cifre i zbog toga je k=3, ukupan broj elemenata skupa je 9, zbog toga jen=9. Potrebno je da izračunamo varijacije sa ponavljanjem klase 3 skupa koji ima 9 elemenata i to će iznositi<ul> <img style="width:120px; max-width:98%" src="mnmr/6.png"> </ul> 
 
<br>

<b>Kombinacije bez ponavljanja</b>
<br>
Kombinacija bez ponavljanja k-te klase skupa A koji ima n elemenata je svaki k-točlani podskup skupa A i iznosi <ul> <img style="width:150px; max-width:98%" src="mnmr/7.png"> </ul> 
<br>

<i>Primer</i>: U kutiji je 7 lopti. Na koliko načina možemo izabrati 4 lopte? 
<br>
Rešenje: Ukupan broj elemenata skupa je 7. Potrebne su nam 4 lopte. Iz toga zaključujemo da je n=7 i k=4. Lopte možemo odabrati na <ul> <img style="width:120px; max-width:98%" src="mnmr/8.png"> </ul>  načina. 

<br>
<br>
<b>Kombinacije sa ponavljanjem </b>
<br>
Ako se iz n-točlanog kupa A bira jedan po jedan element sa vraćanjem, i tako k puta, i ako nije bitan redosled, već samo koji element je i koliko puta izabran onda se rezultat izbora naziva kombinacija kte klase sa n elemenata sa ponavljanjem i iznosi <ul> <img style="width:150px; max-width:98%" src="mnmr/9.png"> </ul>  
 <br>

<i>Primer</i>: Na koliko načina turista od 10 razglednica može kupiti 3? 
<br>
Rešenje: Ukupan broj razglednica je n=10, njemu se potrebne k=3 razglednice. Iz toga sledi da je ukupan broj načina jednak <ul> <img style="width:120px; max-width:98%" src="mnmr/10.png"> </ul> 
 
 
<br>
<br> 

_____________________________________________________________________________________________
<br>
 <br>
Zadaci za vežbu: 
<ul>
1. Na koliko načina devet različitih knjiga možemo poređati u red? 
 <br>
 <ul>Rešenje:
<br> Ovo su permutacije bez ponavljanja. Devet knjiga možemo poređati na P(9)=9! načina. 
 
</ul>
</ul> 
<ul>
2. Na koliko načina iz kutije u kojoj se nalazi 5 kuglica možemo izvući 3? 
 <br>
<ul>Rešenje: 
<br>Ovo su kombinacije bez ponavljanja i 3 kuglice možemo izvući na <ul> <img style="width:120px; max-width:98%" src="mnmr/11.png"> </ul>  načina. 
 
</ul>
</ul> 
<ul>
3. Koliko ima osmocifrenih brojeva koji se satoje od cifara 0,1,2,3,4,5 ako se u svakom broju cifra 1 pojavljuje 3 puta, a ostale cifre po jednom ili se ne pojavljuju. (Napomena: Nula ne sme da se nalazi na prvom mestu) 
 
<ul>Rešenje:  
 
 <iframe width="560" height="315" src="https://www.youtube.com/watch?v=r1xWRG-B2OA" frameborder="0" allowfullscreen></iframe>


 </ul>
</ul> 
 <ul>
4. Na koliko načina može biti ocenjen 1 učenik na kraju školske godine ako ukupno ima 12 predmeta i ako: a) iz svih predmeta može dobiti ocene od 1 do 5? b) iz 2 predmeta ne može dobiti ocenu višu od 3 i iz 3 predmeta ne može dobiti ocenu nižu od 4? 
<br>
<ul> Rešenje: 
<br>a) Ukupan broj varijacija sa ponavljanjem je n<sup>k</sup> = 512.
<br> b) Iz dva predmeta ne može dobiti ocenu višu od tri 3<sup>2</sup> </ul>
 <ul>Iz tri predmeta ne može dobiti ocenu nižu od četiri 2<sup>3</sup> </ul>
 <ul>Iz preostalih sedam predmeta može dobiti bilo koju ocenu 5<sup>7</sup></ul>
 <ul>Ukupno može biti ocenjen na 3<sup>2</sup> ∗ 2<sup>3</sup> ∗ 5<sup>7</sup> načina. </ul>
</ul>
</ul>
 
<ul>
5. Iz grupe u kojoj se nalaze 4 muškarca I 3 žene treba odabrati 6 osoba tako da među njima budu bar 2 žene. Na koliko se načina to može odraditi? 
 <br>
<ul>Rešenje: 
<br>Možemo odabrati dve žene i četiri muškarca ili tri žene i tri muškarca.
<br> Dve žene i četiri muškarca biramo na <img style="width:120px; max-width:98%" src="mnmr/12.png"> načina. 
<br>Tri žene i tri muškarca biramo na <img style="width:120px; max-width:98%" src="mnmr/13.png"> načina.
<br> Ukupan broj načina na koji možemo odabrati grupu koji tražimo je 3+4=7. 
</ul>
</ul>
 
<ul>
 
6. U jednoj državi ne postoje 2 stanovnika sa jednakim brojem i rasporedom zuba. Koliko maksimalno može da bude stanovnika u toj državi? 
 <br>
<ul>Rešenje: 
<br>Čovek ukupno treba ima 32 zuba, i svaki može ili da ima ili da nema. Ukupan broj različitih varijacija iznosi 232. 
 
 </ul>
</ul>
 
<ul>
7. U restoranu se bira jelo koje se sastoji od predjela, supe, glavnog jela i dezerta. Postoje tačno 3 različiti vrste predjela, 2 vrste supe, 4 vrste glavnog jela i 10 vrsta dezerta. Na koliko načina gost može da odabere svoj obrok? 
 <br>
<ul>Rešenje: Predjelo možemo odabrati na 3 načina, supu na 2 načina, glavno jelo na 4 načina i desert na 10 načina. Ukupan broj različitih obroka iznosi: 3*2*4*10 = 240.
</ul>
</ul>
 
 
<ul>
