# Šipak

Larina dnevna vježba matematike: baseline test kroz prvi tjedan, niz dana, zrna i nagrade, pregled za roditelja.

- Statična stranica (GitHub Pages), bez build koraka.
- Podaci (rezultati, zahtjevi za nagrade, PIN) i fotke su u Supabaseu (EU, Frankfurt), iza prijave. Pristup imaju samo prijavljeni korisnici (Row Level Security).
- Ključ u `index.html` je Supabase *publishable* ključ, namijenjen javnom kodu. Secret ključ nikad ne ide u ovaj repozitorij.
