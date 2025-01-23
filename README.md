# Markdown Cheat Sheet
Köszönöm a látogatást [Markdown segédlet](https://www.markdownguide.org!)

Ez a leírás gyors áttekintést nyújt az összes Markdown szintaktikai elemről.Nem tud minden esetet lefedni, ezért ha további információra van szüksége ezen elemek bármelyikével kapcsolatban, tekintse meg a referencia útmutatókat [alapvető szintaxis](https://www.markdownguide.org/basc-syntax/) és [bővített szintaxis](https://www.markdownguide.org/extended-syntax/).

## Fejezetcímek
# H1
## H2
### H3
# **Félkövér**
__félkövér szöveg__

## *Dőlt*
_dőlt szöveg_

## Bekezdés, sortörés
Az elektromos áram munkáját a feszültség és az áramerősség értelmezése alapján számíthatjuk ki. **I** erősségű áramnál **t** idő alatt a vezetőn __I*t__ töltés halad át és a vezető végpontjai között **U** nagyságú _FESZÜLTSÉG_ van. A végzett munka a töltésnek és a feszültségnek szorzata: 

__W=U*Q=U*I*t=P*t__

A váltakozó áram teljesítménye (látszólagos teljesítménye):P=U<sub>eff</sub>I<sub>eff</sub> (Ha szükséges a képletekbe behelyettesíthetjük Ohm törvényét: **U=R*I** ). Ha a feszültséget **Volt**ban, az áramerősséget **Amper**ben adjuk meg, akkor az elektromos teljesítményt **Watt**ban kapjuk.  
Tehát az átváltás: __1 Watt=1 Volt* 1 Amper__. (1 W=1 V* 1 A)
## Idézet
>_Idézet szöveg dőlten_
## Számozás
1. Első elem
2. Második elem
3. Harmadik elem
## Felsorolás
+ Első elem
- Második elem
* Harmadik elem
## Kód
`code`

## Vízszintes vonal
Link
[segédlet](https://www.markdownguide.org)
## Kép
![Pingvin](https://www.markdownguide.org/assets/images/tux.png "Pingvin")
## Táblázat

| Szintakszis | Leírás|
|---------|---------|
| Fejléc | Cím|
| Bekezdés | Szöveg|

## Táblázat középre

| Szintakszis | Leírás|
|:---------:|:---------:|
| Fejléc | Cím|
|Bekezdés | Szöveg|
## Kódblokk
``` python
{
  "keresztnev": "János",
  "vezeteknev": "Szabó",
  "eletkor": 25
}
```
## Lábjegyzet
Itt van egy mondat lábjegyzettel.[^1]

[^1]: Ez a lábjegyzet.
## Definiciós lista
fogalom:
fogalom leírása
## Áthúzás
~~The world is flat.~~
## Feladatlista
- [x] Megírni a sajtóközleményt
- [] Frissíteni a weboldalt
- [] Felvenni a kapcsolatot a médiával
## Emoji
Ez olyan vicces! :joy:

(Lásd még [Emoji másolása és beillesztése](https://www.markdownguide.org/extended-syntax/ "#copying-and-pasting-emoji"))
