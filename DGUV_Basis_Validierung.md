#### Übersicht der validierten Basis Profile

[BehandelndeEinrichtung](#BehandelndeEinrichtung)
[DArzt](#DArzt)
[DArztOrganisation](#DArztOrganisation)
[Datenschutz](#Datenschutz)
[DiagnoseFreitext](#DiagnoseFreitext)
[DiagnoseStrukturiert](#DiagnoseStrukturiert)
[Krankenkasse](#Krankenkasse)
[Leistungserbringer](#Leistungserbringer)
[Pflegekasse](#Pflegekasse)
[Unfallbetrieb](#Unfallbetrieb)
[Unfallereignis](#Unfallereignis)
[Unfallort](#Unfallort)
[Unfallversicherungstraeger](#Unfallversicherungstraeger)
[VersichertenVerhältnis](#VersichertenVerhältnis)
[VersichertePerson](#VersichertePerson)
[WeiterbehandelndeOrganisation](#WeiterbehandelndeOrganisation)
[WeiterbehandelnderArzt](#WeiterbehandelnderArzt)



#### Validierungsergebnisse

<a id="BehandelndeEinrichtung">BehandelndeEinrichtung</a>

| Art           | Bezeichnung                               | Bemerkung |
| ------------- | ----------------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_BehandelndeEinrichtung.xml |           |
| Profil        | DGUV_Basis_PR_BehandelndeEinrichtung.xml  |           |
| Code Set(s)   |                                           |           |
| Value Set(s)  |                                           |           |
| Validiert am: | 22.09.2025                                |           |

**Validierung: 20.05.2025**

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_BehandelndeEinrichtung.xml 04:51:50
[1, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung: 22.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_BehandelndeEinrichtung.xml 02:43:30
[2, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[19, 15] Organization.identifier[1].type.coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS-Base_identifier_type' could not be found, so the code cannot be validated
[19, 15] Organization.identifier[1].type: Error - !!!!!!!!!!!!!!!!!!Das im Profil http://fhir.dguv.de/Basis/Organization/DGUV-Basis-PR-BehandelndeEinrichtung|1.3 definierte Pattern [System https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type, Code KSN, und Anzeige 'null'] wurde nicht gefunden. Probleme: [ValidationMessage[level=ERROR,type=VALUE,location=Organization.identifier[1].type.coding.system,message=!!!!Der Wert ist 'https://fhir.kbv.de/CodeSystem/KBV_CS-Base_identifier_type', muss aber 'https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type' sein.]]
[19, 15] Organization.identifier[1].type: Warning - Keiner der angegebenen Codes ist im Valueset 'IdentifierType' (http://hl7.org/fhir/ValueSet/identifier-type|4.0.1), und ein Code sollte aus diesem Valueset stammen, es sei denn, er enthält keinen geeigneten Code) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS-Base_identifier_type#KSN)
[21, 94] Organization.identifier[1].type.coding[0].system: Error - !!!!Der Wert ist 'https://fhir.kbv.de/CodeSystem/KBV_CS-Base_identifier_type', muss aber 'https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type' sein.
```

**Validierung: 22.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_BehandelndeEinrichtung.xml 01:51:44
[2, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[19, 15] Organization.identifier[1].type: Warning - Keiner der angegebenen Codes ist im Valueset 'IdentifierType' (http://hl7.org/fhir/ValueSet/identifier-type|4.0.1), und ein Code sollte aus diesem Valueset stammen, es sei denn, er enthält keinen geeigneten Code) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type#KSN)
```

**Validierung: 24.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_BehandelndeEinrichtung.xml 01:51:44
[2, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[19, 15] Organization.identifier[1].type: Warning - Keiner der angegebenen Codes ist im Valueset 'IdentifierType' (http://hl7.org/fhir/ValueSet/identifier-type|4.0.1), und ein Code sollte aus diesem Valueset stammen, es sei denn, er enthält keinen geeigneten Code) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type#KSN)
```





  <a id="DArzt">DArzt</a>

| Art           | Bezeichnung              | Bemerkung |
| ------------- | ------------------------ | --------- |
| Beispieldatei | DGUV_Basis_Bsp_DArzt,xml |           |
| Profil        | DGUV_Basis_PR_DArzt.xml  |           |
| Code Set(s)   |                          |           |
| Value Set(s)  |                          |           |
| Validiert am: | 22.09.2025               |           |

**Validierung:**   22.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DArzt.xml 04:32:57
[20, 47] PractitionerRole: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[31, 9] PractitionerRole.code[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV-CS-Base-Role-Care' version '1.6.0' could not be found, so the code cannot be validated. No versions of this code system are known
[32, 13] PractitionerRole.code[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/PractitionerRole/DGUV-Basis-PR-DArzt|1.3 überein.
[39, 14] PractitionerRole.specialty[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE' version '1.03' could not be found, so the code cannot be validated. Valid versions: []
[39, 14] PractitionerRole.specialty[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Practice Setting Code Value Set' (http://hl7.org/fhir/ValueSet/c80-practice-codes|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE#01)
[40, 13] PractitionerRole.specialty[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/PractitionerRole/DGUV-Basis-PR-DArzt|1.3 überein.

```



**Validierung: 24.09.2025**

```
-------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DArzt.xml 02:06:23
[20, 47] PractitionerRole: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[31, 9] PractitionerRole.code[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/gender-amtlich' version '1.6.0' could not be found, so the code cannot be validated. No versions of this code system are known
[32, 13] PractitionerRole.code[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/PractitionerRole/DGUV-Basis-PR-DArzt|1.3 überein.
[39, 14] PractitionerRole.specialty[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE' version '1.03' could not be found, so the code cannot be validated. Valid versions: []
[39, 14] PractitionerRole.specialty[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Practice Setting Code Value Set' (http://hl7.org/fhir/ValueSet/c80-practice-codes|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE#01)
[40, 13] PractitionerRole.specialty[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/PractitionerRole/DGUV-Basis-PR-DArzt|1.3 überein.

```





  <a id="DArztOrganisation">DArztOrganisation</a>

| Art           | Bezeichnung                          | Bemerkung |
| ------------- | ------------------------------------ | --------- |
| Beispieldatei | DGUV_Basis_Bsp_DArztOrganisation,xml |           |
| Profil        | DGUV_Basis_PR_DArztOrganisation.xml  |           |
| Code Set(s)   |                                      |           |
| Value Set(s)  |                                      |           |
| Validiert am: | 20.05.2025                           |           |

**Validierung:**   20.05.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DArztOrganisation.xml 05:02:14
[1, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)

```

**Validierung:**   24.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DArztOrganisation.xml 02:15:33
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[37, 15] Organization.identifier[1].type: Warning - Keiner der angegebenen Codes ist im Valueset 'IdentifierType' (http://hl7.org/fhir/ValueSet/identifier-type|4.0.1), und ein Code sollte aus diesem Valueset stammen, es sei denn, er enthält keinen geeigneten Code) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type#KSN)

```



 <a id="Datenschutz">Datenschutz</a>

| Art           | Bezeichnung                    | Bemerkung |
| ------------- | ------------------------------ | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Datenschutz.xml |           |
| Profil        | DGUV_Basis_PR_Datenschutz.xml  |           |
| Code Set(s)   |                                |           |
| Value Set(s)  |                                |           |
| Validiert am: | 21.05.2025                     |           |

**Validierung:** 21.05.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Datenschutz.xml 08:35:56
[2, 42] Observation: Warning - !!Alle Observations sollten ein effectiveDateTime oder eine effectivePeriode haben
[2, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:** 22.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Datenschutz.xml 02:28:49
[24, 42] Observation: Warning - !!Alle Observations sollten ein effectiveDateTime oder eine effectivePeriode haben
[24, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:**   24.05.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Datenschutz.xml 02:19:39
[24, 42] Observation: Warning - !!Alle Observations sollten ein effectiveDateTime oder eine effectivePeriode haben
[24, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)

```



<a id="DiagnoseFreitext">DiagnoseFreitext</a>

| Art           | Bezeichnung                         | Bemerkung |
| ------------- | ----------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_DiagnoseFreitext.xml |           |
| Profil        | DGUV_Basis_PR_DiagnoseFreitext.xml  |           |
| Code Set(s)   |                                     |           |
| Value Set(s)  |                                     |           |
| Validiert am: | 19.05.2025                          |           |

**Validierung:** 19.05.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\local_validation\BASE\DGUV_Basis_Bsp_DiagnoseFreitext.xml 05:09:02
[2, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:** 22.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DiagnoseFreitext.xml 04:47:41
[20, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:** 24.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DiagnoseFreitext.xml 02:21:31
[20, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```



 <a id="DiagnoseStrukturiert">DiagnoseStrukturiert</a>

| Art           | Bezeichnung                             | Bemerkung |
| ------------- | --------------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_DiagnoseStrukturiert.xml |           |
| Profil        | DGUV_Basis_PR_DiagnoseStrukturiert.xml  |           |
| Code Set(s)   |                                         |           |
| Value Set(s)  |                                         |           |
| Validiert am: | 22.09.2025                              |           |

**Validierung:** 21.05.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\local_validation\BASE\DGUV_Basis_Bsp_DiagnoseStrukturiert.xml 05:52:54
[2, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[7, 8] Condition.code.coding[0].system: Warning - A definition for CodeSystem 'http://fhir.de/CodeSystem/bfarm/icd-10-gm' version '2019' could not be found, so the code cannot be validated. Valid versions: []
```



**Validierung:** 22.09.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\local_validation\BASE\DGUV_Basis_Bsp_DiagnoseStrukturiert.xml 05:52:54
[2, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[7, 8] Condition.code.coding[0].system: Warning - A definition for CodeSystem 'http://fhir.de/CodeSystem/bfarm/icd-10-gm' version '2019' could not be found, so the code cannot be validated. Valid versions: []
```



**Validierung:** 24.09.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_DiagnoseStrukturiert.xml 02:25:23
[20, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[26, 8] Condition.code.coding[0].system: Warning - A definition for CodeSystem 'http://fhir.de/CodeSystem/bfarm/icd-10-gm' version '2019' could not be found, so the code cannot be validated. Valid versions: []
```





 <a id="Krankenkasse">Krankenkasse</a>

| Art           | Bezeichnung                     | Bemerkung |
| ------------- | ------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Krankenkasse.xml |           |
| Profil        | DGUV_Basis_PR_Krankenkasse.xml  |           |
| Code Set(s)   |                                 |           |
| Value Set(s)  |                                 |           |
| Validiert am: | 22.09.2025                      |           |

**Validierung:**  20.05.2025

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Krankenkasse.xml 05:27:24
[1, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)

```

**Validierung:**  22.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Krankenkasse.xml 04:51:46
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:**  24.09.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Krankenkasse.xml 02:27:16
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```





<a id="Leistungserbringer">Leistungserbringer</a>

| Art           | Bezeichnung                           | Bemerkung |
| ------------- | ------------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Leistungserbringer.xml |           |
| Profil        | DGUV_Basis_PR_Leistungserbringer.xml  |           |
| Code Set(s)   |                                       |           |
| Value Set(s)  |                                       |           |
| Validiert am: | 24.09.2025                            |           |

**Validierung 22.09.2025:**

```

----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Leistungserbringer.xml 02:29:21
[2, 43] Practitioner: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)

```

**Validierung:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Leistungserbringer.xml 02:29:21
[2, 43] Practitioner: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)

```





<a id="Pflegekasse">Pflegekasse</a>

| Art           | Bezeichnung                    | Bemerkung |
| ------------- | ------------------------------ | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Pflegekasse.xml |           |
| Profil        | DGUV_Basis_PR_Pflegekasse.xml  |           |
| Code Set(s)   |                                |           |
| Value Set(s)  |                                |           |
| Validiert am: | 24.09.2025                     |           |

**Validierung 22.09.2025:**

```

----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Pflegekasse.xml 05:21:11
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:**

```

----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Pflegekasse.xml 02:33:03
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```



<a id="Unfallbetrieb">Unfallbetrieb</a>

| Art           | Bezeichnung                      | Bemerkung |
| ------------- | -------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Unfallbetrieb.xml |           |
| Profil        | DGUV_Basis_PR_Unfallbetrieb.xml  |           |
| Code Set(s)   |                                  |           |
| Value Set(s)  |                                  |           |
| Validiert am: | 24.09.2025                       |           |

**Validierung 22.09.2025:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallbetrieb.xml 04:59:16
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```



**Validierung:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallbetrieb.xml 02:34:40
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```





<a id="Unfallereignis">Unfallereignis</a>

| Art           | Bezeichnung                       | Bemerkung |
| ------------- | --------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Unfallereignis.xml |           |
| Profil        | DGUV_Basis_PR_Unfallereignis.xml  |           |
| Code Set(s)   |                                   |           |
| Value Set(s)  |                                   |           |
| Validiert am: | 24.09.2025                        |           |

**Validierung 22.09.2025:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallereignis.xml 05:00:43
[20, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[20, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[41, 36] Observation.extension[0].extension[1]: Error - Constraint failed: ext-1: 'Must have either extensions or value[x], not both' (defined in http://hl7.org/fhir/StructureDefinition/Extension)
[41, 36] Observation.extension[0].extension[1]: Error - Extension.extension:Pflegekasse.value[x]: mindestens erforderlich = 1, aber nur gefunden 0
[41, 36] Observation.extension[0].extension[1]: Error - Observation.extension:Pflegeunfall.extension:Pflegekasse.value[x]: mindestens erforderlich = 1, aber nur gefunden 0
[42, 16] /f:Observation/f:extension/f:extension: Error - !!Undefiniertes Element 'value'
[48, 9] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-Verletzungsartenverzeichnis|1.3
[60, 11] Observation.component[0].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[70, 11] Observation.component[1].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[80, 11] Observation.component[2].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[90, 11] Observation.component[3].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[100, 11] Observation.component[4].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
```



**Validierung:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallereignis.xml 02:37:19
[20, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[20, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[41, 36] Observation.extension[0].extension[1]: Error - Constraint failed: ext-1: 'Must have either extensions or value[x], not both' (defined in http://hl7.org/fhir/StructureDefinition/Extension)
[41, 36] Observation.extension[0].extension[1]: Error - Extension.extension:Pflegekasse.value[x]: mindestens erforderlich = 1, aber nur gefunden 0
[41, 36] Observation.extension[0].extension[1]: Error - Observation.extension:Pflegeunfall.extension:Pflegekasse.value[x]: mindestens erforderlich = 1, aber nur gefunden 0
[42, 16] /f:Observation/f:extension/f:extension: Error - !!Undefiniertes Element 'value'
[48, 9] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-Verletzungsartenverzeichnis|1.3
[60, 11] Observation.component[0].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[70, 11] Observation.component[1].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[80, 11] Observation.component[2].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[90, 11] Observation.component[3].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[100, 11] Observation.component[4].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3

```





<a id="Unfallort">Unfallort</a>

| Art           | Bezeichnung                  | Bemerkung |
| ------------- | ---------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Unfallort.xml |           |
| Profil        | DGUV_Basis_PR_Unfallort.xml  |           |
| Code Set(s)   |                              |           |
| Value Set(s)  |                              |           |
| Validiert am: | 24.09.2025                   |           |

**Validierung 22.09.2025:**

```

----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallort.xml 05:02:32
[20, 39] Location: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallort.xml 02:39:23
[20, 39] Location: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```





<a id="Unfallversicherungstraeger">Unfallversicherungstraeger</a>

| Art           | Bezeichnung                                   | Bemerkung |
| ------------- | --------------------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_Unfallversicherungstraeger.xml |           |
| Profil        | DGUV_Basis_PR_Unfallversicherungstraeger.xml  |           |
| Code Set(s)   |                                               |           |
| Value Set(s)  |                                               |           |
| Validiert am: | 22.09.2025                                    |           |

**Validierung:**

```

```



 <a id="VersichertenVerhaeltnis">VersichertenVerhaeltnis</a>

| Art           | Bezeichnung                                | Bemerkung |
| ------------- | ------------------------------------------ | --------- |
| Beispieldatei | DGUV_Basis_Bsp_VersichertenVerhaeltnis.xml |           |
| Profil        | DGUV_Basis_PR_VersichertenVerhaeltnis.xml  |           |
| Code Set(s)   |                                            |           |
| Value Set(s)  |                                            |           |
| Validiert am: | 24.09.2025                                 |           |

**Validierung 21.05.2025:** 

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_VersichertenVerhaeltnis.xml 08:47:22
[2, 39] Coverage: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```



**Validierung 22.09.2025:** 

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallversicherungstraeger.xml 05:04:13
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_Unfallversicherungstraeger.xml 02:41:07
[20, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```







<a id="VersichertePerson">VersichertePerson</a>

| Art           | Bezeichnung                                        | Bemerkung |
| ------------- | -------------------------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_VersichertePerson.xml               |           |
| Profil        | DGUV_Basis_PR_VersichertePerson.xml                |           |
| Code Set(s)   | http://fhir.de/CodeSystem/identifier-type-de-basis |           |
| Value Set(s)  |                                                    |           |
| Validiert am: | 22.09.2025                                         |           |

**Validierung  19.05.2025:** 

```
C:\Users\Ext.Matten.Friedhelm\sources\local_validation\BASE\DGUV_Basis_Bsp_VersichertePerson.xml 04:09:06
[-1, -1] n/a: Information - Alles OK
```



**Validierung 22.09.2025:**  

```
C:\Users\Ext.Matten.Friedhelm\sources\local_validation\BASE\DGUV_Basis_Bsp_VersichertePerson.xml 04:09:06----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_VersichertePerson.xml 05:07:38
[-1, -1] n/a: Information - Alles OK
[-1, -1] n/a: Information - Alles OK
```

**Validierung:** 

```

```







<a id="WeiterbehandelndeOrganisation">WeiterbehandelndeOrganisation</a>

| Art           | Bezeichnung                                      | Bemerkung |
| ------------- | ------------------------------------------------ | --------- |
| Beispieldatei | DGUV_Basis_Bsp_WeiterbehandelndeOrganisation.xml |           |
| Profil        | DGUV_Basis_PR_WeiterbehandelndeOrganisation.xml  |           |
| Code Set(s)   |                                                  |           |
| Value Set(s)  |                                                  |           |
| Validiert am: | 22.09.2025                                       |           |

**Validierung 20.05.2025:** 

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_WeiterbehandelndeOrganisation.xml 05:32:26
[1, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validierung  22.09.2025:** 

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_WeiterbehandelndeOrganisation.xml 05:13:10
[2, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[29, 21] Organization.identifier[2]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/Organization/DGUV-Basis-PR-WeiterbehandelndeOrganisation|1.3 überein.
[30, 15] Organization.identifier[2].type: Warning - Keiner der angegebenen Codes ist im Valueset 'IdentifierType' (http://hl7.org/fhir/ValueSet/identifier-type|4.0.1), und ein Code sollte aus diesem Valueset stammen, es sei denn, er enthält keinen geeigneten Code) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type|1.7.0#KSN)

```

**Validierung 24.09.2025:** 

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_WeiterbehandelndeOrganisation.xml 02:44:57
[2, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[29, 21] Organization.identifier[2]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/Organization/DGUV-Basis-PR-WeiterbehandelndeOrganisation|1.3 überein.
[30, 15] Organization.identifier[2].type: Warning - Keiner der angegebenen Codes ist im Valueset 'IdentifierType' (http://hl7.org/fhir/ValueSet/identifier-type|4.0.1), und ein Code sollte aus diesem Valueset stammen, es sei denn, er enthält keinen geeigneten Code) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_Base_identifier_type|1.7.0#KSN)
```







<a id="WeiterbehandelnderArzt">WeiterbehandelnderArzt</a>

| Art           | Bezeichnung                               | Bemerkung |
| ------------- | ----------------------------------------- | --------- |
| Beispieldatei | DGUV_Basis_Bsp_WeiterbehandelnderArzt.xml |           |
| Profil        | DGUV_Basis_PR_WeiterbehandelnderArzt.xml  |           |
| Code Set(s)   |                                           |           |
| Value Set(s)  |                                           |           |
| Validiert am: |                                           |           |

**Validierung 22.09.2025:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_WeiterbehandelnderArzt.xml 05:17:28
[2, 47] PractitionerRole: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[21, 16] PractitionerRole.specialty[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE' version '1.03' could not be found, so the code cannot be validated. Valid versions: []
[21, 16] PractitionerRole.specialty[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Practice Setting Code Value Set' (http://hl7.org/fhir/ValueSet/c80-practice-codes|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE#57)
[22, 17] PractitionerRole.specialty[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/PractitionerRole/DGUV-Basis-PR-WeiterbehandelnderArzt|1.3 überein.
```



**Validierung 24.09.2025:**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-BASE\DGUV_Basis_Bsp_WeiterbehandelnderArzt.xml 02:46:50
[2, 47] PractitionerRole: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[21, 16] PractitionerRole.specialty[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE' version '1.03' could not be found, so the code cannot be validated. Valid versions: []
[21, 16] PractitionerRole.specialty[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Practice Setting Code Value Set' (http://hl7.org/fhir/ValueSet/c80-practice-codes|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE#57)
[22, 17] PractitionerRole.specialty[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/Basis/PractitionerRole/DGUV-Basis-PR-WeiterbehandelnderArzt|1.3 überein.
```

