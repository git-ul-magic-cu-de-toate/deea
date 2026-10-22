# DEEA (Dispozitve electronice si electronica analogica)


## Electronica Analogica

- **Definitie**: Electronica analogica se ocupa cu
`semnale continue` in care nivelurile de tensiune sau curent 
variaza intr-un mod continuu si nelimitat.

- **Semnal analogic**: Un semnal analogic poate avea orice valoare
intr-un anumit interval. De exemplu, tensiunea si curentul pot varia
in mod continuu, intre valorile minime si maxime. Semnalele 
analogice au `o infinitate de valori`.

- **Reprezentare**: Valorile semnalului sunt reprezentate printr-o
`variabila continua`, spre exemplu `timpul`

- **Exemple**: semnale audio, semnale video, senzori analogici


## Electronica Digitala

- **Definite**: Electronica digitala se ocupa cu `semnale discrete`

- **Semnale discrete**: Un semnal digital ia doar
`un set finit de valori`. Aceste valori pot fi, 0 si 1 `biti`,
reprezentand starea de logica binara.

- **Reprezentare**: Valorile semnalului sunt reprezentate printr-o
variabila discreta, cum ar fi o succesiune de impulsuri sau tensiune
definite.

- **Exemple**: computere, comunicatii digitale, memorie digitala



| Caracteristica | Semnal `anlogic` | Semnal `digital` |
| -------------- | ---------------- | ---------------- |
| Reprezentare   | continua         |  discreta        |
| Variabila      | infinita         |  finita          |






