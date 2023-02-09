# 11-CSS--Osnove-stilizovanja-blokova-TEORIJA

BLOK ELEMENTI DIVOVI: DISPLAY: INLINE-BLOCK, FLEX

-Divovi imaju display blok i zauzimaju celu duzinu parrent elementa  <br>
-Blokovni elementi koji imaju display block mehanizam su tako napravljeni  da ne mogu da se stekuju jedan pored drugog
vec, jedan ispod drugog. To je osobina blokovnih elemenata. <br>
<br>
- Da bi blokovni elemnti bili jedan pored drugog, najstarijji nacin, koji bi mogao da se koristi je da se svaki kvadrat
koji imamo na nasem ekranu index2.html, ponasao kao jedno veliko slovo.  <br>

- Slova u tekstu se redjaju jedna pored drugog. Na primer: Branko. Svako slovo se ponasa kao inline element! <br>
- 
- Da bi promenili nacin prikaza divova da ne budu blokovni, nego da budu inline blokovni moramo da koristimo
DISPLAY osobinu: inline-block; Onda ce se divovi poredjati jedan pored drugog kao sto bi se redjao i text! <br>

DISPLAY: INLINE BLOCK cini da se dati elementi ponasaju kao reci i 
	slova u tekstu i da izmedju njih postoje razmaci ako imamo bar jednu belinu <br>

Da bi napravili da nema tih praznina. Napravicemo novi div i ta 3 diva koji smo napravili stavicemo u taj novi div. <br>
Tom novom divu dodelicemo novu klasu na pr holder. <br>
Klasi holder stavljamo: <br>
display: flex <br>
width: 450px <br>
height: 150px <br>
<br>
a ostalim divovima uklanjamo display: inline-block<br>
stavljamo <br>
border: 2px solid black; <br>
width: 150px; <br>
height:150px <br>
flex-grow:1 <br>

flex-grow(Ukratko: Ako imamo 3 elementa u nizu i prva dva stavimo da su flex-grow: 1, a trećem stavimo da je flex-grow: 3, <br>
 onda je ukupan zbir 1+1+3 = 5, <br>
 tako da će prva dva biti 1/5 širine, a treći 3/5 širine.) <br>

FLEX: neka ova 3 diva imaju fleksibilne dimenzije na osnovu holdera u kojem se nalaze tj diva sa klasom holder <br>
Ako imamo flex dimenzije, to znaci da nam width i height nisu potrebni. Mozemo da ih obrisemo. Rezultat ce biti isti. <br>
