# AdventureWorksReport_PowerBI_Team  

**IT**  
# **Analisi Business Intelligence AdventureWorks**  
*(Luglio 2017 - Gennaio 2021, Progetto di gruppo)*  

Il progetto ha riguardato l'analisi completa del dataset AdventureWorks, azienda specializzata nella vendita al dettaglio di biciclette e accessori correlati. L'obiettivo è stato quello di sviluppare un report dinamico in Power BI per analizzare performance di vendita, trend temporali e fattori chiave che influenzano i ricavi nel periodo 2017-2021.  
Durante la fase di preparazione dati, sono state combinate le tabelle factinternetsales e factresellersales in un'unica tabella Sales ottimizzata per il refresh schedulato. Sono state unificato le tabelle dimproduct, dimproductsubcategory e dimproductcategory tramite join per creare la tabella Product, importando solo i record necessari dalla tabella dimemployee (SalespersonFlag = True) per ottimizzare le prestazioni.  
Sono state create misure DAX specifiche per calcolare ricavi anno precedente (SAMEPERIODLASTYEAR), numero prodotti distinti, ordini, transazioni e unità vendute. L'analisi ha evidenziato crescita costante fino al 2019, seguita da un calo nel 2020 riconducibile al Covid-19, con le vendite online a sostenere il fatturato. Il comparto Bikes risulta il principale motore delle entrate, mentre Accessories, Clothing e Components mostrano margini percentuali superiori.  

Il risultato è un report interattivo multi-pagina con confronti ricavi/costi nel tempo, analisi performance agenti rispetto alla mediana, funzionalità di drill-up/drill-down per analisi approfondite in un finale grafico ad albero per esplorare le dimensioni che influenzano i ricavi: paese, categoria, sottocategoria, colore e taglia.  

**Tecnologie utilizzate:**  

- 🔄 **Power Query** (ETL, ottimizzazione modello dati)  
- 📊 **PowerBI** (Report interattivo, Dashboard)  
- 📈 **DAX** (Misure personalizzate, Time Intelligence)

## **EN**
# **AdventureWorks Business Intelligence Analysis**  
*(July 2017 - January 2021 | Power BI Team Project)*  

This **team project** involved comprehensive analysis of the AdventureWorks dataset, a company specializing in bicycle and related accessories retail. The objective was to develop a dynamic Power BI report to analyze sales performance, temporal trends, and key factors influencing revenue during the 2017-2021 period.

**Data Preparation Highlights**  
- Combined tables optimization:
  - factinternetsales and factresellersales merged into unified Sales table for scheduled refresh
  - dimproduct, dimproductsubcategory, and dimproductcategory joined to create Product table
  - dimemployee filtered (SalespersonFlag = True) for performance optimization

**Key Features**  
- Custom DAX measures for:  
  - Previous year revenue calculations (SAMEPERIODLASTYEAR)
  - Distinct products, orders, transactions, and units sold
- Multi-page interactive report with:
  - Revenue/cost comparisons over time
  - Sales agent performance vs median analysis
  - Drill-up/drill-down functionality in a tree diagram to explore revenue-influencing dimensions: country, category, subcategory, color, and size

**Insights Uncovered**  
The analysis reveals consistent growth until 2019, followed by a 2020 decline attributable to COVID-19, with online sales sustaining revenue. The Bikes segment drives primary revenue, while Accessories, Clothing, and Components show superior percentage margins.

**Technical Stack:**    
- 🔄 **Power Query** (ETL, data model optimization)
- 📊 **Power BI** (Interactive reports, dashboards)
- 📈 **DAX** (Custom measures, Time Intelligence)