[site util: Bazele electronici](https://sites.google.com/site/bazeleelectronicii/cuprins)
[site util: Electronics Tutorials](https://www.electronics-tutorials.ws/)



# Rezistor (rezistenta)
Un rezistor este un dispozitiv electronc pasiv proiectat sa ofere o anumita
rezistenta la trecerea curentului electric.
Rezistenta electrica este o masura a dificultatii cu care curentul trece printr-un
material.


Cand trece curent electric printr-un rezistor,
acesta se incalzeste si **produce caldura**,
proces cunoscut sub numele de **efect Joule**, descris de **legea lui Joule**:
`P = I^2 * R` (puterea disipata de un rezistor).


Rezistoarele sunt utilizate in circuite electronice din motive precum:
- controlul curentului
- divizor de tensiune
- generare de caldura
- stabilizarea tensiunii
- corectarea impendantei
- ajustarea sau calibrarea circuitelor


Gruparea rezistoarelor se face
- in serie
  1. **intensitatea (I)**   : aceasi pentru toate
  2. **tensiunea (V)**      : tensiunea totala este suma tensiunilor pe fiecare rezistor
  3. rezistenta echivalenta : `Re = R1 + R2 + ...`
  ![gruparea rezistentelor in serie](https://www.electricalc.ro/images/Gruparea%20serie.jpg)

- in paralel
  1. **intensitatea (I)**  : intensitatea totala este suma intensitatilor pe fiecare rumura in parte
  2. **tensiunea (V)**     : aceasi pentru toate
  3. rezistenta echivalent : `1/Re = 1/R1 + 1/R2 + ...`
  ![gruparea rezistentelor in paralel](https://www.electricalc.ro/images/gruparea%20paralel.jpg)



Legea lui Ohm: ``` U = I * R```


Rezistoarele fizice au o serie de benzi colorate care indica rezistenta acestor:
[calcularea valorii rezistentei in functie de benzi](https://eprofu.ro/cc/cc.html)


![cod culori rezistenta](https://seguidores.online/wp-content/uploads/2023/09/codigo-de-colores-de-resistencias.png)


| Culoare    | Prima Cifra | A Doua Cifra | Multiplicator | Toleranta  |
| ---------- | ----------- | ------------ | ------------- | ---------- |
| Negru      |      0      |       0      |     x 1       |     -      |
| Maro       |      1      |       1      |     x 10      |   +- 1%    |
| Rosu       |      2      |       2      |     x 10^2    |   +- 2%    |
| Portocaliu |      3      |       3      |     x 10^3    |   +- 3%    |
| Galben     |      4      |       4      |     x 10^4    |   +- 4%    |
| Verde      |      5      |       5      |     x 10^5    |   +- 0.5%  |
| Albastru   |      6      |       6      |     x 10^6    |   +- 0.25% |
| Mov        |      7      |       7      |     x 10^7    |   +- 0.1%  |
| Gri        |      8      |       8      |     x 10^8    |   +- 0.05% |
| Alb        |      9      |       9      |     x 10^9    |     -      |
| Auriu      |      -      |       -      |     x 10^-1   |    +- 5%   |
| Argintiu   |      -      |       -      |     x 10^-2   |    +- 10%  |
 


[Cum functioneaza rezistorul?](https://youtu.be/DYcLFHgVCn0)


## Divzor de tensiune (rezistor / rezistenta)
Divizorul de tensiune presupune **gruparea in serie** a rezistoarelor.
Un divizor de tensiune simplu consta in doua rezisotare conectate in serie
intre doua puncte, iar tensiunea de iesire este preluata de-a lungul uneia dintre rezistoare.

![divizor de tensiune](https://www.electrokits.ro/wp-content/uploads/2021/04/divizorul-de-tensiune-divizorul-de-curent.jpg)





# Ligile lui Kirchhoff
- Legea 1 : intr-un nod de circuit, suma algebrica a `curentilor` este `0`
- Legea 2 : intr-un ochi de circuit suma tensiunilor generatore este egala cu
            suma caderilor de tensiune


`U = R * I`

# Dioda
O dioda este un dispozitiv electronic cu doui electrozim numit `anod (A)` si `catod (K)`.
Dioda permite trecea curentului electric intr-o singura directie si prezinta
o rezistenta electrica foarte mica (**conductie**) in aceasta directie,
iar in directia opusa prezinta o rezistenta foarte mare.

Functia principala a diodei este sa permita **fluxul unidirectional al curentului**
intr-un circuit si sa previna trecerea curentului in directia opusa.

Diodele cu `jonctiune PN`:
- regiunea de tip `P (pozitiv)`: **goluri**, de obicei **anodul** (de obicei pinul mai lung)
- regiunea de tip `N (negativ)`: **electroni**, de obicei **catodul** (de obicei piciorul mai scurt)


Tipuri de diode:
- Dioda redresoare
- Dioda **Zenner**
- Dioda Varicap
- Dioda Shottky
- Dioda Tunnel
- Fotodioda
- LED-ul (Light Emitting Diode)

[Cum functioneaza dioda?](https://youtu.be/Fwj_d3uO5g8)

![tipuri diode](https://www.creeaza.com/files/electronica-electricitate/986_poze/image009.gif)

![dioda](https://hobbytronica.ro/wp-content/uploads/2013/09/Simbolizarea-principalelor-categorii-de-diode.jpg)



## Dioda redresoare
Curentul poate sa treaca doar printr-un singu sens
Are doua stari:
- Conductie directa (circula curent): `Id > 0A, Ud = 0.6V`
- Blocata (nu circula curent): `Id = 0A, Ud < 0.6V`


## Dioda Zenner
Curentul poate circula in ambele sensuri

Are trei stari:
- conductie inversa (circula curent in sens opus): `Ud = -Udz, Id < 0`
- blocata (nu circula curent): `-Udz < Ud < 0.6, Id = 0`
- conductie directa (circula curent): `Ud = 0.6V, Id > 0`

unde `Udz` este o tensiune specifica fiecarei diode Zenner,
difera in functie de constructia diodei








# Tranzistorul
Tranzistoarele sunt componente semiconductoare utilizate pentru a amplifica,
comuta si controla cemnale electronice in ciruitele electronices

- `B` = baza (are intotodeauna acel T intors)
- `E` = emitor (are sagetuta care pleaca dinspre emitor / vine spre emitor)
- `C` = colector

``` Ie = Ib + Ic ```

``` Ic = beta * Ib ```


[Cum functioneaza tranzistorul?](https://youtu.be/J4oO7PT_nzQ)

![pnp vs npn transitor](https://cdn1.byjus.com/wp-content/uploads/2020/02/Transistor-2.png)

![pnp vs npn transitor current flow](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToRNawqQKr3gLQ1-1Q7Bl3FuU24ouWP0J3Y49_z8nR2NMRb_4SMHnQwmnTTTwlhUaS1IE&usqp=CAU)



## Tranzstorul PNP
|       \        | tranzistor `PNP`                                |
| -------------- |-------------------------------------------------|
| `C` (colector) | sectiune `P (pozitiv)`, goluri, iese curent     |
| `B` (baza)     | sectiune `N (negativ)`, electroni, iese curent  |
| `E` (emitor)   | sectiune `P (pozitive)`, goluri, intra curent   |


## Tranzstorul NPN
|       \        |              tranzistor `PNP`                          |
| -------------- | ------------------------------------------------------ |
| `C` (colector) | sectiune `N (negativ)`, electroni, intra curent curent |
| `B` (baza)     | sectiune `P (pozitiv)`, goluri, intra curent           |
| `E` (emitor)   | sectiune `N (negativ)`, electroni, iese curent         |



## Regiuni de functionare
`RAN` = Regiunea (de functionare) Activa Normala
      => `Ue < Ub < Uc`
`RAI` = Regiunea (de functionare) Activa Inersa


| \   |         `RAN`    |       Saturatia  |       `RAI`      |      Blocat      |
| --- | ---------------- | ---------------- | ---------------- | ---------------- |
|`NPN`| Ube > 0, Ucb < 0 | Ube > 0, Ucb < 0 | Ube < 0, Ucb < 0 | Ube < 0, Ucb > 0 |  
|`PNP`| Ueb > 0, Ubc < 0 | Ueb > 0, Ubc < 0 | Ueb < 0, Ubc < 0 | Ueb < 0, Ubc > 0 |


## PSF (Punctul Static de Functionare)
Punctul static de functionare se refera la starea de repaus sau la conditia
de functionare stabila a unui dispozitiv electronic intr-un circuit in absenta
semnalelor de intrare variabile.

Este momentul in care un dispozitiv, cum ar fi un `tranzistor` sau un `amplificator`,
se afla intr-un stare constanta, fara variatii semnificative in semnalele de intrare / iesire.

`f(E, 0), ui = 0`




# Bobina
Bobina se mai numeste `inductor` sau `bobina de inductie`
(in engleza `inductor`, `induction coil`)

Termenul de **inductie** se refera la procesul de inducere sau producere
a unei forte electromotoare sau a unei tensiuni intr-un circuit electric ca rezultat
al **variatiei fluului magnetic** in acel circuit, fenumen cunoscut sub numele de
inductie electromagnetica.

O `bobina` este un component electronic pasiv (nu amplifica sau nu genereaza semnale 
electronice), adesea infasurata in jurul unui miez magnetic.

Aceasta este utilizata pentru **stocarea energiei** sub forma de camp magnetic
atunci cand un curent electric trece prin ea.


``` U(t) = L * dl(t) / dt ```


[Cum functioneaza bobina?](https://youtu.be/KSylo01n5FY)

![bobina de inductie](https://ce8dc832c.cloudimg.io/cdn/n/n@72165f50f5c3830151c014f3fd132974c2441391/_cs_/2020/10/5f996ffa6593f/scheme_3.png)

![bobina si sursa ideala de curent](https://s3-us-west-2.amazonaws.com/courses-images-archive-read-only/wp-content/uploads/sites/222/2014/12/20110918/Figure_24_09_01.jpg)





# Condenstatorul (in engleza: capacitor)
Un condensator este un component electronic pasiv care este folosit pentru
stocarea si eliberarea de energie electrica intr-un circuit.



Condensatorul **permite trecerea curentului alternativ**
si **blocheaza curentul continuu**.

Acesta este format din doua placi conductive separate printr-un 
material dielectric (izolator), care impiedica fluxul direct de curnet intre
cele doua placi. Principalalee caracteristici ale condensatoarelor includ:

- `Capacitate`: capacitatea unui condensator, masurata in `farazi (F)`,
reprezinta capacitatea acestuia de a stoca sarcina electric intr-o anumita tensiune.
Cu cat cpacitatea este mai mare, cu atat va stoca mai multa energie

- `Tensiune Nominala`: condensatorul are o tensiune nominala maxima (V) pe care o
poate suporta in mod sigur. Depasirea acestei tensiuni poate deteriora condensatorul

- `Aplicatii`: filtrarea in sursele de alimentare, stocarea de energie in flash-urile
foto si circuitelor de decuolare in cirucitele electronice

[Cum functioneaza un condensator?](https://youtu.be/X4EUwTwZ110?t=339)


Ecuatie condensator:
``` I(t) = C * dU(t) / dt ```



# Curent alternativ `~`
Simbolul `~` intr-un cerc este un simbol stantdard folosit pentru a reperezenta
**curentul alaternatic (AC)**.

Curentul alternativ este un tip de curent electric in care directia
fluxului de curent se inverseaza periodic, osciland intre valori pozitive si negative.

Un exemplu tipic este curentul alternativ furnizat in locuinte, care are
forma de **unde sinusoidala**. Aceasta inseamna ca nivelul de curent creste si scade
intr-un mod periodic, generand o forma de unda car se repeta in timp.

Formula generala a acestei ecuatii pentru un curent alternativ sinusoidal este:

``` I(t) = Imax * sin(w * t + fi)```

- `I(t)` = reprezinta curentul in functie de timp
- `Imax` = amplitudinea, valoarea maxima a curentului
- `w` = frecventa angulara a curentului alternativ
  1. ``` w = 2 * pi * f ```, f = frecventa
- `t` = timpul
- `fi` = unghi de faza, faza initiala a undei sinusoidale
  



# Amplificator Operational (A.O)
![imeagine amplificator operational](https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/Op-amp_symbol.svg/180px-Op-amp_symbol.svg.png)

[ce este amplificatorul operational?](https://eprofu.ro/docs/electronica/analogica/circuite/3amplificatoare-operationale.pdf)


In mod uzual, un amplificator operational are doua borne de intrare si
una singura de iesire.
- `V+`: intrarea fara inversare
- `V-`: intrarea cu inversare
- `Vout`: semnalul de iesire
- `Vs+` sau `Vcc`: alimentarea cu tensiune pozitiva
- `Vs-` sau `Vee`: alimentarea cu tensiunea negativa

`Vcc` = Tensiune de Colector-Colector = tensiunea de alimentare pozitiva
`Vee` = Tensiunea de Emitor-Emitor = tensiunea de alimentare negativa

Alimentarea simetrice cu `Vcc` si `Vee` permite semnale pozitive si negative
sa fie amplificate in mod corespunzator.


``` Uo = A * (V+ - V-) ```



## Reactie Negativa (Amplificator Operational)

![imagine AO inversor](Amplificatoare-Operationale/AO-reactie-negativa.png)

Reactia negativa este o metoda prin care o parte din tensiune de iesire a unui AO
este adusa la **intrarea inversoare**, in antifaza fata de semnalul de intrare.

Deoarece castigu in tensiune a AO este foarte mare, utilitatea AO
fara reactie negativa este extrem de restransa.

Pentru AO cu rectie negativa, `V+ = V-`
(tensiunile care intra in amplificator sunt egale)



## Tipuri de circuite cu AO
Exemple de circuite de **Amplificatoare Operationale**:
- neivnersor
- inversor
- repetor
- sumator
- log
- exp



### Amplificator Operational Neinversor
Tensiunea de intrare intra in amplificator prin intrarea neinversoare, cea cu `+`.

![imagine AO neinversor](https://lh4.googleusercontent.com/f7gN0eW2JMk8Tu8cJx2Ewng3fX0HS7P03xB36yM_Lpw43dtXBi6jal-5TJxn0BR1QZJinJK2N-a0-hnjBESSt0_e_u53evIHMDPPp-JRPAxK1DTc=w1280)


### Amplificator Operational Inversor
Tensiunea de intrare intra in amplificator prin intrarea inversoare, cea cu `-`.

![imagine AO inversor](https://lh3.googleusercontent.com/LqZWeQUsyCv_5o6xdyfMNZUGg677F9WTcy1VbN-1KC2boLlgyD0ejBtGcAsgxBNYsYooIj1_SWZqRHJPCgMsylugOygI4jnQSH8SAb_0a8FKWw0c=w1280)



### Amplificator Operational Repetor de Tensiune
![imagine AO repetor](Amplificatoare-Operationale/AO-repetor.png)

Este un circuit liniar, prin care
semnalul de iesire al AO-ului este adus inapoi in amplificator,
**la intrarea inversoare `-`**, fara alte modificari.



### Amplificator Operational Sumator
[amplificator operational SUMATOR](https://sites.google.com/site/bazeleelectronicii/home/amplificatoare-operationale/4-amplificator-sumator)


Acestea pot fi de doua tipuri, in fuctie de intrarea circuitului:
- Daca tensiunile de intrare sunt conectate la `+`, avem un AO neinversor sumator
adica semnalul de iesire va fi suma tensiunilor de intrare, cu **acelasi semn**
![AO sumator neinversor](Amplificatoare-Operationale/AO-sumator-neinversor.png)

- Daca tensiunile de intrare sunt conectate la `-`, avem un AO inversor sumator,
adica semnalul de iesire va fi suma tensiunilor de intrare, cu **semn schimbat**
![AO sumator inversor](Amplificatoare-Operationale/AO-sumator-inversor.png)



### Amplificator Operational Logaritmic
![imagine 1 AO log T](Amplificatoare-Operationale/AO-logaritmic-(tranzistor).png)
![imagine 2 AO log D](Amplificatoare-Operationale/AO-logaritmic-(dioda).jpeg)


### Amplificator Operational Exponential
![imagine 1 AO exp T](Amplificatoare-Operationale/AO-exponential-(tranzistor).png)
![imagine 2 AO exp D](Amplificatoare-Operationale/AO-exponential-(dioda).jpeg)











[simulator circuit electric](https://www.tinkercad.com/learn/circuits)
