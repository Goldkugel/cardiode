# CARDIO:DE

CARDIO:DE is the first distributable and freely available German clinical corpus containing 500 discharge letters from the cardiology deparment of the Heidelberg University Hospital covering a broad range of cardiovascular clinical routine documents.

All discharge letters were carefully anonymized by domain experts using automatic (Richter-Pechanski et al., 2019) and manual methods.

CARDIO:DE contains manual gold standard annotations of:

1. medication information (ActiveIng, Drug, Duration, Form, Frequency, Strength)
2. section types (Abschluss, Anamnese, Anrede, Diagnosen, AufnahmeMedikation, Befunde, EchoBefunde, AktuellDiagnosen, EntlassMedikation, KuBefunde, Labor, Anderes, RisikofaktorenAllergien, Zusammenfassung)

CARDIO:DE contains 500 discharge letters in plain text files and in tsv3 format (<a href="https://webanno.github.io/webanno/releases/3.4.5/docs/user-guide.html#sect_webannotsv">documentation</a>). 

The folder structure is as follows:

cardiode/
├── tsv/
│   ├── CARDIODE100_heldout
│   ├── CARDIODE400_main
└── txt/
    ├── CARDIODE100_heldout
    └── CARDIODE400_main
	
CARDIO:DE is split into CARDIO:DE400 and CARDIO:DE100. Annotations of CARDIO:DE100 are kept internally as held-out data for future shared task purposes.
