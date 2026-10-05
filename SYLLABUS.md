# SYLLABUS: AI Engineering, fra machine learning til specialiserede modeller

Studerende: Valdemar Bang Nielsen
Start: mandag 5. oktober 2026. Slut: fredag 5. februar 2027. Juleferie 21. december til 1. januar.
Omfang: 2 timer hver hverdag. Afleveringer i `modul-XX/dag-YY/`. Notebooks skal være kørt.

## Ugens rytme
Mandag: video og teori, note i `noter/`. Tirsdag til torsdag: kodeopgaver. Fredag: ugeopgave eller quiz plus refleksion.

## Vurdering (7 trinsskalaen)
Korrekthed 40 %, forståelse 30 %, kodekvalitet 20 %, refleksion 10 %.
Feedback i tre dele: hvad virker, hvad skal forbedres, én konkret ting til næste gang.

## Lærerens regler
1. Giv aldrig den færdige løsning.
2. Trappet hjælp: først et spørgsmål, så et konkret hint, så et pseudokode skelet med huller.
3. Kommer den studerende bagud, rykkes planen. Dage springes ikke over.

---

## Modul 1: Python og værktøjer

### Uge 1 (5. til 9. okt): Python og git
Videoer: https://www.youtube.com/watch?v=RGOj5yH7evk (Git, freeCodeCamp), https://www.youtube.com/watch?v=_uQrJ0TkZlc (Python, Mosh, opslag)
- Dag 1: Installér Python, VS Code, git. Klon repo, opret struktur og README.
- Dag 2: `mean`, `median`, `std` i ren Python med `assert` tests.
- Dag 3: Læs CSV med `csv` modulet, filtrér med list comprehensions.
- Dag 4: Klassen `Dataset` der indlæser CSV og giver kolonner og statistik.
- Dag 5: Ugeopgave: ordfrekvens script, top 20 ord, med tests.

### Uge 2 (12. til 16. okt): numpy, pandas, Colab
Videoer: https://www.youtube.com/watch?v=GB9ByFAIAH4 (NumPy, Keith Galli), https://www.youtube.com/watch?v=ZyhVh-qRZPA (Pandas, Corey Schafer)
- Dag 6: Statistikfunktioner i numpy, mål hastighed på 1 mio. tal.
- Dag 7: 10 øvelser i vektorisering og broadcasting.
- Dag 8: Titanic i pandas i Colab: kolonner, manglende værdier, datatyper.
- Dag 9: `groupby` og 4 matplotlib grafer om overlevelse.
- Dag 10: MODULAFLEVERING: analyse notebook, 5 spørgsmål, grafer, konklusion.

## Modul 2: Matematik til ML

### Uge 3 (19. til 23. okt): Lineær algebra
Videoer: https://www.youtube.com/watch?v=fNk_zzaMoSs, https://www.youtube.com/watch?v=kYB8IZa5AuE, https://www.youtube.com/watch?v=XkY2DOUCWMU (3Blue1Brown)
- Dag 11: Note: vektor, matrix, lineær transformation med egne ord.
- Dag 12: `dot`, `norm`, `add` i ren Python, tjek mod numpy.
- Dag 13: Matrixmultiplikation fra bunden, plot rotation af kvadrat.
- Dag 14: Lineær regression med normalligningen.
- Dag 15: Quiz og refleksion.

### Uge 4 (26. til 30. okt): Afledte og sandsynlighed
Videoer: https://www.youtube.com/watch?v=WUvTyaaNkzM, https://www.youtube.com/watch?v=sDv4f4s2SB8, https://www.youtube.com/watch?v=rzFX5NWojp0, https://www.youtube.com/watch?v=HZGCoVF3YvM
- Dag 16: Numerisk afledt vs analytisk for 3 funktioner.
- Dag 17: Gradient descent i 1D og 2D, plot stien.
- Dag 18: Simulér terninger og normalfordeling, histogrammer.
- Dag 19: Bayes: medicinsk test eller spamfilter, beregnet og simuleret.
- Dag 20: MODULAFLEVERING: lineær regression med gradient descent fra bunden, tabskurve, sammenlign med normalligning.

