# Modello_Statistico_Peso_Neonato
Third Project of the Master in Data Science by Professional.AI

**Link a rpubs: http://rpubs.com/GiusSinatra/1260521**
In questo progetto a tema è stata messa la statistica inferenziale, dovendo creare un modello statistico per la previsione del peso neonatale, usando dati clinici estratti da tre ospedali. Fasi del progetto:
1. Analisi preliminare: individuazione dati anomali, studio caratteristiche delle distribuzioni delle variabili, individuazione outliers, analisi parti cesarei tra ospedali con test del $$X^2$$. Utilizzando i dati dell'università di Ronchester verifica se il nostro campione è rappresentativo della popolazione.
2. Creazione del modello di regressione: test di shapiro-wilk sulla variabile target, studio della correlazione tra le features e il peso, t-test per verificare se le variabile categoriche influenzano il target. Per la costruzione del modello ho seguito un approccio backwards con analisi dei p-value dei singoli regressori e del $$R^2_{adj}$$ per i diversi modelli.
3. Selezione del modello ottimale: per la scelta del modello ottimale ho usato i seguenti test: AIC, BIC e ANOVA
4. Analisi della qualistà del modello: verifica dell'assenza di collinearità (VIF), calcolo delle metriche $$R^2_{adj}$$ e RMSE, analisi dei residui (qqplot, shapiro-wilk test, breusch-pagan test e durbin-watson test), individuazione outliers tramite distanza di Cook.
5. Previsioni e risultati: realizzazione di grafici per confrontare le previsioni del nostro modello con i dati reali.

Linguaggio di programmazione: R
