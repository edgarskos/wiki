# wiki

A collection of scripts assisting with several tasks on Wikimedia Foundation projects.

Most of them require the rewrite branch of the [Pywikipediabot](//www.mediawiki.org/wiki/Manual:Pywikipediabot) framework.

### compleanno.py
Written in Italian for the [Italian Wikipedia](//it.wikipedia.org), it searches for users born in the current day (from [this page](//it.wikipedia.org/wiki/Wikipedia:Wikipediani/Per_giorno_di_nascita)) and wishes them a happy birthday with a predefined message.

### fp_notice.py
From an [idea](//it.wikipedia.org/wiki/Discussioni_progetto:Coordinamento/Immagini#Migliorare_la_qualit.C3.A0_delle_immagini_presenti_nelle_voci_usando_quelle_gi.C3.A0_selezionate_da_Commons) of [Marcok](//it.wikipedia.org/wiki/Utente:Marcok), it checks for Wikimedia Commons [Featured Pictures](//commons.wikimedia.org/wiki/COM:FP) that are used in English articles but not in their Italian versions, and logs them in a user subpage.
