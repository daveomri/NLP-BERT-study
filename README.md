# Nazev semestralni prace

Contradictory, My Dear Watson

# Zadani

If you have two sentences, there are three ways they could be related: 
one could entail the other, one could contradict the other, or they 
could be unrelated. Natural Language Inferencing (NLI) is a popular 
NLP problem that involves determining how pairs of sentences (consisting 
of a premise and a hypothesis) are related.

Your task is to create an NLI model that assigns labels of 0, 1, or 2 
(corresponding to entailment, neutral, and contradiction) to pairs of 
premises and hypotheses. To make things more interesting, the train and 
test set include text in fifteen different languages! 

# Popis dat

Dodana data se deli na dve casti, a to na trenovaci a testovaci. 
Nejedna se o klasicke rozdeleni, nybrz testovaci data jsou vystupem
teto kaggle vyzvy. Nejsou proto ohodnocena a nelze na nich zmerit
uspesnost vytvoreneho modelu.

Pro tyto potrebu se vyuziji data trenovaci, ktere se vhodne rozdeli.

Dataset obsaguje petici sloupcu, id, premisu, hypotezu, kod jazyka, jazyk a label.
Hypoteza a premisa se zde nachazi v nekolika jazycich. Z vetsi casti se jedna
o anglictinu, zbytek je pak dalsich 14 jazyku. V kazde premise se skryva infomace
ktera je porovnana s hypotezou, jsou-li informace ve sporu, pak je label 2, pokud
spolu souhlasi, label je 0 a pokud ani jedno je label 1.

Data jsou v adresari input, a to v takovem formatu, aby po presunu notebooku
do Kagglu ihned spustit.

# Popis zpracovani - bude se lehce modifikovat

Jelikoz je tato problematika nova, chci se v teto praci zamerit na pochopeni a to 
takovym zpusobem, ze zacnu s naivnim pristupem, ktery rozebere veskere dale 
komplexnejsi pristupy.

Tento projekt zpracovavam v jupyter-notebooku a to kvuli tomu, abych jednak vytvoril
potrebne modely, tak i si pripravil prehledny material, ze ktereho budu v budoucnu vychazet.

# todo

