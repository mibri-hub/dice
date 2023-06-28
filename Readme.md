# GIT verziókezelés

- Helyi REPO inicializálása:
    > git init
- A helyi REPO állapotának ellenőrzése:
    > git status
-  Előkészítjük a commitolásra, felteszük a színpadra (Stage), indexelés történik:
    > git add . (a 'pont' minden állományra vonatozik)

    > git status
- Commit (az új verzió létre hozása)
    > git commit -m "firstCommit" (Helyi REPO inicializálása)

    > git status
- Távoli REPO létrehozása(a Github oldalán)
- Összekapcsoljuk a távoli REPO-t a helyivel (csak a legelső alkalommal):
    > git remote add origin https://token@github.com/mibri-hub/TestRepo03.git
- Kiválasztjuk az ágat a távoli REPO-ban (branch):
    >git push -u origin master (csak a legelső alkalommal kell)

    >git push (a további alkalmakkor)
- Token használa ( ezzel azonosítjuk magunkata github-ban)

## Publikálás
- A publikálandü file neve index.html
- Settings > Pages > Branch non-ból kiválastjuk a master-t > Save
- Action-ben láthatjuk a publikálási folyaamatot
- Minden commit után automatikusan újra publikálodik az oldal

