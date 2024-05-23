# DelDemo

## Gitin käyttö selkosuomeksi
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

### muita hyödyllisiä
git status #näyttää statuksen  
git log #näyttää commit historian  
git checkout <<commit-id>> #voit palauttaa vanhan commitin aikaisen tilanteen. luo uuden branchin  

### tämä tulee tähän väliin verkosta
