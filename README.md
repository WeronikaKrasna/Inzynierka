Praca inżynierska - System do rozpoznawania książek po zdjeciu lub skanie okładki

Rozpiska prac:

1.Aplikacja Android studio -> zaczęta (pewnie ulegnie jeszcze zmianie wizualenej)

2. Baza Postgres (potrebna do trzymania danych o użytkownikach) -> API na razie w Node.js, możliwe przeniesienie do ASP.NET. Kwestia gdzie będzie stalo to API rozbija się o AWS i czy dam to do jednej maszymy wirtualnej razem z modelami czy osobno np. w Google Cloud (dlatego że Google Cloud przymuje karty wirtualne jako płatność)

3. Praca w chmurze -> tutaj mam wszytko wyszukane jak to ma działać, chmura dostanie zdjecie z aplikacji mobilnej i po przetworzeniu jej i wyciagnieciu informacji przesle paczke z danymi spowrotem do aplikacji i z poziomu aplikacji przesla sie one do postgresa.
