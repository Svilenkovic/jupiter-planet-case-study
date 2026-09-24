<a href="https://jupiterplanet.rs/"><img src="media/cover.jpg" alt="Jupiter Planet, naslovna strana na laptopu i telefonu" width="100%"></a>

# Jupiter Planet

Sajt za radionicu štampe i veza iz Kragujevca, sa konfiguratorom prednje i zadnje strane majice koji umesto korpe vodi do upita.

**[jupiterplanet.rs](https://jupiterplanet.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/jupiter-planet) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Jupiter Planet</td></tr>
  <tr><td><b>Delatnost</b></td><td>Štampa i vez na majicama i konfekciji</td></tr>
  <tr><td><b>Lokacija</b></td><td>Kragujevac</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana i konfiguratorom majica</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, SQLite, Fabric.js 5.1, vanilla JS</td></tr>
</table>

## O projektu

Jupiter Planet u Kragujevcu proizvodi, štampa i veze majice, polo majice, dukseve, trenerke i kape, od deset komada po dizajnu. Pre sajta je ceo posao išao preko poruka na Instagramu, a prepiska nije mesto gde se objašnjava razlika između DTF štampe i veza, niti se u njoj vidi kako logo stoji na leđima duksa. Cena zavisi od količine, materijala i tehnike, pa korpa sa fiksnim cenama nije ni dolazila u obzir.

Glavni deo sajta je konfigurator sa sedam odevnih predmeta, paletom boja i posebnim slojevima za tekst i logo na prednjoj i zadnjoj strani. Dizajn se seče po silueti samog komada, pa štampa može da ide bilo gde, čak i na rukav. Boja nastaje filterom množenja preko jedne bele fotografije, pa nabori i senke ostaju vidljivi u svakoj nijansi. Nov predmet se pojavi čim se slike njegove prednje i zadnje strane ubace u folder, bez diranja koda.

## Šta sam uradio

- U upitu stižu obe strane dizajna kao slike, veličine, količine i referentni broj, a vlasniku odmah ide mejl
- Kontrole za dodir: dugme za brisanje na samom objektu, vodilica za centriranje i platno koje prati širinu ekrana
- Podloga majice smanjena sa 1,36 MB na oko 85 KB u WebP formatu, a biblioteka za platno se učitava tek kad se skrolom dođe blizu konfiguratora
- Kritični CSS upisan u samu stranu i rezervni tajmer od 2,6 sekundi, pa pad skripte više ne može da ostavi praznu stranu
- Ispravka u SMTP slanju: red u kome stoji samo tačka više ne preseca poruku kupca
- Taj konfigurator je kasnije prešao u vlasnikovu prodavnicu majica, gde umesto upita puni korpu

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 99 | 100 | 100 | 100 |
| Desktop | 98 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `ClothingStore`, `FAQPage`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Jupiter Planet, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Jupiter Planet, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Konfigurator: prednja i zadnja strana, sedam predmeta, boja i brzi šabloni">
<sub>Konfigurator: prednja i zadnja strana, sedam predmeta, boja i brzi šabloni</sub>

<img src="media/inner-2.webp" alt="Šest tipova posla: reklamne majice, maturanti, klubovi, veleprodaja, štampa i vez, KUD-ovi">
<sub>Šest tipova posla: reklamne majice, maturanti, klubovi, veleprodaja, štampa i vez, KUD-ovi</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
