{\rtf1\ansi\ansicpg1252\cocoartf1504\cocoasubrtf840
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 #include <iostream>\
#include <vector>\
#include <string>\
#include <iomanip>\
\
using namespace std;\
\
struct Categoria \{\
    int id;\
    string nome;\
\};\
\
struct Spesa \{\
    string data;     // YYYY-MM-DD\
    double importo;\
    int idCategoria;\
\};\
\
struct Budget \{\
    string mese;     // YYYY-MM\
    double importo;\
    int idCategoria;\
\};\
\
int main() \{\
    vector<Categoria> categorie;\
    vector<Spesa> spese;\
    vector<Budget> budgets;\
\
    int nextIdCategoria = 1;\
    int scelta;\
\
    cout << "Benvenuto nel Sistema di Gestione delle Spese Personali\\n";\
\
    while (true) \{\
        cout << "\\n-------------------------\\n";\
        cout << "SISTEMA SPESE PERSONALI\\n";\
        cout << "-------------------------\\n";\
        cout << "1. Gestione Categorie\\n";\
        cout << "2. Inserisci Spesa\\n";\
        cout << "3. Definisci Budget Mensile\\n";\
        cout << "4. Visualizza Report\\n";\
        cout << "5. Esci\\n";\
        cout << "-------------------------\\n";\
        cout << "Inserisci la tua scelta: ";\
        cin >> scelta;\
\
        switch (scelta) \{\
\
            case 1: \{\
                string nomeCategoria;\
                cout << "Nome categoria: ";\
                cin >> nomeCategoria;\
\
                if (nomeCategoria == "") \{\
                    cout << "Errore: nome non valido.\\n";\
                    break;\
                \}\
\
                Categoria c;\
                c.id = nextIdCategoria;\
                c.nome = nomeCategoria;\
                categorie.push_back(c);\
                nextIdCategoria++;\
\
                cout << "Categoria inserita correttamente. ID = " << c.id << "\\n";\
                break;\
            \}\
\
            case 2: \{\
                if (categorie.size() == 0) \{\
                    cout << "Errore: prima inserisci almeno una categoria.\\n";\
                    break;\
                \}\
\
                Spesa s;\
\
                cout << "Data (YYYY-MM-DD): ";\
                cin >> s.data;\
\
                cout << "Importo: ";\
                cin >> s.importo;\
\
                if (s.importo <= 0) \{\
                    cout << "Errore: l'importo deve essere maggiore di zero.\\n";\
                    break;\
                \}\
\
                cout << "Categorie disponibili:\\n";\
                for (int i = 0; i < (int)categorie.size(); i++) \{\
                    cout << categorie[i].id << " - " << categorie[i].nome << "\\n";\
                \}\
\
                cout << "ID Categoria: ";\
                cin >> s.idCategoria;\
\
                bool esiste = false;\
                for (int i = 0; i < (int)categorie.size(); i++) \{\
                    if (categorie[i].id == s.idCategoria) \{\
                        esiste = true;\
                    \}\
                \}\
\
                if (!esiste) \{\
                    cout << "Errore: la categoria non esiste.\\n";\
                    break;\
                \}\
\
                spese.push_back(s);\
                cout << "Spesa inserita correttamente.\\n";\
                break;\
            \}\
\
            case 3: \{\
                if (categorie.size() == 0) \{\
                    cout << "Errore: prima inserisci almeno una categoria.\\n";\
                    break;\
                \}\
\
                Budget b;\
\
                cout << "Mese (YYYY-MM): ";\
                cin >> b.mese;\
\
                cout << "Categorie disponibili:\\n";\
                for (int i = 0; i < (int)categorie.size(); i++) \{\
                    cout << categorie[i].id << " - " << categorie[i].nome << "\\n";\
                \}\
\
                cout << "ID Categoria: ";\
                cin >> b.idCategoria;\
\
                bool esiste = false;\
                for (int i = 0; i < (int)categorie.size(); i++) \{\
                    if (categorie[i].id == b.idCategoria) \{\
                        esiste = true;\
                    \}\
                \}\
\
                if (!esiste) \{\
                    cout << "Errore: la categoria non esiste.\\n";\
                    break;\
                \}\
\
                cout << "Importo budget: ";\
                cin >> b.importo;\
\
                if (b.importo <= 0) \{\
                    cout << "Errore: il budget deve essere maggiore di zero.\\n";\
                    break;\
                \}\
\
                bool aggiornato = false;\
                for (int i = 0; i < (int)budgets.size(); i++) \{\
                    if (budgets[i].mese == b.mese && budgets[i].idCategoria == b.idCategoria) \{\
                        budgets[i].importo = b.importo;\
                        aggiornato = true;\
                    \}\
                \}\
\
                if (!aggiornato) \{\
                    budgets.push_back(b);\
                \}\
\
                cout << "Budget mensile salvato correttamente.\\n";\
                break;\
            \}\
\
            case 4: \{\
                int sceltaReport;\
\
                while (true) \{\
                    cout << "\\n--- MENU REPORT ---\\n";\
                    cout << "1. Totale spese per categoria\\n";\
                    cout << "2. Spese mensili vs budget\\n";\
                    cout << "3. Elenco completo delle spese ordinate per data\\n";\
                    cout << "4. Ritorna al menu principale\\n";\
                    cout << "Scelta: ";\
                    cin >> sceltaReport;\
\
                    if (sceltaReport == 1) \{\
                        cout << "\\nCategoria\\tTotale Speso\\n";\
                        cout << "----------------------------\\n";\
\
                        for (int i = 0; i < (int)categorie.size(); i++) \{\
                            double totale = 0;\
\
                            for (int j = 0; j < (int)spese.size(); j++) \{\
                                if (spese[j].idCategoria == categorie[i].id) \{\
                                    totale += spese[j].importo;\
                                \}\
                            \}\
\
                            cout << categorie[i].nome << "\\t\\t" << fixed << setprecision(2) << totale << "\\n";\
                        \}\
                    \}\
                    else if (sceltaReport == 2) \{\
                        string mese;\
                        cout << "Mese (YYYY-MM): ";\
                        cin >> mese;\
\
                        for (int i = 0; i < (int)categorie.size(); i++) \{\
                            int idCat = categorie[i].id;\
                            double speso = 0;\
                            double budget = -1;\
\
                            for (int j = 0; j < (int)spese.size(); j++) \{\
                                if (spese[j].idCategoria == idCat) \{\
                                    if (spese[j].data.substr(0, 7) == mese) \{\
                                        speso += spese[j].importo;\
                                    \}\
                                \}\
                            \}\
\
                            for (int k = 0; k < (int)budgets.size(); k++) \{\
                                if (budgets[k].mese == mese && budgets[k].idCategoria == idCat) \{\
                                    budget = budgets[k].importo;\
                                \}\
                            \}\
\
                            if (budget != -1) \{\
                                cout << "\\nMese: " << mese << "\\n";\
                                cout << "Categoria: " << categorie[i].nome << "\\n";\
                                cout << "Budget: " << fixed << setprecision(2) << budget << "\\n";\
                                cout << "Speso: " << fixed << setprecision(2) << speso << "\\n";\
\
                                if (speso > budget) \{\
                                    cout << "Stato: SUPERAMENTO BUDGET\\n";\
                                \} else \{\
                                    cout << "Stato: OK\\n";\
                                \}\
                            \}\
                        \}\
                    \}\
                    else if (sceltaReport == 3) \{\
                        cout << "\\nData\\t\\tCategoria\\tImporto\\n";\
                        cout << "------------------------------------------\\n";\
\
                        for (int i = 0; i < (int)spese.size(); i++) \{\
                            string nomeCat = "";\
\
                            for (int j = 0; j < (int)categorie.size(); j++) \{\
                                if (categorie[j].id == spese[i].idCategoria) \{\
                                    nomeCat = categorie[j].nome;\
                                \}\
                            \}\
\
                            cout << spese[i].data << "\\t" << nomeCat << "\\t\\t"\
                                 << fixed << setprecision(2) << spese[i].importo << "\\n";\
                        \}\
                    \}\
                    else if (sceltaReport == 4) \{\
                        break;\
                    \}\
                    else \{\
                        cout << "Scelta non valida. Riprovare.\\n";\
                    \}\
                \}\
\
                break;\
            \}\
\
            case 5:\
                cout << "Uscita...\\n";\
                return 0;\
\
            default:\
                cout << "Scelta non valida. Riprovare.\\n";\
        \}\
    \}\
\}}