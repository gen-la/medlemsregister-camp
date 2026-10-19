# medlemsregister-camp

## Ett problem vi löste
I filen src/Main.java, rad 3, krockade samma println med varandra. Det var två println på samma rad men med olika texter att printa. Felet uppstod pga. två grenar ändrade samma rad
samtidigt. Detta löstes genom att först läsa mellan staketen och kolla vad varje ändring var för något (och kolla vilken rad det gäller), sedan valde jag vilken rad som jag ville behålla och raderade den andra (inklusive markörerna). Kontrollerade att allt stod rätt till
och körde sedan git add, commit och push, laddade om min PR på GitHub och synkade stambanan lokalt.