## Code list library

***Code lists for***
  * [Depression](#depression)
  * [Anxiety](#anxiety)
  * [Self harm](#self-harm)
  * [Eating disorders](#eating-disorders)
  * [Alcohol misuse](#alcohol-misuse)
  * [Substance misuse](#substance-misuse)
  * [Severe mental illness](#severe-mental-illness)

### The Networked Data Lab

<img src="ndlbanner.png" width="405" height="96">

The [Networked Data Lab](https://www.health.org.uk/funding-and-partnerships/our-partnerships/the-networked-data-lab) is a Health Foundation research programme bringing together five different partners across the UK - including Public Health Wales, NHS Grampian and CCGs in North West London, Leeds, Liverpool and Wirral. In 2021, we started working on children and young people's mental health using linked health and social care datasets. During this time, we identified the need for common code lists to enable the comparability of results.

Our analysts used code lists to identify users of mental health services in their data, in some cases stratified by condition or type of contact. We performed an initial search of publicly-available code lists, to help our partners identify those that were relevant to their research questions.

### How this library should be used

The code list library shown here is the result of our initial search. We considered the following mental health conditions or disorders:
* Depression
* Anxiety
* Self harm
* Eating disorders
* Alcohol/substance misuse
* Severe mental illness, which includes schizophrenia spectrum, bipolar affective disorders and psychosis

We are providing this library as a resource to other researchers, but cannot guarantee the validity of all code lists - users will need to make a judgement on whether these are appropriate to their research questions. This library is aimed at an audience already familiar with the use of code lists in health care data. The code lists themselves are hosted on the provider's page, which are linked here.

### Our approach

We considered the following types of codes:
- READ/SNOMED-CT codes for primary care data
- ICD-10 codes for secondary care data
- BNF codes for medicines (British National Formulary)

Our main resources were:

* [CALIBER's chronological map of human health](https://www.caliberresearch.org/portal/phenotypes) (Health Data Research UK - see associated [Lancet](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(19)30012-3/fulltext) publication)
* [CALIBER's Phenotype Library](https://portal.caliberresearch.org/disease-or-syndrome) (Health Data Research UK)
* [OpenCodelists](https://www.opencodelists.org/)
* [ClinicalCodes](https://clinicalcodes.rss.mhs.man.ac.uk/)
* [ATHENA](https://athena.ohdsi.org/search-terms/start)
* [CPRD @ Cambridge group](https://www.phpc.cam.ac.uk/pcu/research/research-groups/crmh/cprd_cam/codelists/v11/)
* [Anna Head's mapping of READ codes from CALIBER to SNOMED-CT](https://github.com/annalhead/CPRD_multimorbidity_codelists) (University of Liverpool)
* [LHSTM DataCompass](https://datacompass.lshtm.ac.uk/)
* [Centre for Disease Control and Prevention](https://phinvads.cdc.gov/vads/SearchVocab.action )

We also referred to code lists directly uploaded with scientific publications.

### Depression

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Depression | Secondary | ICD-10 codes | CALIBER (HDR UK) | :paperclip: [link](https://www.caliberresearch.org/portal/phenotypes/depression) |
| Depression | Primary | READ codes | CALIBER (HDR UK) | :paperclip: [link](https://www.caliberresearch.org/portal/phenotypes/depression) |
| Depression | Primary | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_DEP152_MC_V1-1_Oct2018.zip) |
| Depression | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Depression.csv) |
| Talking therapies | Primary | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/2186/) |
| Depression | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Depression.csv) |
| Antidepressants (all types) | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/0403/) |
| Antidepressants (SSRIs) | Medicines | BNF codes | OpenSAFELY via OpenCodelists | :paperclip: [link](https://www.opencodelists.org/codelist/opensafely/selective-serotonin-reuptake-inhibitors-dmd/6a572e55/) |
| Antidepressants (all types) | Medicines | READ codes | ClinicalCodes (University of Manchester Institute of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/59/codelist/res55-antidepressant/download/) |
| Antidepressants (all types) | Medicines | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/1402/) |
| Antidepressants (all types) | Medicines | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_DEP153_PC_V1-1_Oct2018.zip) |
| Antidepressants (all types) | Medicines | SNOMED codes | Centers for Disease Control and Prevention (CDC) | :paperclip: [link](https://phinvads.cdc.gov/vads/ViewCodeSystemConcept.action?oid=2.16.840.1.113883.6.96&code=372720008) |
| Antidepressants (SSRIs) | Medicines | SNOMED codes | Centers for Disease Control and Prevention (CDC) | :paperclip: [link](https://phinvads.cdc.gov/vads/ViewCodeSystemConcept.action?oid=2.16.840.1.113883.6.96&code=373225007) |
| Antidepressants (SSRIs) | Medicines | SNOMED codes | OpenCodelists | :paperclip: [link](https://www.opencodelists.org/snomedct/concept/349854005/) |

### Anxiety

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Anxiety | Secondary | ICD-10 codes | CALIBER (HDR UK) | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-anxiety-lgwmqosnaterehdytpzbwy) |
| Anxiety | Primary  | READ codes | University of Bristol | :paperclip: [link](https://bmjopen.bmj.com/content/bmjopen/6/12/e013167/DC1/embed/inline-supplementary-material-1.pdf?download=true) |
| Anxiety | Primary | READ codes | CALIBER (HDR UK) | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-anxiety-lgwmqosnaterehdytpzbwy) |
| Anxiety | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Anxiety%20disorders.csv) |
| Anxiety (and other neurotic, stress related & somatoform disorders) | Primary | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_ANX140_MC_V1-1_Oct2018.zip) |
| Anxiety | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Anxiety%20disorders.csv) |
| Hypnotics and anxiolytics | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/0401/) |
| Drugs with anxiety as possible indication | Medicines | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_ANX141_PC_V1-1_Oct2018.zip) |
| Drugs with anxiety as possible indication | Medicines | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/1399/) |
| Drugs with anxiety or depression as possible indication | Medicines | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/2027/) |
| Hypnotics and anxiolytics | Medicines | READ codes | University of Bristol | :paperclip: [link](https://bmjopen.bmj.com/content/bmjopen/6/12/e013167/DC1/embed/inline-supplementary-material-1.pdf?download=true) |
| Anxiolytic, sedative, hypnotic or tranquilizer | Medicines | SNOMED codes | Centers for Disease Control and Prevention (CDC) | :paperclip: [link](https://phinvads.cdc.gov/vads/ViewCodeSystemConcept.action?oid=2.16.840.1.113883.6.96&code=373209002) |

### Self harm

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Self harm | Secondary | ICD-10 | CDC | :paperclip: [link](https://www.cdc.gov/nchs/data/nhsr/nhsr108.pdf) |
| Self harm, suicidal ideation and suicidal attempt | Secondary | ICD-10 | US Agency for Healthcare Research and Quality (Healthcare Cost and Utilization Project) | :paperclip: [link](https://www.hcup-us.ahrq.gov/reports/ataglance/HCUPanalysisPedEDVisitsSuicide.pdf) |
| Self harm | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/carr-selfharm-at4xpewdjeacvfkgbikmhm) |
| Self harm | Primary | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/1428/ ) |
| Self harm | Primary | SNOMED codes | National Center for Biomedical Ontology | :paperclip: [link](https://bioportal.bioontology.org/ontologies/SNOMEDCT/?p=classes&conceptid=http%3A%2F%2Fpurl.bioontology.org%2Fontology%2FSNOMEDCT%2F248062006) |
| Self harm and suicidal behaviour | Primary | SNOMED codes | NHS County Durham and Darlington | :paperclip: [link](https://www.cddft.nhs.uk/media/654963/09.18.12%20self-harm%20and%20suicidal%20intent.pdf) |
| Suicidal behaviour | Primary | SNOMED codes | National Center for Biomedical Ontology | :paperclip: [link](https://bioportal.bioontology.org/ontologies/SNOMEDCT/?p=classes&conceptid=http%3A%2F%2Fpurl.bioontology.org%2Fontology%2FSNOMEDCT%2F425104003) |
| Suicidal ideation | Primary | SNOMED codes | MedGEN (NCBI) | :paperclip: [link](https://www.ncbi.nlm.nih.gov/medgen/140856) |

### Eating disorders

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Eating disorders (anorexia and bulimia) | Secondary | ICD-10 codes | CALIBER (HDR UK) | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-eating-dz-uhasdhczdsx5cfjwmvfcnv) |
| Anorexia | Primary | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/1915/) |
| Eating disorders (anorexia and bulimia) | Primary | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_ANO139_MC_V1-1_Oct2018.zip) |
| Eating disorders (anorexia and bulimia) | Primary | READ codes | CALIBER (HDR UK) | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-eating-dz-uhasdhczdsx5cfjwmvfcnv) |
| Eating disorders (anorexia, bulimia and referral to specialist service) | Primary | READ codes | ClinicalCodes (University of Manchester Institue of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/36/codelist/res36-eating-disorder/) |
| Eating disorders (anorexia, bulimia and referral to specialist service) | Primary | READ codes | ClinicalCodes (University of Manchester Institue of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/38/codelist/res38-eating-disorder/) |
| Eating disorders (anorexia, bulimia and referral to specialist service) | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Eating%20Disorders.csv) |
| Eating disorders (anorexia, bulimia and referral to specialist service) | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Eating%20Disorders.csv) |

### Alcohol misuse

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Alcohol Status | Secondary | ICD-10 codes | CDC | :paperclip: [link](https://www.cdc.gov/alcohol/ardi/alcohol-related-icd-codes.html) |
| Alcohol Problems | Secondary | ICD-10 codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-alc-problems-uxiyf5acxtxnjzpnvwfye4 ) |
| Alcohol misuse | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Alcohol%20Misuse.csv) |
| Alcohol Problems | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-alc-problems-uxiyf5acxtxnjzpnvwfye4 ) |
| Alcohol Status | Primary | READ codes | CALIBER | :paperclip: [link](https://www.caliberresearch.org/portal/phenotypes/alcohol) |
| Alcohol Status | Primary | READ codes | ClinicalCodes | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/17/codelist/res17-alcohol-status/) |
| Alcohol Status | Primary | READ codes | CALIBER | :paperclip: [link](https://www.caliberresearch.org/portal/phenotypes/alcohol) |
| Harmful alcohol use | Primary | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/938/ ) |
| Alcohol misuse | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Alcohol%20Misuse.csv) |
| Drugs to treat alcoholism | Medicines | BNF codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/827/ ) |
| Drugs used for alcohol dependence | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/041001/) |

### Substance misuse

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Substance misuse | Secondary | ICD-10 codes | Swansea University | :paperclip: [link](https://www.medrxiv.org/content/medrxiv/early/2021/06/26/2021.06.21.21259276/DC4/embed/media-4.pdf?download=true) |
| Other psychoactive substance misuse | Secondary | ICD-10 codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-substance-misuse-6k6xkuwjkn9nycafszswyp) |
| Illicit substance/nonprescribed drug use, Under the care of substance misuse services | Primary | READ codes | NHS England | :paperclip: [link](https://www.england.nhs.uk/statistics/wp-content/uploads/sites/2/2019/04/FINAL-Technical-definition-2019-20-physical-health-SMI-data-collection-16.04.2019.pdf) |
| Other psychoactive substance misuse | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-substance-misuse-6k6xkuwjkn9nycafszswyp) |
| Psychoactive substance misuse | Primary | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_PSM173_MC_V1-1_Oct2018.zip) |
| Substance misuse | Primary | READ codes | ClinicalCodes (University of Manchester Institue of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/55/codelist/res55-substance_misuse/) |
| Substance misuse | Primary | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/2185/) |
| Substance misuse | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Substance%20Misuse.csv ) |
| Substance misuse | Primary | READ codes | Swansea University | :paperclip: [link](https://www.medrxiv.org/content/medrxiv/early/2021/06/26/2021.06.21.21259276/DC4/embed/media-4.pdf?download=true) |
| Illicit substance/nonprescribed drug use, Under the care of substance misuse services | Primary | SNOMED codes | NHS England | :paperclip: [link](https://www.england.nhs.uk/statistics/wp-content/uploads/sites/2/2019/04/FINAL-Technical-definition-2019-20-physical-health-SMI-data-collection-16.04.2019.pdf) |
| Substance misuse | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Substance%20Misuse.csv ) |
| Drugs used for opioid dependence | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/041003/) |

