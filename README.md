\# Projekt APBD - Git



Merge nie był fast-forward, ponieważ na gałęzi main pojawiły się nowe, niezależne commity w trakcie pracy nad gałęzią feature-max. Git musiał połączyć rozwidloną historię tworząc nowy merge commit.



Przygotowanie do rebase'a



Merge zachowuje oryginalną historię gałęzi i tworzy commit łączący, natomiast rebase przepisuje historię, przenosząc commity na koniec gałęzi głównej, co daje liniową historię bez commitów łączących.



Konflikt w pliku FirstClass.cs powstał, ponieważ ta sama metoda została zmodyfikowana w tym samym miejscu na dwóch różnych gałęziach (main i feature-conflict). Rozwiązałem go ręcznie, otwierając plik w edytorze tekstowym. Usunąłem znaczniki wygenerowane przez Gita (<<<<<<<, =======, >>>>>>>) i zapisałem.

