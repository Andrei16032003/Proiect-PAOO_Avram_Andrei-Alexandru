Gestiunea Elevilor Bursieri la Liceu (.NET Edition)
Sistem desktop performant dezvoltat în C# pentru monitorizarea și administrarea centralizată a burselor școlare. Aplicația facilitează gestionarea criteriilor de eligibilitate și distribuția sprijinului financiar, oferind analize vizuale complexe și rapoarte automatizate.
 Tehnologii și Librării
•	Limbaj: C# (.NET Framework).
•	Interfață Grafică: Windows Forms (WinForms) pentru un UI intuitiv.
•	Bază de Date: MySQL cu integrare prin ADO.NET (DbHelper, MySqlCommand).
•	Grafice & Analytics: LiveCharts (PieChart, CartesianChart, Column, Line, Polar).
•	Export Rapoarte: iTextSharp pentru generarea documentelor PDF.
•	Design: FontAwesome.Sharp pentru iconițe vectoriale moderne.
 Funcționalități Principale
1. Niveluri de Acces (Roluri)
•	Mod Vizitator: Permite vizualizarea listei de bursieri cu date anonimizate (fără nume/prenume) pentru protecția confidențialității.
•	Mod Elev: Acces securizat prin ID unic pentru vizualizarea detaliilor personale, mediei și statusului bursei proprii.
•	Mod Administrator: Control total asupra sistemului (autentificare cu user/pass), incluzând operațiuni CRUD și generare de statistici.
2. Module Administrative
•	Gestionare Elevi: Adăugarea, editarea și ștergerea înregistrărilor din baza de date MySQL.
•	Statistici Dinamice: Vizualizarea repartizării pe clase și tipuri de burse (Merit, Socială, Performanță) prin grafice interactive.
•	Sistem de Raportare: Exportul listelor filtrate direct în format PDF.
•	Istoric Acțiuni: Jurnalizarea completă a tuturor evenimentelor (cine, ce, când și detaliile operației) pentru trasabilitate.
   Securitate și Validare
•	Validare Input: Verificarea tipurilor de date (e.g., int.TryParse pentru coduri numerice) și a câmpurilor obligatorii.
•	Prevenire SQL Injection: Utilizarea parametrizării interogărilor SQL în ADO.NET.
•	Integritate: Mecanisme de tip try-catch pentru gestionarea excepțiilor și prevenirea crash-urilor.

