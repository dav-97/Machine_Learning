# Machine Learning
ONZE VRAGEN : 
1. Wat zal de gemiddelde temperatuur in Maastricht zijn in juni 2020?
2. Wat zal de gemiddelde duur van de neerslag in Maastricht zijn in 2020?
________________________________________________________________________________________________________________________________
1. Je maakt gebruik van minimaal de volgende libraries: numpy , pandas , matplotlib ( seaborn ) en scikit-learn . Optioneel: maak ook gebruik van de libraries, die in de colleges zijn behandeld of benoemd.
2. Alle code werkt zonder run-time errors (warnings zijn acceptabel).
3. Je hebt minimaal 2 machine learning algorithm/technieken toegepast (2 modellen). Je toont hiermee aan inzicht te hebben in de situatie en dat je niet slechts één machine learning techniek gebruikt, die je dan 'toevallig' kent.
4. Je hebt een verantwoording beschreven voor de feature selection . M.a.w. je kan uitleggen de keuzen voor de features en wat je ermee gedaan hebt voor aanvang van de analysis (zoals weglaten, mee laten wegen met bepaalde factor, etc.).
5. Elke (deel)opdracht is in het resultaat aanwezig.
6. Elk teamlid is in staat een relevant antwoord te geven op vragen van panel


https://github.com/flashypepo/mcl_2019-2020/blob/master/assignment%20casus/Toets%20Opdracht%202019-2020.pdf


4:)
    over vraag 1:
        gebruiken we TG, TN, TX, jaar en maand. en in die features zitten geen NaN waarden. Dus hier hoeven we niet op te
        schonen in missende waarden
    over vraag 2:
        gebruiken we DR, jaar en maand. Deze feature heeft wel NaN waarden. Regels 1 tot en met 18628 hebben NaN waarden.
        regel 18628 heeft als waarde voor datum 1-1-1957. Dus als we voor deze dataset alle waarden voor 1957 er uit halen,
        ofwel alle regels van 1 t/m 18627, dan hebben we een schone dataset die we kunnen gebruiken voor onze voorspelling 
        van vraag 2
        
        
Naam casus: Weersvoorspelling Maastricht juni 2020

Korte omschrijving: In deze casus wordt er voorspelt wat de neerslag en de temperatuur zal zijn in Maastricht. Deze voorspelling wordt gedaan voor de maand juni in 2020.

referentie: 

KNMI
http://projects.knmi.nl/klimatologie/daggegevens/selectie.cgi
