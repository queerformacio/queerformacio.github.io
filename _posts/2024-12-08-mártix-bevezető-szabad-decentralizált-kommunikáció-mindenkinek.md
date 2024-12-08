---
layout: blog
title: Mártix bevezető - szabad, decentralizált kommunikáció mindenkinek
date: 2024-12-08T21:10:00.000Z
author: anonymous
tags: matrix online biztonság lgbt biztonságos tér
---
## Mi a mátrix

A [mátrix](https://matrix.org) egy nyitott standard és ehhez kapcsolódó ökoszisztéma, melynek
segítségével tudunk online beszélgetni családdal, barátainkkal, vagy csak
internetes társainkkal szabadon, a profitéhes cégek cenzúrája nélkül. Szabad
és nyitott forráskódú szoftverre épül, ingyenes használni, és decentralizált,
azaz nem egy központi cég szerverein fut, hanem több, kisebb cég, közösség
vagy privát emberek szerverei alkotta hálózaton.

## Hogy működik?

Hasonlít az emailhez -- minden felhasználó egy szerverhez/szolgáltatóhoz
kapcsolódik (mint például email esetében gmail, outlook, protonmail, tuta...).
A különböző szolgáltatók felhasználói tudnak kommunikálni természetesen más
szolgáltatók felhasználóival is. Ellentétben az emaillel viszont, a mátrix
valós idejű kommunikációra van kitalálva, chat alkalmazásokhoz, mint a Discord,
Slack, Messenger vagy Microsoft Teams jobban hasonlít.

## Hol kell regisztrálni?

Mivel nincs egy központi szerver, ezért először egy szolgáltatót kell
választani (angolul a `homeserver` kulcsszó). Hála a föderációnak ez a
választás nem befolyásolja kivel tudsz kommunikálni, ezért ne aggódj
emiatt túlságosan. Személyesen az [envs.net](https://element.envs.net/), a tchncs.de[3] vagy pedig
a [joinmatrix.org](https://tchncs.de/matrix) listájáról egyik szolgáltatót választanám. A [grin.hu](servers.joinmatrix.org)
egy magyar szolgáltató szintén egy megbízható választás. A legtöbb kliens
alapból a matrix.org szolgáltatót választja, de ez nem ajánlott azért mert
túl tud terhelve lenni, továbbá ha mindenki ugyanarra a szerverre regisztrál,
az csökkenti a föderációt.

## Barátok, szobák, terek

A mátrix chat szobákra épül. Nincsenek megkülönböztetve a privát üzenetek,
csoportok és nyilvános szobák annyira mint más platformokon. A privát üzenetek
lényegében kettő emberes szobák.

Egyes szobáknak van nyilvános címük, mellyel felfedezhetőek (például
#magyar-lgbt:tchncs.de a mi szobánk, vagy a #community:the-apothecary.club egy
nemzetközi LGBTQ+ szoba). Ezekbe bárki be tud lépni aki ismeri a szoba címét.
Más szobákba meghívó linkkel lehet belépni, vagy pedig ha egy ismerős egyenesen
meghív, a kliensen belül.

A terek egy relatív új mátrix fogalom, mely több szobát csoportosít egybe,
hasonlóan discord szerverekhez, vagy Slackhez. Ellentétben discorddal,
kevésbé egyesített, mert az összes szobának a tereken belül más tagjai,
adminjai, szabályai lehetnek, továbbá egy szoba egyszerre több térben is lehet.
A különbségek ellenére a terek még mindig hasznosak tudnak lenni ha egy
közösségnek több chat szobára van szüksége.

## Titkosítás

A föderáción kívül ez egy másik előnye mátrixnak olyan platformokkal szemben,
mint a discord vagy a messenger, viszont kisebb fejfájásokat tud okozni, ha
valaki nem érti. Ha be van kapcsolva egy mátrix szobában a titkosítás, akkor
az azután küldött üzenetek végpontból végpontba titkosítva lesznek, szóval
csak a szoba tagjai tudják elolvasni, a szolgáltatók nem. Közhittel ellentétben
nem túl sok platform implementálja ezt (telegram sem!), ezért ez egy jó
tulajdonsága mátrixnak, viszont hátránya, hogy tudatában kell lenni, hogy
minden kliensnek szüksége van a titkosítási kulcsokra is. A titkosítási
kulcsokat kétféle módon tud egy kliens megszerezni: verifikációval és
bizonsági kulcs backup opción keresztül.

Amikor új klienssel jelentkezel be a felhasználódba első alkalommal,
ajánlott hogy nyiss meg egy meglévő klienset is, vagy a böngészőt, amivel
regisztráltál maradjon nyitva. Megjelenik egy figyelmeztetés, ami megkér
hogy verifikáld az új klienst. A verifikálás során a titkosítási kulcsok
a régi kliensből az új kliensbe át lesznek másolva, ezért is egy fontos lépés
ezt megtenni.

A biztonsági kulcs backup opció a beállításokon keresztül történik.
Megtalálható a "security key" menüben, itt exportálhatod a kulcsokat.
Ha ezt a lépést megteszed, akkor még akkor is hozzáférhetsz majd a titkosított
üzeneteidhez ha elveszted a hozzáférést az összes klienshez (mert ugye akkor
nem tudsz már új klienseket meglévő kliensekkel verifikálni).

## Kivel tudok mátrixon beszélgetni?

- Magyar LGBT szoba [#magyar-lgbt:tchncs.de](https://matrix.to/#/#magyar-lgbt:tchncs.de)
- Magyarul beszélő szobák mátrix tér [#magyarul:matrix.org](https://matrix.to/#/#magyarul:matrix.org)
- [Népszerű (angol) szobák](https://joinmatrix.org/guide/popular-rooms/)