## Modul 3: Klassisk machine learning

### Uge 5 (2. til 6. nov): Regression og klassifikation
Videoer: https://www.youtube.com/watch?v=nk2CQITm_eo, https://www.youtube.com/watch?v=yIYKR4sgzI8, https://www.youtube.com/watch?v=EuBBz3bI-aA (StatQuest)
- Dag 21: Note: supervised/unsupervised, train/test, overfitting, eksempel fra bank.
- Dag 22: `LinearRegression` på California Housing, MAE og RMSE.
- Dag 23: Logistisk regression fra bunden.
- Dag 24: Sammenlign med scikit learns `LogisticRegression`.
- Dag 25: Overfitting: polynomier grad 1 til 15, plot train/test fejl.

### Uge 6 (9. til 13. nov): Evaluering
Videoer: https://www.youtube.com/watch?v=Kdsp6soqA7o, https://www.youtube.com/watch?v=4jRBRDbJemM, https://www.youtube.com/watch?v=fSytzGwwBVw, https://www.youtube.com/watch?v=_L39rN6gz7Y
- Dag 26: Confusion matrix, precision, recall, F1 i hånden og kode.
- Dag 27: ROC kurve fra bunden.
- Dag 28: Krydsvalidering og `Pipeline` med skalering.
- Dag 29: Logistisk regression vs kNN vs beslutningstræ.
- Dag 30: MODULAFLEVERING: Breast Cancer klassifikation med fuld evaluering og begrundet metrik.

## Modul 4: ML på tabeldata i praksis

### Uge 7 (16. til 20. nov): Træmodeller og datarensning
Videoer: https://www.youtube.com/watch?v=J4Wdy0Wc_xQ, https://www.youtube.com/watch?v=3CC4N4z3GJc, https://www.youtube.com/watch?v=OtD8wVaFm6E
- Dag 31: German Credit: manglende værdier, kategoriske variable.
- Dag 32: Feature engineering, 5 nye variable med begrundelse.
- Dag 33: Random forest og feature importance.
- Dag 34: XGBoost/LightGBM med tuning via krydsvalidering.
- Dag 35: Ubalancerede klasser: class weights, oversampling, tærskel.

### Uge 8 (23. til 27. nov): Modulprojekt kreditrisiko
- Dag 36: Problemformulering og omkostning ved FP og FN.
- Dag 37: Baseline og evalueringsopstilling.
- Dag 38: Bedste model, tunet, sammenlignet med baseline.
- Dag 39: SHAP og vurdering af skævhed.
- Dag 40: MODULAFLEVERING: README, model card, kørbar notebook.

## Modul 5: Neurale netværk og PyTorch

### Uge 9 (30. nov til 4. dec): Fra neuron til backpropagation
Videoer: https://www.youtube.com/watch?v=aircAruvnKk, https://www.youtube.com/watch?v=IHZwWFHWa-w, https://www.youtube.com/watch?v=Ilg3gGewQ5U, https://www.youtube.com/watch?v=VMj-3S1tku0 (micrograd)
- Dag 41: Note med tegning af netværk med 2 lag.
- Dag 42: Klassen `Value` med plus og gange.
- Dag 43: `backward()`, tjek gradienter numerisk.
- Dag 44: `Neuron`, `Layer`, `MLP`.
- Dag 45: Træn MLP på `make_moons`, plot beslutningsgrænse.

