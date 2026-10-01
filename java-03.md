Java 3 — Kartat dhe faqet
Prova 1: Lista dhe responsive design

Hapat: Hapa faqen kryesore të RideShare dhe kontrollova listën në modalitetin e telefonit me gjerësi 375px. Kontrollova gjithashtu që të shfaqeshin tri karta udhëtimi: Prishtinë, Fushë Kosovë dhe Lipjan.

Rezultati: Në faqen kryesore shfaqen saktësisht tri karta me udhëtime fiktive dhe në gjerësi 375px faqja nuk ka lëvizje horizontale; të gjitha kartat janë të lexueshme.

Prova 2: Detajet e udhëtimit

Hapat: Nga lista hapa kartën e dytë dhe kontrollova adresën /udhetimi/2. Kontrollova gjithashtu detajet e udhëtimit dhe provova adresën /udhetimi/99.

Rezultati: /udhetimi/2 shfaq nisjen, destinacionin, orën, vendtakimin dhe numrin e vendeve të lira. Butoni "Kërko vend" është aktiv sepse udhëtimi 2 ka 1 vend të lirë. /udhetimi/99 shfaq mesazhin "Udhëtimi nuk u gjet" dhe lidhjen për kthim te lista.

Prova 3: Simulimi i kërkesës dhe kthimi mbrapa

Hapat: Nga faqja e detajeve hapa faqen e kërkesës dhe kontrollova udhëtimet me dhe pa vende të lira. Kontrollova gjithashtu lidhjet për kthim në faqet e aplikacionit.

Rezultati: Për udhëtimet me vende të lira shfaqet "Simulim: Në pritje". Për kartën 3, e cila ka zero vende të lira, butoni "Nuk ka vende të lira" është i çaktivizuar. Lidhjet e kthimit funksionojnë në të gjitha faqet.

Përfundim

Rrjedha e aplikacionit funksionon sipas specifikimeve: lista → detaje → kërkesë → kthim mbrapa, pa databazë, pagesë ose rezervim real. Aplikacioni është i orientuar për përdorim në pajisje mobile dhe përputhet me dizajnin e skicës.