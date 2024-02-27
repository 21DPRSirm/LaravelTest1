# Teorija
**This is bold text**
1. 
Question: Kas ir API ?
Answer: API nozīmē "Application Programming Interface"
tas ir iepriekš izveidotu(definētu) klašu, procedūru, funkciju struktūru un konstanšu kopums.

2.
Question: Kā deklarēt mainīgo PHP valodā?
Answer: PHP valodā var deklarēt mainīgo ar "$" un tad mainīgā nosaukums,
piemērs:
$x = 900;
$y = "WindowsOS"
$variable = "variableNo1"
$number1 = "Microsoft"

3. 
Question: Kādu arhitektūru izmanto Laravel.
Answer: Laravel izmanto "Model-View-Controller"(saīsināti "MVC")

4.
Question: Kas ir ORM, un kāpēc to izmanto tīra SQL vietā.
Answer: ORM jeb "Object-Relational-Mapping" ir programmēšanas tehnoloģija, kurā dati no datubāzēm sasaista objektos pēc
objektorientētās programmēšanas teorijas, rezultātā iegūstot virtuālo objektu datubāzi.



5.
Answer: Eloquent ORM pieprasījums modelim "User", kur nepieciešams iegūt visus lietotājus kuriem vērtējums(reitings) ir lielāks par "4" ir:
$lietotaji = lietotajs::where('vertejums', '>', 4)-get();
$lietotaji = User::where('rating', '>', 4)-get();
