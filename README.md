# Pašizveidots projekts
## projekta uzdevums

Projekta uzdevums ir automatizēt noteikta excel faila rediģēšanu. Šis darbs palīzdēs atbrīvot personu no stundām ilga darba meklējot un dzēšot ārā dublikātus, kas ir nejauši izveidoti noteiktas kompānijas dalībnieku arakstā
Sarakstā ir dublikāti izveidojušies divās vietās.
* ir pierakstīta persona divas vai vairākas reizes
* ir perakstīts dalībnieka vārds nepareizi un atkārtoti pierakstīts e-pasts

Darba rezūltējošais mērķis ir izveidot programu, kas automatiski izveidos jaunu vailu kurā būs iegšā pieprasītais ligs(sheet) un izdzēsti duplikāti.

## Izmantotās bibleotēkas 
* Pandas

Pandas bibleotēka tika izmantota, lai atvētu failu, iegūtu informāciju no faila un izveidotu jaunu failu.
Sākotnēji darbs tika mēģināts realizēt ar openpyxl. Šis bija tamdēļ, ka šī bibleotēka bija dauzdz izmantota kursa laikā un sākotnēji likās ērtāka šim darbam, tomēr pēc dažādu apgrūtinājumu sastapšanas tika izvēlēta pandas bibleotēka.
Šī pibleotēka piedāvāja efektīvu veidu kā igūt visus tabulas datus kā arī efektīvi saglabāt jaunā failā.

## Programaturas izmantošanas metodes

Šajā programā patā tiek peilietota viena metode. Tiek izveidots sarakst pie kura katrā iderācijā pieievieno jaunus datus, tomēr ja tiek konstatēts, ka sarakstā jau eksistē šī informācija saraksts neteik papildināts.
Pēc šī saraksta izveidošanas saraksta datus izmanto, lai izveidotu jaunu excel tabulu. 
Dažas nelielas lietas ko izmanto darbā ir
* cilvēka ievade terminālā.
* jauna faila nosaukšana palstoties uz terminālā ievadīto
* Faila atveršana balstoties uz personas ievadni terminālā
