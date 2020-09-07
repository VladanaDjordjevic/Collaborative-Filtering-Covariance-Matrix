# Sistem preporuka zasnovan na uzajamnom filtriranju koristeći matricu kovarijansi

Sistem preporuka je sistem koji preporučuje proizvode korisniku za koje smatra da su mu od značaja. Ovi sistemi su široko rasprostranjeni i korišćeni u različitim sferama života. Postoji više različitih vrsta takvih sistema, ovde će biti korišćen sistem zasnovan na **uzajamnom filtriranju**. Osnovna ideja uzajamnog filtriranja je da ako su korisnici imali slična interesovanja u prošlosti imaće slična interesovanja i u budućnosti, tj. da prethodno ponašanje korisnika ima ogroman uticaj na njegovo buduće ponašanje. 

U ovom projektu je implementiran algoritam CFCM (Collaborative Filtering Covariance Matrix) kojim se poboljšava se kvalitet preporuka.

Jupyter radna sveska **MovieLens 100K - Primena algoritma** predstavlja implementiran algoritam, metrike i poređenje sa već dostupnim algoritmima koje pruža biblioteka Surprise. Sve to je primenjeno na već dostupnoj podeli na trening i test skup koju pruža MovieLens 100K skup podataka. S obzirom na to da skup nudi 5 podela na trening i test skup, a u radnoj svesci smo upotrebili samo jednu podelu, sastavljena je još jedna radna sveska **MovieLens 100K - Primena algoritma na skupu 2** gde je ceo postupak isti, samo su trening i test skup drugačiji, pa je svrha te sveske validacija. 

Tijana Tošev 1101/2019  
Vladana Đorđević 1092/2019  