### Uge 10 (7. til 11. dec): PyTorch
Video: https://www.youtube.com/watch?v=V_xro1bcAuA (kun tensors, workflow, klassifikation)
- Dag 46: Tensors og autograd, genskab micrograd eksempel.
- Dag 47: Træningsløkke på FashionMNIST med GPU.
- Dag 48: Eksperimenter med læringsrate, batch, lag.
- Dag 49: Lille CNN og dropout.
- Dag 50: MODULAFLEVERING: MLP vs CNN, gemt model, rapport.

## Modul 6: Transformere og sprogmodeller

### Uge 11 (14. til 18. dec): Fra bigram til attention
Videoer: https://www.youtube.com/watch?v=PaCmpygFfXo, https://www.youtube.com/watch?v=wjZofJX0v4M, https://www.youtube.com/watch?v=eMlx5fFNoYc, valgfri https://www.youtube.com/watch?v=zduSFxRajkE
- Dag 51: Bigram model ved optælling på danske fornavne.
- Dag 52: Samme som neuralt netværk i PyTorch.
- Dag 53: Embeddings og ét attention hoved i numpy.
- Dag 54: Sammenlign tokenizers på dansk og engelsk.
- Dag 55: Quiz og refleksion.

JULEFERIE 21. dec til 1. jan: ingen opgaver.

### Uge 12 (4. til 8. jan): Byg en GPT
Videoer: https://www.youtube.com/watch?v=kCc8FmEb1nY, https://www.youtube.com/watch?v=zjkBMFhNj_g
- Dag 56: Let's build GPT del 1 med H.C. Andersens eventyr.
- Dag 57: Self attention og multi head attention.
- Dag 58: Træn i Colab, generér tekst, dokumentér.
- Dag 59: Hugging Face `pipeline` til tekstklassifikation.
- Dag 60: MODULAFLEVERING: lille GPT, eksperimenter, forklaring af attention.

## Modul 7: Specialisering af sprogmodeller

### Uge 13 (11. til 15. jan): Prompting og RAG
Videoer: https://www.youtube.com/watch?v=T-D1OfcDW1M, https://www.youtube.com/watch?v=zYGDpG-pTho, https://www.youtube.com/watch?v=7xTGNNLPyMI (første time)
- Dag 61: Vælg domæne, lav evalueringssæt med 20 spørgsmål, mål baseline prompt.
- Dag 62: Embeddings og similarity search.
- Dag 63: Chunking og vektordatabase (Chroma/FAISS).
- Dag 64: Generering med kontekst og kildehenvisning.
- Dag 65: Evaluér RAG mod baseline.

### Uge 14 (18. til 22. jan): LoRA finjustering
Videoer: https://www.youtube.com/watch?v=t1caDsMzWBk, https://www.youtube.com/watch?v=bZQun8Y4L2A
- Dag 66: Datasæt med ca. 200 eksempler.
- Dag 67: LoRA med `peft` i Colab på lille åben model.
- Dag 68: Evaluér mod basismodel.
- Dag 69: Fejlanalyse og ny træning.
- Dag 70: MODULAFLEVERING: rapport prompting vs RAG vs LoRA, model card.

## Modul 8: AI agenter og eksamen

### Uge 15 (25. til 29. jan): Agenter
Videoer: https://www.youtube.com/watch?v=F8NKVhkZZWI, https://www.youtube.com/watch?v=sal78ACtGTc
- Dag 71: Tool calling med to værktøjer.
- Dag 72: Agentløkke fra bunden uden framework.
- Dag 73: Agenten bruger RAG systemet som værktøj.
- Dag 74: Testcases, fejltyper, omkostning.
- Dag 75: Projektforslag til eksamen, godkendes af læreren.

### Uge 16 (1. til 5. feb): Eksamensprojekt
- Dag 76: Data og baseline.
- Dag 77: Kerneløsning fra ende til anden.
- Dag 78: Evaluering mod succeskriterier.
- Dag 79: Forbedringer og fejlanalyse.
- Dag 80: EKSAMEN: README rapport (max 5 sider), demo, refleksion. Læreren stiller 5 mundtlige spørgsmål.
