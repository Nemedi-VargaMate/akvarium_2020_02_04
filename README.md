# Ez a weboldal a most legnépszerűbb akváriumi 🐟kezdő díszhalakat halakat mutatja be.
####A weboldalon felsorolt adatok  2025 elején kerültek felvitelre, a változás jogát fenn tartom.
A weboldalat ezen az oldalon tudod megtekinteni : °:•.🐠*.•🪸.•:° https://nemedi-vargamate.github.io/akvarium_2020_02_04/

## A HTML szerkezet
### A főoldalé:
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akváriumi élővilág</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <Table>
        <thead>
            <tr id="eleje">
                <th>Neve</th>
                <th>Képe</th>
                <th>Tulajdonságai</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Platti</td>
                <td><img src="platti.jpg.webp" alt="Platti" title="Platti" ></td>
                <td><a href="index_1.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Színpompás dánió</td>
                <td><img src="choprai dánió.jpg.webp" alt="színpompás dánió" title="Színpompás dánió"></td>
                <td><a href="index_2.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Zöldsávos törperazbóra</td>
                <td><img src="boraras_brigittae.jpg" alt="Zöldsávos törperazbóra" title="Zöldsávos törperazbóra" ></td>
                <td><a href="index_3.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Ancistrus</td>
                <td><img src="ancistrus-600x600.jpg" alt="ancistrus" title="Ancistrus" ></td>
                <td><a href="index_4.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Gömb molly</td>
                <td><img src="gömb molly.jpg.webp" alt="Gömb molly" title="Gömb molly" ></td>
                <td><a href="index_5.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Neonhal</td>
                <td><img src="paracheirodon-innesi.jpg" alt="Neonhal" title="Neonhal" ></td>
                <td><a href="index_6.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Repülő róka</td>
                <td><img src="replülő róka.jpg" alt="Repülő róka" title="Repülő róka"></td>
                <td><a href="index_7.html">Tulajdonságai</a></td>
            </tr>
            
            <tr>
                <td>Ezüst molly</td>
                <td><img src="ezüst molly.jpg" alt="Ezüst molly" title="Ezüst molly"></td>
                <td><a href="index_8.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Arany molly</td>
                <td><img src="arany molly.jpg.webp" alt="Arany molly" title="Arany molly"></td>
                <td><a href="index_9.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Fekete molly</td>
                <td><img src="poecilia_sphenops__.jpg" alt="Fekete molly" title="Fekete molly"></td>
                <td><a href="index_10.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Mexikói Kardfarkú</td>
                <td><img src="xiphophorus_hellerii.jpg" alt="Mexikói Kardfarkú" title="Mexikói Kardfarkú"></td>
                <td><a href="index_11.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Vörösúszójú pontylazac</td>
                <td><img src="Vörösúszójú pontylazac.jpg" alt="Vörösúszójú pontylazac" title="Vörösúszójú pontylazac"></td>
                <td><a href="index_12.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Kolibrihal</td>
                <td><img src="kolibrihal.jpg" alt="Kolibrihal" title="Kolibrihal"></td>
                <td><a href="index_13.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Zebracsiga</td>
                <td><img src="neritina-natalensis-zebra.jpg" alt="Zebracsiga" title="Zebracsiga"></td>
                <td><a href="index_i.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Sisak csiga</td>
                <td><img src="sisak-min.jpg" alt="Sisak csiga" title="Sisak csiga"></td>
                <td><a href="index_ii.html">Tulajdonságai</a></td>
            </tr>
            <tr>
                <td>Hagymacsiga</td>
                <td><img src="hagyma-csiga-Vittina-semiconica-300x300.jpg" alt="Hagymacsiga" title="Hagymacsiga"></td>
                <td><a href="index_iii.html">Tulajdonságai</a></td>
            </tr>       
        </tbody>
    </Table>
    <p><a href="index_forrasok.html">Források megtekintése</a></p>
    <p><a href="#eleje">Vissza az oldal tetejére</a></p>
</body>
</html>
```
### A tulajdonság oldalké:
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plati</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 id="eleje">Platti</h1>
    <h2>Tulajdonságai</h2>
        <p>Békés és könnyen tartható hal, szinte bármilyen fajjal megfér. <br> A hímek általában nem agresszívak egymással, de eltérő tapasztalatok is vannak. <br>
            Kannibalizmusra különösen az először szülő anyák hajlamosak.</p>
     <h3>Szaporodása</h3>
            <p>Közepesen kemény 23-28 fok vízhőmérsékletű vízben szaporodik.<br>
                A nőstények 4-6 után eltérő számú utódot hoznak világra.</p>
    <h3>Tápláláléka</h3>
                <p>Az akváriumokban a lemezes tápokkal táplálkozik.</p> 
    <h3>Igényei</h3>
                <p>Kemény /közepesen kemény vízben érzi jól magát</p>
    <h3>Élettartam</h3>
     <p>~3-5 év</p>
     <h3>Kifejlett példány hossza</h3>
    <p>4-6 cm</p>
    <h3>Ára</h3>
                <p>~700 Ft/db</p>
                <p><a href="https://greenaqua.hu/hu/hal-elevenszulo-platti.html">Irány a bolt-></a></p>
                <img src="platti.jpg.webp" alt="Platti" title="A Képen a platti látható">
    <p><a href="index.html">Vissza a Főoldalra</a> <br> <a href="#eleje">Vissza az oldal tetejére</a></p>
 </body>
</html>
```
## Az oldal kinézetért felős CSS:
```CSS
table {
    border: 5px solid;
    background-color: rgb(0, 0, 0);
    /* háttérszín */
    font-family: 'Courier New', Courier, monospace;
    /* betűstílus */
    font-size: 40px;
    /* betűméret */
    font-weight: bold;
    width: 90%;
  }
img{
    height:auto;
    /*kép méret*/
}
thead{
    background-color:rgb(96, 156, 206) ;
    text-align: center;
}
tbody{
    background-color:rgb(96, 156, 206); 
}
h1{
    font-family:Georgia, 'Times New Roman', Times, serif;
    color: white;
    background-color: darkblue;
    text-align: center;
    font-size: 40px;
    height: auto;
    font-weight: bolder;
    
}
h2{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: black;
    background-color: rgb(96, 156, 206);
    font-size: 30px;
    height: auto;
}
h3{
    font-family: Arial, Helvetica, sans-serif;
    color: black;
    font-size: 25px;
    font-weight: lighter;
    background-color: aquamarine;
}
p{
    font-family: 'Times New Roman', Times, serif;
    font-size: 20px;
    color: black;
}
```