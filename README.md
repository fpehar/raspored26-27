# raspored26-27

Raspored nastave na Odjelu za informacijske znanosti i tehnologije, akad. god. 2026./2027., u obliku kalendara na koje se studenti mogu pretplatiti.

**Stranica za studente:** https://fpehar.github.io/raspored26-27/

## Datoteke

Svaka godina studija ima jednu .ics datoteku:

| Datoteka | Studij |
|---|---|
| `pds-1g.ics`, `pds-2g.ics`, `pds-3g.ics` | Preddiplomski, 1.–3. godina |
| `ds-red-1g.ics`, `ds-red-2g.ics` | Diplomski redovni, 1.–2. godina |
| `ds-izv-1g.ics`, `ds-izv-2g.ics` | Diplomski izvanredni, 1.–2. godina |
| `dok-1g.ics`, `dok-2g.ics` | Doktorski (kad bude objavljen) |

Datoteke se generiraju iz izvoza rasporeda i ne uređuju se ručno.

## Ažuriranje (za administratora)

1. U sustavu za raspored pokrenuti izvještaj (Run Report) za cijeli semestar i sve godine te ga spremiti kao `report.ics`.
2. Pokrenuti skriptu `split_mrbs_ics.py` (čuva se izvan ovog repozitorija) i pregledati ispis. Ako navodi upozorenja, riješiti ih prije objave.
3. Nove .ics datoteke kopirati u ovaj repozitorij, istim imenima i preko starih, pa `git add`, `git commit` i `git push`.
4. Promjena je na stranici za minutu-dvije, a u kalendarima studenata unutar nekoliko sati.

## Što se ne smije mijenjati

Pretplate studenata vezane su uz adresu datoteka. Zato se ne preimenuju repozitorij ni korisnički račun i ne mijenjaju imena .ics datoteka. Ako se adresa ipak promijeni, pretplate prestaju raditi, a studenti to neće odmah primijetiti.

Datoteka `.nojekyll` mora ostati u korijenu repozitorija.
