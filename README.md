# klasa tacka
Klasa tacka treba da sadrzi dva atributa(jedna za svaku koordinatu u 2d)
Klasa tacka treba da sadrzi boolean atribut da se vidi da li je tacka selektovana
mora da ima prazan konstruktor
treba da ima konstruktor kojima se inicijalizuju svi atributi klase
klasa da ima metodu kojom se racuna udaljenost tacke od neke druge tacke
treba da sadrzi metodu koja proverava da li tacka sadrzi neku drugu tacku (distanca je manja ili jednaka 2)
treba da sadrzi metodu tostring koja vraca(printa) koordinate tacke u zagradi razdvojen zarezom
treba da sadrzi metodu equals koja prima univerzalni tip object i vraca boolean u zavisnosti da li je poslati objekat jednak sa datim objektom
equals metoda treba da vrati tacno ako poslati objekat ima iste koordinate kao i objekat koji je poziva?
treba da ima gettere i settere za x i y
treba da sadrzi nulti zahtev (klasa tacka treba da bude podklasa shape(nasledjuje klasu shape))
treba da override-uje metodu draw i da u toj metodi setuje boju na crnu
treba da nacrta liniju funkcijom draw line sa argumentima (x-2) i (y) i (x+2) i (y)
u okviru iste metode nacrta liniju sa argumentima 
da nacrta vertikalnu liniju sa argumentima: x, y-2, x, y+2
ako je tacka selektovana, treba da promeni boju u plavu i da se oko nje nacrta rectamgle koristeci metodu drawrect sa sledecim arguentima: x-2, y-2, 4, 4
klasa tacka treba da sadrzi metodu za pomeranje tako sto ce tacka da se pomeri na nove date koordinate (moveto)
treba da overriduje moveto metodu
treba da overriduje moveby
mora da overriduje compareto