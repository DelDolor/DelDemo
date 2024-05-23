# DelDemo

## Gitin käyttö selkosuomeksi
### Ympäristön konfigurointi
git config --global user.name "Etunimi Sukunimi"  
git config --global user.email "etu.suku@mail.com"     

### Uuden readme filen luonti konsolista ja upload main branchiin
echo "# DelDemo" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  

### Liitetään paikallinen git GitHubin online repoon ja pusketaan commitoidut
git remote add origin git@github.com:DelDolor/DelDemo.git  
git push -u origin main  

### Verkossa olevan Git repon muutosten lataus paikalliseen repoon
git pull  

### muokatun paikallisen tiedoston vieminen verkossa olevaan Git repoon
git add README.md  
git commit README.md -m "jee"  
git push  

### Päivitä paikallinen reposi ajantasalle
git pull

### Luo manuaalisesti uusi branch ja työnnä kaikki data sinne
git branch branhcname  
git push origin branchname  

### Hae klooni toisesta reposta, poista sen .git tiedot ja lisää osaksi omaa repoasi
git clone https://github.com/kangasta/week-53  
rm -rf week-53/.git  
git add week-53/  
commit -m "add week53 exmaple"  

### muita hyödyllisiä
git status #näyttää statuksen  
git log #näyttää commit historian  
git checkout <<commit-id>> #voit palauttaa vanhan commitin aikaisen tilanteen. luo uuden branchin  
