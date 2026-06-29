# SxS BuildLab - Learning Journal

Autor: Miloš Brejcha

---

# Lekce 1 - Git Bash základy
```bash

*.md Markdown is a lightweight markup language for creating formatted text using a plain-text editor. 

</>
Zobrazí aktuální adresář.
pwd
(Print Working Directory)

</>
cd /c/APCODE/sxs-buildlab
priklad zmeny korenoveho adresare

/c/Users/smajl/sxs-buildlab

</>
Výpis souborů
ls / ll

</>
Změna adresáře
cd docs

</>
O úroveŘ výše:
cd ..

</>
Do domovského adresáře:
cd ~

</>
Vytvoření adresáře
mkdir 

</>
Vytvoření více adresářů
mkdir docs src tests assets

</>
Vytvoření souboru
touch 

</>
Smazání souboru
rm

</>
Smazání prázdného adresáře
rmdir

</>
Stav repozitáře
git status

Ukáže změny proti poslednímu commitu.

</> 
Přidání souborů
git add README.md

</> 
Všechny změny:
git add .

</>
Commit
git commit -m "Create project structure"
commit = uloží změny do historie
-m = message

</>
Odeslání na GitHub
git push

</>
Stažení změn
git pull
nahrani zmen z GITu na lokal machine

Proč používám git add . ?
Protože Git nejdříve změny připraví (Staging Area).
Teprve potom vytvořím commit.

Working Directory
        │
        ▼
git add .
        │
        ▼
Staging Area
        │
git commit
        ▼
Repository
        │
git push
        ▼
GitHub      

