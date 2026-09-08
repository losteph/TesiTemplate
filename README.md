# 🎓 Template Tesi in LaTeX (Versione Semplificata per Locale)

Un template LaTeX pulito, leggero e pronto all'uso per la stesura della tesi di laurea. 

Questo progetto è una **versione rielaborata, semplificata e ottimizzata per la compilazione in locale** del template ufficiale realizzato dal gruppo di ricerca [SisInfLab](http://sisinflab.poliba.it/) del **Politecnico di Bari**. 

## 💡 Perché questo template?
Il template originale (disponibile su [Overleaf](https://www.overleaf.com/latex/templates/politecnico-di-bari-sisinflab-thesis-template/ndsfpdvnqtdf)) è eccellente, ma risulta complesso rispetto ai comandi che uso e conosco io, per questo ho:
- **Semplificato la struttura** rimuovendo file o pacchetti superflui.
- Adattato il codice al mio stile per renderlo più leggibile.
- Predisposto l'ambiente per una facile **compilazione in locale** (senza dipendere da Overleaf).

## 🚀 Requisiti

Per utilizzare questo template in locale sul tuo PC, avrai bisogno di:
1. **Una distribuzione LaTeX:**
   - [TeX Live](https://www.tug.org/texlive/) (Consigliata per Windows e Linux)
   - [MacTeX](https://www.tug.org/mactex/) (Per macOS)
   - [MiKTeX](https://miktex.org/) (Alternativa per Windows)
2. **Un editor di testo per LaTeX:**
   - [TeXstudio](https://www.texstudio.org/) (Consigliato per chi inizia)
   - [Visual Studio Code](https://code.visualstudio.com/) + Estensione "LaTeX Workshop" (Per utenti più esperti)

## 📂 Struttura del Progetto

Ho aggiunto una versione italiana ed una inglese. Nota: è presente anche un file ```.gitignore``` perché da locale, a differenza di quando si usa overleaf,
verranno prodotti una serie di file superflui necessari solo alla compilazione (aggiungendo questo file, tutti i documenti con le estensioni non neccessarie non verranno poi caricate qua).

```text
├── 0_main.tex                  # File principale da compilare
├── 0_frontespizio.tex          # Impaginazione del frontespizio
├── ref.bib                     # File del database bibliografico
└── images/                     # Cartella dove inserire figure e grafici
```
