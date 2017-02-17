1.Tworzymy repozytorium na git (prawy gorny rog i plusik)

2.otwieramy katalog, w ktorym jest nasz projekt i otwieramy konsole "git bash";

3.Wykonujemy nastepujace komendy:

git init

git add . 
git commit -m "first commit"
git remote add origin https://github.com/mwolniak/test.git (oczywiscie tutaj bedziecie mieli swoj adres repozytorium ,ktory wyswietli wam sie na ekranie tuz po dodaniu 
git push -u origin master
(tutaj nas prawdopodobnie zapyta o dane dostepowe do githuba)


4.Przydatne polecenia

potem aby sprawdzac i/lub dodawac nowy kod do repozytorium posługujemy sie nastepujacymi komendami ;
git log (pokazuje historie naszych commitow)
git status (sprawdzamy czy dodalismy pliki do etapu, w ktorym mozemy je zcommitowac)
git add . (przygotowuje wszystkie pliki do wrzucenia w commit)
git commit -m "tresc commita" ( commitujemy plik)

git push (to powinno działać po ostatnim kroku w punkcie 3.)
ALBO
git push -u origin master 