### Severe mental illness

| Condition or medicine | Setting | Type | Source | Link |
| --- | --- | --- | --- | --- |
| Bipolar affective disorder and mania | Secondary | ICD-10 codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-bad-3mzxcczrugwenywt4ee75n) |
| Obsessive-compulsive disorder | Secondary | ICD-10 codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-ocd-6e56trtebtyvcebzxgcxcw) |
| Personality disorders | Secondary | ICD-10 codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-pd-nbqnqx3pxna42bgzzhajr7) |
| Schizophrenia, schizotypal and delusional disorders | Secondary | ICD-10 codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-schizo-3l5nkpq72j7aasdmvy73qm) |
| Severe Mental Illness | Secondary | ICD-10 codes | QCOVID COVID-19 Population Risk Assessment | :paperclip: [link](https://datadictionary.nhs.uk/Covid19PRA/Severe_Mental_Illness.html) |
| Severe Mental Illness (Schizophrenia, Persistent delusional disorder, Schizoaffective disorder, Bipolar disorder) | Secondary | ICD-10 codes | Norwegian Institute of Public Health | :paperclip: [link](https://bmcpsychiatry.biomedcentral.com/articles/10.1186/s12888-017-1256-8) |
| Bipolar affective disorder and mania | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-bad-3mzxcczrugwenywt4ee75n) |
| Bipolar affective disorder and mania | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Bipolar%20affective%20disorder%20and%20mania.csv) |
| Bipolar disorder | Primary | READ codes | ClinicalCodes (University of Manchester Institue of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/36/codelist/res36-bipolar-disorder/ ) |
| Obsessive-compulsive disorder | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-ocd-6e56trtebtyvcebzxgcxcw) |
| Personality disorders | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-pd-nbqnqx3pxna42bgzzhajr7) |
| Personality disorders | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Personality%20disorders.csv) |
| Schizophrenia | Primary | READ codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Schizophrenia.csv) |
| Schizophrenia (and related non-organic psychosis) or bipolar disorder | Primary | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_SCZ175_MC_V1-1_Oct2018.zip) |
| Schizophrenia, schizotypal and delusional disorders | Primary | READ codes | CALIBER | :paperclip: [link](https://portal.caliberresearch.org/phenotypes/kuan-schizo-3l5nkpq72j7aasdmvy73qm) |
| Severe Mental Illness | Primary | READ codes | LSHTM Data Compass | :paperclip: [link](https://datacompass.lshtm.ac.uk/id/eprint/868/) |
| Severe Mental Illness | Primary | READ codes | University of Manchester, University of York, University of Lancaster | :paperclip: [link](https://www.researchgate.net/publication/296271122_S1_SMI_Code-Lists_Code-lists_used_to_define_Severe_Mental_Illness) |
| Bipolar affective disorder and mania | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Bipolar%20affective%20disorder%20and%20mania.csv) |
| Personality disorders | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Personality%20disorders.csv) |
| Schizophrenia | Primary | SNOMED codes | CALIBER (HDR UK), adapted to SNOMED by Anna Head (PhD, University of Liverpool) | :paperclip: [link](https://github.com/annalhead/CPRD_multimorbidity_codelists/blob/main/codelists/Schizophrenia.csv) |
| Severe Mental Illness | Primary | SNOMED codes | OpenCodelists (PRIMIS Covid Vaccination Uptake Reporting) | :paperclip: [link](https://www.opencodelists.org/codelist/primis-covid19-vacc-uptake/sev_mental/v1/#full-list) |
| Severe Mental Illness | Primary | SNOMED codes | QCOVID COVID-19 Population Risk Assessment | :paperclip: [link](https://datadictionary.nhs.uk/Covid19PRA/Severe_Mental_Illness.html) |
| Antipsychotic depot injections | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/040202/) |
| Antipsychotic drugs | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/040201/ ) |
| Drugs used for mania and hypomania | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/040203/) |
| Mania and hypomania | Medicines | BNF codes | OpenPrescribing | :paperclip: [link](https://openprescribing.net/bnf/040203/) |
| Antipsychotic drugs | Medicines | READ codes | ClinicalCodes (University of Manchester Institue of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/55/codelist/res55-antipsychotic/ ) |
| Bipolar disorder | Medicines | READ codes | ClinicalCodes (University of Manchester Institue of Population Health) | :paperclip: [link](https://clinicalcodes.rss.mhs.man.ac.uk/medcodes/article/36/codelist/res36-bipolar-disorder/ ) |
| Schizophrenia (and related non-organic psychosis) or bipolar disorder | Medicines | READ codes | CPRD @ Cambridge | :paperclip: [link](http://www.cprdrepos.phpc.cam.ac.uk/V11/CPRDCAM_SCZ176_PC_V1-1_Oct2018.zip) |

### Authors

* Sebastien Peytrignet, Senior Data Analyst at the Health Foundation ([GitHub](https://github.com/sg-peytrignet/)) ([Twitter](https://twitter.com/SebastienPeytr2))
* Jorgen Engmann, Senior Data Manager at the Health Foundation ([Twitter](https://twitter.com/EngmannJorgen))
