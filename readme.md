[![hackmd-github-sync-badge](https://hackmd.io/re_vKvaTQnq7NhaQ-9sxQQ/badge)](https://hackmd.io/re_vKvaTQnq7NhaQ-9sxQQ)
**#Protocol RR **





* Motivación - No se presenta en la literatura una definición de consenso respecto de que se entiende por calidad de código.
Objetivo :  Lograr una definición de QC y sus principales características / dimensiones a partir de una RR.

_PI : ¿Qué se entiende por Calidad de Código?

_PI: ¿Qué técnicas, métodos, prácticas, estándares y herramientas se utilizan en la industria para controlar la calidad del código?

_PI; ¿Qué atributos de Q de código se prenentan en los artículos seleccionados?

Def. QC:   * {max min (ATRIB_Q Interna/Externa) (Costos)}
            sa restricciones contexto* 
> [TOC]

---


`*PI:¿Qué se entiende actualmente por  Calidad de Código? *`
Keywords: Code Quality AND Software


---
` TITLE-ABS-KEY ( "code quality"  AND  software )  AND  ( LIMIT-TO ( PUBYEAR ,  2021 )  OR  LIMIT-TO ( PUBYEAR ,  2020 ) )` 

---


Fuente: Scopus
Fecha : 14-Nov-2020
Search String: "code quality" AND software

Proceso de obtención: Exportación del archivo a Mendeley para poder catalogar y exportación del archivo .bib de la selección(para poder mas adelante utilizar)

Unidad de análisis- definición de Calidad Código (atributos)

1. Copiar Template ... y completar
#Template 

# Template Paper ID (Titulo): 

-  BIB (Referencia tex de Scholar): 
 ```
NULL
```
-   DEF_CQ_ABSTRACT 
```
NULL
```
-  DEF_CQ_PAPER 
```
NULL
```
-  CQ_ARQ_ATRIB
```
NULL
```
- CQ_PRAC/TECN
```
NULL
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP
`NULL`
- CQ_TOOL
`NULL`

- CQ_CITE_@ref: 
```
NULL
```

- Author / TimeStamp Start/ End
> [name= ]
> START_[time=]
> END_ [time=]



---

```
Cada paper se imprimió y establece el etiquetado (algo parecido a lo realizadao en paper anterior y posteriormente search en mendeley para poder replicar)

relevancia de versionado de esta herramienta y subir al repo GitHub
```





# Paper 1 (Ale): 


-  BIB (Referencia tex de Scholar): 
 ```
   @article{lenarduzzi2019does,
  title={Does Code Quality Affect Pull Request Acceptance? An empirical study},
  author={Lenarduzzi, Valentina and Nikkola, Vili and Saarim{\"a}ki, Nyyti and Taibi, Davide},
  journal={arXiv preprint arXiv:1908.09321},
  year={2019}
}
```
-   DEF_CQ_ABSTRACT 
```
NULL
```

-  DEF_CQ_PAPER 
```
"...code quality issues such as code smells, antipatterns, and coding style violations in the pull request code.." 
```
` ..we aim at understanding whether code quality issues such as code smells, antipatterns, and coding style violations in the pull request code affect the chance of its acceptance when reviewed by a maintainer of the project...` , `..."Quality was revealed as one of the top priorities for developers..."`, `..."We measured code quality against a set of rules pro- vided by PMD, one of the most frequently used open-source software tools for analyzing source code"`

-  CQ_ATRIB
```
mantenibilidad,tolerancia a fallas,defectos,
estilo de codificación, diseño, error prone, documentation,performance,
seguridad
```
- CQ_PRAC/TECN
```
Code Review, Pull Requests, Technical Debt, Static Code Analisis`
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP

- CQ_TOOLS
`Checkstyle, Findbugs, SonarQube`


- CQ_OTROS: 
` Code Smells, anti patterns, code Style, clean code, git , gitHub`



-  COMMENTS : - `Case Study dentro del contexto de ESE (Empirical Software Eng.)` `menciona a GIT como tecnología y GITHub como repo central` y `PI asociada al tema RQ2. Does code quality affect pull request acceptance?... 'Pull request are a verypoerfull instrument', Aporte de este paper: Code qualite does not seem to be a keydriver for the acceptance of PR`

- CQ_APPROACH: High
---

- CQ_CITE_@ref: 
```
NULL
```

- Author / TimeStamp Start/ End
> [name=Alejandro Adorjan]
> START_[time=Sun, Nov 8, 2020 3:55 PM]
> END_ [time=Sun, Nov 8, 2020 4:15 PM]



---





| Key| Descripción| Comentarios/Nota|
| -------- | -------- | -------- |
| DEF_CQ_ABSTRACT     | En el abstract del artículo se menciona directamente o indirectamente al concepto de Calidad de Código (CQ)(Copiar Literal la Mención (CLM)) . NULL en caso de no presentar   |     |
|DEF_CQ_PAPER | En el desarrollo del artículo se presenta una definición directa al concepto de calidad de código . NULL en caso de no presentar| La presencia de NULL indicaría la exclusión de la revisión en el árticulo
|CQ_ATRIB | En el artículo se mencionanatributos de calidad de código que directa o indirectamente  (Como por ejemplo  mantenibilidad, escalabilidad, disponibilidad, etc). Mencionar y enumerar cuales son los atributos mencionados.|
|CQ_PRAC/TECN | En el artículo se presentan prácticas o técnicas asociadas a aspectos de CQ (Como por ejemplo PR(Pull Request), Code Review (CR), etc )|
|CQ_METH/PROC/STD|En el artículo se presentan métodos, prácticas o estándares que ayudan a obtener CQ| |
|CQ_PEOP | En el artículo se presentan aspectos de calidad de código en relación a equipos y personas |
|CQ_TOOL | En el artículo se mencionan herramientas asociadas a la calidad de Código( analisadores estáticos, linterns específicos,etc)|
|CQ_OTROS | En el artículo se presentan otras referencias a conceptos asociados a CQ que no necesariamente estan dentro de la clasificación de CQ_* |
|CQ_CITE_@ref| El paper menciona una cita a otro artículo que hace referencia a conceptos y en particular la definición de CQ. @REF el es el bibtex de dicho artículo| 
|COMMENTS | Comentarios en relación al artículo||
|CQ_APPROACH| Low : el paper menciona superficalmente los conceptos de QC , High: el paper trata no superficialmente los aspectos de CQ||
- Author / TimeStamp Start/ End
> [name= nombre del autor]
> TimeStamp ( la untización de versionado permite ver el tiempo)
> START_[time=Sat, Nov 21, 2020 19:15PM]
> END_ [time=Sat, Nov 21, 2020 19:50 PM]


---


# Paper 1 DIEGO : 

-  BIB (Referencia tex de Scholar): 
 ```
   @article{lenarduzzi2019does,
  title={Does Code Quality Affect Pull Request Acceptance? An empirical study},
  author={Lenarduzzi, Valentina and Nikkola, Vili and Saarim{\"a}ki, Nyyti and Taibi, Davide},
  journal={arXiv preprint arXiv:1908.09321},
  year={2019}
}
```
-   DEF_CQ_ABSTRACT 
```
Define por la negativa ya que menciona 'cosas' de mala QC
"[code] quality flaws such as code smells, anti-patterns, security
vulnerabilities, and coding style violations"

```
-  DEF_CQ_PAPER 
```
En lo siguiente hay una expresión que podría entenderse también como una definición de code quality a alto nivel.
"Previous work confirmed that the presence of PMD issues in the code [some code quality issues], including the code smells and anti-patterns collected
by PMD, significantly increases the risk of faults and maintenance effort."

Code quality relacionado a technical debt
"PMD is an open-source tool that aims to identify issues that can lead to technical debt accumulating during development."
```
-  CQ_ATRIB
```
- Software maintainability
- Low fault-proneness
"Therefore, we expect that developers take care of these issues, in order to increase software maintainability and decrease fault-proneness."
```
- CQ_PRAC/TECN
```
NULL
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP
`NULL`
- CQ_TOOL
Herramienta PMD para encontrar code quality flaws.
PMD -> Herramienta de análisis estático (por si luego usamos clasificaciones de algún tipo).
"We analyzed the quality flaws [...] using PMD, one of the most frequently used static analysis tools"

- CQ_OTROS: 
`NULL`

---


-  Comentarios : - 

---

- CQ_CITE_@ref: 
```
"However, the respondents specified quality differently from their pespective perception, as conformance, good available documentation, and contributor reputation." , Gousios et al. (2015) https://ieeexplore.ieee.org/document/7194588

Esto puede servir para introducción como motivación o como trabajos previos.
"Moreover, they report that developers generally associate the quality of a pull request with the quality of its description, complexity, and revertability." . Kononenko et al. (2018)
https://dl.acm.org/doi/10.1145/3183519.3183542
```

- Author / TimeStamp Start/ End
> [name= Diego]
> START_[time=11:52]
> END_ [time=14:53]
> PAUSA_ [2 HORAS 9 MINUTOS]
> TIME ON TASK_ [52 MINUTOS]


# Paper 1 MARTÍN: 

-  BIB (Referencia tex de Scholar): 
 ```
   @article{lenarduzzi2019does,
  title={Does Code Quality Affect Pull Request Acceptance? An empirical study},
  author={Lenarduzzi, Valentina and Nikkola, Vili and Saarim{\"a}ki, Nyyti and Taibi, Davide},
  journal={arXiv preprint arXiv:1908.09321},
  year={2019}
}
```
-   DEF_CQ_ABSTRACT 
```
quality flaws such as code smells, anti-patterns, security
vulnerabilities, and coding style violations in a pull request’s code affect the chance of its acceptance
when reviewed by a maintainer
```
-  DEF_CQ_PAPER 
```
We considered the quality flaws highlighted by PMD rules (code smells, anti-patterns, and coding style violations),


```
-  CQ_ARQ_ATRIB
```
NULL
```
- CQ_PRAC/TECN
```
NULL
```
- CQ_METH/PROC/STD
```
pull request
review
static analysis
code smells
coding style
technical debt
code coverage 
```
- CQ_PEOP
`NULL`
- CQ_TOOL
`PMD
Checkstyle
FindBugs
SonarQube`
- CQ_OTROS: 
`implementation of new features seem to be more important acceptance factors than any other aspects, including quality (Gousios et al., 2015; Calefato et al., 2017)

Considering the code style as an influencing factor for inte- grating pull requests, several code style criteria have generally revealed high divergence while several other criteria always in- dicated consistency. However, code style inconsistency between pull requests and the code would affect the process of merging them into the code (Yu et al., 2015).

Integrators decide to accept a contribution after analyzing source code quality, code style, documentation, granularity, and adherence to project conventions (Gousios et al., 2014). 


In another work, Gousios et al. (2015) conducted a survey aimed at characterizing the key factors considered in the decision- making process of pull request acceptance. Quality was revealed as one of the top priorities for developers. The most important ac- ceptance factors they identified are targeted area importance, test cases, and code quality. However, the respondents specified qual- ity differently from their respective perception, as conformance, good available documentation, and contributor reputation.

Kononenko et al. (2018) investigated the pull request accep- tance process. Developers’ experience and affiliation were significant factors in both models. Moreover, they report that developers generally associate the quality of a pull request with the quality of its description, complexity, and revertability. 

`


---


-  Comentarios : - 

Menciones a tests (unit, integration). No se profundiza en niveles o automatización.

Mención a CI, herramientas como TravisCI, CloudBees.


Reflexión: Regarding the factors considered to measure their quality, they are based on the developers’ perception.

Discusión: the adoption of pull request quality analysis tools such as SonarQube or the usage of PMD before submitting a pull request will increase the quality of their code; increasing the overall software maintainability and decreasing the fault proneness that could be increased from the injection of some PMD issues.

The results complement those obtained by Soares et al. (2015a) and Calefato et al. (2017), namely, that the reputation of the developer might be more important than the quality of the developed code. 

Reflexión: We are aware that code quality is a broad and general term and that other aspects such as the test coverage of pull requests or the number of bugs generated by the code in pull requests could bring different results.


---

- CQ_CITE_@ref: 
```
NULL
```

- Author / TimeStamp Start/ End
> [name= Martín]
> START_[time=9:10]
> END_ [time=9:40]

**Resumen RR: **

| Atributos| Prácticas| Herramientas|
| -------- | -------- | -------- |
| Text     | Text     | Text     |

> Definiciones: 
1. 
2.

```
Terms and conditions Privacy policy
```
```
Documents
Export Date: 15 Nov 2020
```
1) Lenarduzzi, V., Nikkola, V., Saarimäki, N., Taibi, D.

# 1. Does code quality affect pull request acceptance? An empirical study

```
(2021) Journal of Systems and Software, 171, art. no. 110806,.
```
1) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85090024069&doi=10.1016%2fj.jss.2020.110806&partnerID=40&md5=3fc8497ac55b764c00a741b82889bf
DOI: 10.1016/j.jss.2020.

```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
2) Gupta, A., Suri, B., Wadhwa, B.

# 2. A detection tool for code bad smells in java source code

```
(2021) Advances in Intelligent Systems and Computing, 1086, pp. 479-488.
```
2) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85087533951&doi=10.1007%2f978-981-15-1275-9_39&partnerID=40&md5=d53908b10d8bf19f5b7a641910eae2c
DOI: 10.1007/978-981-15-1275-9_

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
3) Tahmooresi, H., Heydarnoori, A., Nadri, R.

# 3. Studying the Relationship Between the Usage of APIs Discussed in the Crowd and Post-Release

# Defects

```
(2020) Journal of Systems and Software, 170, art. no. 110724,.
```
3) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85088222392&doi=10.1016%2fj.jss.2020.110724&partnerID=40&md5=b088ab72295646040f6f852bfc25fe
DOI: 10.1016/j.jss.2020.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
4) Meldrum, S., Licorish, S.A., Owen, C.A., Savarimuthu, B.T.R.

# 4. Understanding stack overflow code quality: A recommendation of caution

```
(2020) Science of Computer Programming, 199, art. no. 102516,.
```
4) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85088230996&doi=10.1016%2fj.scico.2020.102516&partnerID=40&md5=92ea781a022ae4b8f4bab84597642a


```
Terms and conditions Privacy policy
```
```
DOI: 10.1016/j.scico.2020.
```
```
Document Type: Article
Publication Stage: Final
Source: Scopus
```


# 5. Does migrating a monolithic system to microservices decrease the technical debt?
- [x] 5) Lenarduzzi, V., Lomio, F., Saarimäki, N., Taibi, D.


https://www.scopus.com/inward/record.uri?eid=2-s2.0-85087383887&doi=10.1016%2fj.jss.2020.110710&partnerID=40&md5=eecb57d0a427b954cb57b950789b
DOI: 10.1016/j.jss.2020.

```
Document Type: Review
Publication Stage: Final
Source: Scopus
```
```
(2020) Journal of Systems and Software, 169, art. no. 110710,. Cited 1 time.
```
-  BIB (Referencia tex de Scholar): 
 ```
@article{lenarduzzi2020does,
  title={Does migrating a monolithic system to microservices decrease the technical debt?},
  author={Lenarduzzi, Valentina and Lomio, Francesco and Saarim{\"a}ki, Nyyti and Taibi, Davide},
  journal={Journal of Systems and Software},
  pages={110710},
  year={2020},
  publisher={Elsevier}
}
```
-   DEF_CQ_ABSTRACT 
```
NULL
```
-  DEF_CQ_PAPER 
```
NULL
```
-  CQ_ARQ_ATRIB
```
software maintenance, reliability, maintainability, security, performance, security, transferability, changeability, decreasing delivery time, scalability , funcionability, usability , portability
```
- CQ_PRAC/TECN
```
NULL
```
- CQ_METH/PROC/STD
```
SQUALE method, ISO-9126, ISO/IEC 25010, Focus Group
```
- CQ_PEOP
`Teams`
- CQ_TOOL
`static analysis tools and architectural analisis tools, SonarQube, CAST, Coverity Scan, SQUORE, Designite`
- CQ_OTROS: 
`code smells, anti-patters, model-view-controller, issues, microservice architecture, development process, deploying operating and upgrading, refactoring, techinical debt, bad smells, unit testing, architectural decisions, integration tests, bad smels, architectural smells`
- CQ_APPROACH: `High`
- Comments:
`"SonarQube calculates TD(Technical Debt) using SQAL \cite{mordal2009squale} (an ISO 9126 method) based on 5 categories \curtis2012estimating : robustness, performance, security, transferability and changeability"`
`We analyzed the TD provided by SonarQube considering the following types of ID issues "SonarQube" Technical Debt, also called "Mantenability Remediation Effort (issues classified by SonarQube as "Code Smells".. Reliability Remediation Effort ( issues classified as "Bugs") .. Security Remediation Effort (issues classified as "Security Vulnerabilities"))

ISO/IEC 25010 quality caracteristics (funcionability, performance/efficiency, compatibility, usability, reliability, security, mainteninability, and portability)"

`Muy interesante el Apéndice (anexo) donde se establecen los pasos en tres principales categorias , protocolo de estudio y subestudios, procedimientos , estudio de datos, extraccion y seleccoin de participantes y selecocin de focus group y especificación de ópreguntas de instrumento de investigación. `
`

- CQ_CITE_@ref: 
`@inproceedings{mordal2009squale,
  title={The squale model—A practice-based industrial quality model},
  author={Mordal-Manet, Karine and Balmas, Fran{\c{c}}oise and Denier, Simon and Ducasse, St{\'e}phane and Wertz, Harald and Laval, Jannik and Bellingard, Fabrice and Vaillergues, Philippe},
  booktitle={2009 IEEE International Conference on Software Maintenance},
  pages={531--534},
  year={2009},
  organization={IEEE}
}
@article{curtis2012estimating,
  title={Estimating the principal of an application's technical debt},
  author={Curtis, Bill and Sappidi, Jay and Szynkarski, Alexandra},
  journal={IEEE software},
  volume={29},
  number={6},
  pages={34--42},
  year={2012},
  publisher={IEEE}
}
`

- Author / TimeStamp Start/ End
> [name=Alejandro Adorjan]
> START_[time=Sat, Nov 21, 2020 19:15PM]
> END_ [time=Sat, Nov 21, 2020 19:50 PM]







# 6. A comparison of quality flaws and technical debt in model transformation specifications

---
6) Kolahdouz-Rahimi, S., Lano, K., Sharbaf, M., Karimi, M., Alfraihi, H.
```
(2020) Journal of Systems and Software, 169, art. no. 110684,. Cited 1 time.
```
6) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85086381665&doi=10.1016%2fj.jss.2020.110684&partnerID=40&md5=992a7eee002a59b3a9df05cff256dfc
DOI: 10.1016/j.jss.2020.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
7) Antinyan, V.

# 7. Evaluating Essential and Accidental Code Complexity Triggers by Practitioners Perception

```
(2020) IEEE Software, 37 (6), art. no. 9007382, pp. 86-93.
```
7) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85079885944&doi=10.1109%2fMS.2020.2976072&partnerID=40&md5=a55f259875dbb3ba0ed69ab3b3a867c
DOI: 10.1109/MS.2020.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
8) Pavlič, L., Heričko, M., Beranič, T.

# 8. An expert judgment in source code quality research domain—a comparative study between

# professionals and students

```
(2020) Applied Sciences (Switzerland), 10 (20), art. no. 7088, pp. 1-13.
```
8)


```
Terms and conditions Privacy policy
```
```
https://www.scopus.com/inward/record.uri?eid=2-s2.0-85092773160&doi=10.3390%2fapp10207088&partnerID=40&md5=29c1500b33c19c8661ccf8237ac
DOI: 10.3390/app
```
```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
9) Bakhtiary, V., Gandomani, T.J., Salajegheh, A.

# The effectiveness of test-driven development approach on software projects: A multi-case study

```
(2020) Bulletin of Electrical Engineering and Informatics, 9 (5), pp. 2030-2037.
```
9) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85087115249&doi=10.11591%2feei.v9i5.2533&partnerID=40&md5=de83e4d1e7af2541e86ecf0a4da0dbf
DOI: 10.11591/eei.v9i5.

```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```


# 10. Simplifying the Search of npm Packages

- [x] 10) Abdellatif, A., Zeng, Y., Elshafei, M., Shihab, E., Shang, W.
```
(2020) Information and Software Technology, 126, art. no. 106365,.
```
10) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85086498455&doi=10.1016%2fj.infsof.2020.106365&partnerID=40&md5=864fa3f8ab767860f09e162a9420a10f
DOI: 10.1016/j.infsof.2020.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```

-  BIB (Referencia tex de Scholar): 
 ```
@article{abdellatif2020simplifying,
  title={Simplifying the Search of npm Packages},
  author={Abdellatif, Ahmad and Zeng, Yi and Elshafei, Mohamed and Shihab, Emad and Shang, Weiyi},
  journal={Information and Software Technology},
  pages={106365},
  year={2020},
  publisher={Elsevier}
}
```
-   DEF_CQ_ABSTRACT 
```
NULL
```
-  DEF_CQ_PAPER 
```
NULL
```
-  CQ_ARQ_ATRIB
```
quality, popularity, maintenance
```
- CQ_PRAC/TECN
```
NULL
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP
`Developer community`
- CQ_TOOL
`Stack Overflow, GitHub, RabbitMQ (module mantains all npm packages, ElasticSeach, linterns, VM on AWS (Virtual Machines on Amazon Web Services)`
- CQ_OTROS: 
`Javascript, Node Package Manager (npm), package Metrics, API, test, coverag`, `Source code and comments `
- CQ_APPROACH: 
- `Low`
- COMMENTS:
`Npms ranks are grouped in three main categories : quality, popularity and maintenance`, `The main goil of this paper is to reduce the complexity and imporve the efficiency of the current npms implementation while preserving its results`

- Author / TimeStamp Start/ End
> [name= Ale]
> START_[time=22:10]
> END_ [time=22:25]
11) Pecorelli, F., Di Lillo, G., Palomba, F., De Lucia, A.

# 11. VITRuM: A Plug-In for the Visualization of Test-Related Metrics

```
(2020) ACM International Conference Proceeding Series,.
```
11) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093078975&doi=10.1145%2f3399715.3399954&partnerID=40&md5=7a5377cd2a60558090615e1a30b8c7e
DOI: 10.1145/3399715.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
12) Riesch, M., Haider, M., Jirauschek, C.

# 12. Project Skeletons for Scientific Software


```
Terms and conditions Privacy policy
```
```
(2020) Proceedings of the International Conference on Numerical Simulation of Optoelectronic
Devices, NUSOD, 2020-September, art. no. 9217756, pp. 111-112.
```
12) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093973619&doi=10.1109%2fNUSOD49422.2020.9217756&partnerID=40&md5=f4fe26fdd9c9bbfa4b27b7e15dcdd3e
DOI: 10.1109/NUSOD49422.2020.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
13) Sharma, T., Singh, P., Spinellis, D.

# 13. An empirical investigation on the relationship between design and architecture smells

```
(2020) Empirical Software Engineering, 25 (5), pp. 4020-4068.
```
13) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85089908139&doi=10.1007%2fs10664-020-09847-2&partnerID=40&md5=0f29b8351d518306bf042abd9f0efba
DOI: 10.1007/s10664-020-09847-

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
14) Roy, D., Fakhoury, S., Lee, J., Arnaoudova, V.

# 14. A model to detect readability improvements in incremental changes

```
(2020) IEEE International Conference on Program Comprehension, pp. 25-36.
```
14) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85091927614&doi=10.1145%2f3387904.3389255&partnerID=40&md5=a1199e0245a5874289d28aabe5ba77ad
DOI: 10.1145/3387904.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```

# 15. A Developer Recommendation Method Based on Code Quality

- [x] 15) Da Silva, M.C., Cizotto, A.A.J., Paraiso, E.C.


```
(2020) Proceedings of the International Joint Conference on Neural Networks, art. no. 9207116,.
```
15) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093863935&doi=10.1109%2fIJCNN48605.2020.9207116&partnerID=40&md5=d8cb72b323a210385175eb
DOI: 10.1109/IJCNN48605.2020.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```

-  BIB (Referencia tex de Scholar): 
 ```
NULL
```
-   DEF_CQ_ABSTRACT 
```
NULL
```
-  DEF_CQ_PAPER 
```
NULL
```
-  CQ_ARQ_ATRIB
```
maintenance, complexity, maintainability, testability
```
- CQ_PRAC/TECN
```
quality assurance,
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP
`Collaborative development, development teams, experience of developers, collaborative environment, collaborative development environment`
- CQ_TOOL
`Software Management Tool, GitHub, CK (tool to classify the code qaulity metrics proposed by @chidamber1991towards)`
- CQ_OTROS: 
`code quality metrics, repositories mining, NPL (Natural Language Processing), Information Retrieval (IR), Machine Learning(ML) , Techniques, VCS Version Control Systems, bugs, NLP techniques, issues, request, code repository mining, code quality metrics, bad quality metrics, code quality metrics commits`
- CQ_APPROACH: 
- `Low`
- COMMENTS:
..`When taking into account only the level of experience of developers as a factor for the recomentation process, code quality is put as rish, as the impact code changes may have is not accessed`..
```
The quality of the code produced by a developer does not relate to the type of activity,and the latter condiders than the expertise of a developer is unrelated to the quality of code produced.
```
```
interesante life cicle de change request y valores de resolucion FIXED,INVALID, WONTFIX,DUPLICATE,WORKSFORME.
```
```
..."developers are ordered according to their impact on code quality"
```
```
There's statistically difference between both methods concerning the recommending of developers with a better impact to a repository's code quality 
```
```
El paper propone un modelo de desarrollo dinámico desde la composicion representación, adquisición aprendizaje y mantenimeitno. Presentando un conjunto de métricas dirijidas a la codificación
```
- CQ_CITE_@ref: 
```
@inproceedings{chidamber1991towards,
  title={Towards a metrics suite for object oriented design},
  author={Chidamber, Shyam R and Kemerer, Chris F},
  booktitle={Conference proceedings on Object-oriented programming systems, languages, and applications},
  pages={197--211},
  year={1991}
}
```
---
> [name= Ale]
> START_[time=Tue, Nov 24, 2020 21:35:15PM]
> END_ [time=Tue, Nov 24, 2020 22:07 PM]
> 
16) Block, M., Barcaskey, B., Nimmo, A., Alnaeli, S., Gilbert, I., Altahat, Z.


```
Terms and conditions Privacy policy
```
# 16. Scalable Cloud-Based Tool to Empirically Detect Vulnerable Code Patterns in Large-Scale System

```
(2020) IEEE International Conference on Electro Information Technology, 2020-July, art. no.
9208325, pp. 588-592.
```
16) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85092528407&doi=10.1109%2fEIT48999.2020.9208325&partnerID=40&md5=a186eb9a5d87a34cafeb9676e
DOI: 10.1109/EIT48999.2020.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
17) Vlaovic, J., Vidakovic, M., Kovacevic, M., Kovacevic, B., Lukic, N.

# 17. Developing Consumer Electronics Software Using A-SPICE: Infotainment Development Experience

```
(2020) IEEE Consumer Electronics Magazine, 9 (4), art. no. 9109410, pp. 104-110.
```
17) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85086474781&doi=10.1109%2fMCE.2020.2978212&partnerID=40&md5=f7536f8909710494e49b0ebe0158c90c
DOI: 10.1109/MCE.2020.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
18) Nakamaru, T., Matsunaga, T., Yamazaki, T., Akiyama, S., Chiba, S.

# 18. An Empirical Study of Method Chaining in Java

```
(2020) Proceedings - 2020 IEEE/ACM 17th International Conference on Mining Software
Repositories, MSR 2020, pp. 93-102.
```
18) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093701309&doi=10.1145%2f3379597.3387441&partnerID=40&md5=ad68d2aa596599fb51cbb348bf0f568a
DOI: 10.1145/3379597.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
19) Dey, T., Mousavi, S., Ponce, E., Fry, T., Vasilescu, B., Filippova, A., Mockus, A.

# 19. Detecting and Characterizing Bots that Commit Code

```
(2020) Proceedings - 2020 IEEE/ACM 17th International Conference on Mining Software
Repositories, MSR 2020, pp. 209-219.
```
19) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093690882&doi=10.1145%2f3379597.3387478&partnerID=40&md5=93ad989e3c48c39afe290dbc84bfa
DOI: 10.1145/3379597.

```
Document Type: Conference Paper
```

```
Terms and conditions Privacy policy
```
```
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
20) Jebnoun, H., Braiek, H.B., Rahman, M.M., Khomh, F.

# 20. The Scent of Deep Learning Code: An Empirical Study

```
(2020) Proceedings - 2020 IEEE/ACM 17th International Conference on Mining Software
Repositories, MSR 2020, pp. 420-430.
```
20) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093683910&doi=10.1145%2f3379597.3387479&partnerID=40&md5=ecc5dad25efffa1c2608f7fc4d7b1a
DOI: 10.1145/3379597.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
-  BIB (Referencia tex de Scholar): 
 ```
@inproceedings{jebnoun2020scent,
  title={The Scent of Deep Learning Code: An Empirical Study},
  author={Jebnoun, Hadhemi and Ben Braiek, Houssem and Rahman, Mohammad Masudur and Khomh, Foutse},
  booktitle={Proceedings of the 17th International Conference on Mining Software Repositories},
  pages={420--430},
  year={2020}
}
```
-   DEF_CQ_ABSTRACT 
```
NULL
```
-  DEF_CQ_PAPER 
```
NULL
```
-  CQ_ARQ_ATRIB
```
maintenance, performance, quality of deep learning code, code smells, 
```
- CQ_PRAC/TECN
```
training algorithms, machine learning algorithms, bugfixing, refactoring
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP
`NULL`
- CQ_TOOL
`TensorFlow , Pythorch, GitHub, Github Search API, PySmell`
- CQ_APPROACH: 
- `Low`
- CQ_OTROS:
```
Deep Learning (DL) es a type of machine learning that uses artificial neural network with multiple hidden layers" .. code smels .. "Poor coding practices and quick solutions often result in low quality code containen various code smells. The presence of code smells within the software systems might incidentally degrade their quality and performance" ..These smells do not prevent the program from working, however they are a violation of the best practices that may increse the risk of software bugs or failures in the future.
```
- CQ_CITE_@ref: 
```
NULL
```
- CQ_Comments
```
10 selected code smels:
Long Method (LM), Long Scope Chaining, ... Long...SLOC (Source Line of Code)
```

- Author / TimeStamp Start/ End
> [name= Ale]
> START_[time= 27 Nov 2020, 8:00]
> END_ [time=]
21) Walden, J.

# 21. The Impact of a Major Security Event on an Open Source Project: The Case of OpenSSL

```
(2020) Proceedings - 2020 IEEE/ACM 17th International Conference on Mining Software
Repositories, MSR 2020, pp. 409-419.
```
21) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093676836&doi=10.1145%2f3379597.3387465&partnerID=40&md5=13791106a43d1252730a69cbeaac723c
DOI: 10.1145/3379597.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
22) Gilson, F., Morales-Trujillo, M., Mathews, M.

# 22. How junior developers deal with their technical debt?

```
(2020) Proceedings - 2020 IEEE/ACM International Conference on Technical Debt, TechDebt 2020,
pp. 51-61.
```
22) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093085706&doi=10.1145%2f3387906.3388624&partnerID=40&md5=63079a2815fc72749c121a
DOI: 10.1145/3387906.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```

```
Terms and conditions Privacy policy
```
23) Wu, Y.

# 23 ~~N/A Exploring the relationship between dockerfile quality and project characteristics~~

```
(2020) Proceedings - International Conference on Software Engineering, art. no. 3382169, pp.
128-130.
```
23) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85094103765&doi=10.1145%2f3377812.3382169&partnerID=40&md5=5ff44256e6c8aa9f9d7d1451e
DOI: 10.1145/3377812.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
24) Bai, G.R.

# 24 ~~N/A. Improving students' testing practices~~

```
(2020) Proceedings - International Conference on Software Engineering, art. no. 3381401, pp.
218-221.
```
24) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85094102796&doi=10.1145%2f3377812.3381401&partnerID=40&md5=836e38c3fd8f56a3199dddef555d715e
DOI: 10.1145/3377812.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
25) Kurbatova, Z., Veselov, I., Golubev, Y., Bryksin, T.

# 25. Recommendation of Move Method Refactoring Using Path-Based Representation of Code

```
(2020) Proceedings - 2020 IEEE/ACM 42nd International Conference on Software Engineering
Workshops, ICSEW 2020, pp. 315-322.
```
25) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093099001&doi=10.1145%2f3387940.3392191&partnerID=40&md5=96c8e0baceacad9ad232dca088615aa
DOI: 10.1145/3387940.

-  BIB (Referencia tex de Scholar): 
 ```
NULL
```
-   DEF_CQ_ABSTRACT 
```
NULL
```
-  DEF_CQ_PAPER 
```
NULL
```
-  CQ_ARQ_ATRIB
```
NULL
```
- CQ_PRAC/TECN
```
Heuristic based approaches, machine learning-based approaches, refactoring, machine learning algorithms.
```
- CQ_METH/PROC/STD
```
NULL
```
- CQ_PEOP
`NULL`
- CQ_TOOL
`JDeodorant, JMove`
- CQ_OTROS: 
`code smell ..."mell relates to situation when a method is more interested in the content or behaviour of another class than in its original class.. refactoring tends to make software eaier to understand and mantein.. manually checking the source code to identify refactoring oportunities is a tiresome and time consuming process"`

- CQ_APPROACH: Low
- COMMENTS:

---
```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
26) De Stefano, M., Pecorelli, F., Tamburri, D.A., Palomba, F., De Lucia, A.

# 26. Splicing Community Patterns and Smells: A Preliminary Study

```
(2020) Proceedings - 2020 IEEE/ACM 42nd International Conference on Software Engineering
Workshops, ICSEW 2020, pp. 703-710.
```
26)


```
Terms and conditions Privacy policy
```
```
https://www.scopus.com/inward/record.uri?eid=2-s2.0-85093092679&doi=10.1145%2f3387940.3392204&partnerID=40&md5=f38a32ff52f2fe004701d8333a16d30f
DOI: 10.1145/3387940.
```
```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
27) Dominic, J., Ritter, C., Rodeghero, P.

# 27 ~~N/A Onboarding bot for newcomers to software engineering~~

```
(2020) Proceedings - 2020 IEEE/ACM International Conference on Software and System Processes,
ICSSP 2020, pp. 91-94.
```
27) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85092462077&doi=10.1145%2f3379177.3388901&partnerID=40&md5=fb01f796df697aff2812072de812a6cc
DOI: 10.1145/3379177.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
28) Jiang, L., Rewcastle, R., Denny, P., Tempero, E.

# 28 ~~N/A CompareCFG: Providing Visual Feedback on Code Quality Using Control Flow Graphs~~

```
(2020) Annual Conference on Innovation and Technology in Computer Science Education, ITiCSE,
pp. 493-499.
```
28) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85086447326&doi=10.1145%2f3341525.3387362&partnerID=40&md5=26c71cc563382f499d60ae03ad6f
DOI: 10.1145/3341525.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
29) Uddin, G., Khomh, F., Roy, C.K.

# 29. Mining API usage scenarios from stack overflow

```
(2020) Information and Software Technology, 122, art. no. 106277,.
```
29) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85079356173&doi=10.1016%2fj.infsof.2020.106277&partnerID=40&md5=e3c2ddc19102034140596302b0edf
DOI: 10.1016/j.infsof.2020.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```

```
Terms and conditions Privacy policy
```
30) Salah, A., Truong, Q.-T., Lauw, H.W.

# 30. Cornac: A comparative framework for multimodal recommender systems

```
(2020) Journal of Machine Learning Research, 21,.
```
30) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85087331608&partnerID=40&md5=7d9794d9b4aaad36427cec5b0713db
Document Type: Article
Publication Stage: Final
Source: Scopus

31) Subramanian, K., Maas, J., Borchers, J.

# 31. TRACTUS: Understanding and Supporting Source Code Experimentation in Hypothesis-Driven Data

# Science

```
(2020) Conference on Human Factors in Computing Systems - Proceedings, art. no. 3376764,.
```
31) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85091316657&doi=10.1145%2f3313831.3376764&partnerID=40&md5=3b56a02bc4e938ef0907b73e6f63c
DOI: 10.1145/3313831.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
32) Akbar, M.A., Huang, Z., Yu, Z., Mehmood, F., Hussain, Y., Hamza, M.

# 32. Towards continues code recommendation and implementation system: An Initial Framework

```
(2020) ACM International Conference Proceeding Series, pp. 439-444.
```
32) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85090845801&doi=10.1145%2f3383219.3383282&partnerID=40&md5=ccb7c46c9d352017238f3a4c8bbce4a
DOI: 10.1145/3383219.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
33) Misra, V., Reddy, J.S.K., Chimalakonda, S.

# 33 N/A ~~Is there a correlation between code comments and issue ?: An exploratory study~~

```
(2020) Proceedings of the ACM Symposium on Applied Computing, pp. 110-117.
```
33) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85083040700&doi=10.1145%2f3341105.3374009&partnerID=40&md5=e6f39b375cfff0e7c2e0d7188ac2b0c
DOI: 10.1145/3341105.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
34) Righi, M., Andela, B., Eyring, V., Lauer, A., Predoi, V., Schlund, M., Vegas-Regidor, J., Bock, L.,


```
Terms and conditions Privacy policy
```
```
Brötz, B., De Mora, L., Diblen, F., Dreyer, L., Drost, N., Earnshaw, P., Hassler, B., Koldunov, N.,
Little, B., Loosveldt Tomas, S., Zimmermann, K.
```
# 34 Earth System Model Evaluation Tool (ESMValTool) v2.0-technical overview

```
(2020) Geoscientific Model Development, 13 (3), pp. 1179-1199. Cited 4 times.
```
34) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85082051518&doi=10.5194%2fgmd-13-1179-2020&partnerID=40&md5=e2eb4108e981201241792f951769a
DOI: 10.5194/gmd-13-1179-

```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Sour ce: Scopus
```
35) Ludwig, J., Cline, D., Novstrup, A.

# 35 A Case Study Using CBR-Insight to Visualize Source Code Quality

```
(2020) IEEE Aerospace Conference Proceedings, art. no. 9172526,.
```
35) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85092544818&doi=10.1109%2fAERO47225.2020.9172526&partnerID=40&md5=826ffaf5709d5015ed52d1927440f63c
DOI: 10.1109/AERO47225.2020.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
36) Panigrahi, R., Kuanar, S.K., Kumar, L.

# 36. Application of Naïve Bayes classifiers for refactoring Prediction at the method level

```
(2020) 2020 International Conference on Computer Science, Engineering and Applications, ICCSEA
2020, art. no. 9132849,.
```
36) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85089773794&doi=10.1109%2fICCSEA49143.2020.9132849&partnerID=40&md5=0b7061fefd3c1a7aacb4cfc641a82c
DOI: 10.1109/ICCSEA49143.2020.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
37) Rimawi, D., Zein, S.

# 37. A static analysis of android source code for design patterns usage

```
(2020) International Journal of Advanced Trends in Computer Science and Engineering, 9 (2), pp.
2178-2186.
```
37) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85085160223&doi=10.30534%2fijatcse%2f2020%2f194922020&partnerID=40&md5=a118ae4ecb768cabdb5d34034e0fb7d
DOI: 10.30534/ijatcse/2020/


```
Terms and conditions Privacy policy
```
```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
38) Vassallo, C., Panichella, S., Palomba, F., Proksch, S., Gall, H.C., Zaidman, A.

# 38. How developers engage with static analysis tools in different contexts

```
(2020) Empirical Software Engineering, 25 (2), pp. 1419-1457. Cited 1 time.
```
38) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85076207019&doi=10.1007%2fs10664-019-09750-5&partnerID=40&md5=93c776c9292559058c77371ea7856e
DOI: 10.1007/s10664-019-09750-

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
39) Badanahatti, A., Pillutla, S.

# 39. ~~N/A Interleaving Software Craftsmanship Practices in Medical Device Agile Development~~

```
(2020) ACM International Conference Proceeding Series, art. no. 3385047,.
```
39) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85082655082&doi=10.1145%2f3385032.3385047&partnerID=40&md5=55582268eed8ffa92a4580183d1e
DOI: 10.1145/3385032.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
40) Kirk, D., Crow, T., Luxton-Reilly, A., Tempero, E.

# 40 On assuring learning about code quality

```
(2020) ACE 2020 - Proceedings of the 22nd Australasian Computing Education Conference, Held in
conjunction with Australasian Computer Science Week, pp. 86-94. Cited 1 time.
```
40) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85079325424&doi=10.1145%2f3373165.3373175&partnerID=40&md5=2fc6682e22a439ec9ad3c348933b
DOI: 10.1145/3373165.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
41) Li, G., Liu, H., Jin, J., Umer, Q.

# 41. Deep Learning Based Identification of Suspicious Return Statements

```
(2020) SANER 2020 - Proceedings of the 2020 IEEE 27th International Conference on Software
Analysis, Evolution, and Reengineering, art. no. 9054826, pp. 480-491.
```
41)


```
Terms and conditions Privacy policy
```
```
https://www.scopus.com/inward/record.uri?eid=2-s2.0-85083556267&doi=10.1109%2fSANER48275.2020.9054826&partnerID=40&md5=c5a8f3f4b8a450c6d2aebf306b9ea
DOI: 10.1109/SANER48275.2020.
```
```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
42) Moe, M.M., Oo, K.K.

# 42. Consequences of Dependent and Independent Variables based on Acceptance Test Suite Metric Using Test Driven Development Approach

```
(2020) 2020 IEEE Conference on Computer Applications, ICCA 2020, art. no. 9022828,.
```
42) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85082392543&doi=10.1109%2fICCA49400.2020.9022828&partnerID=40&md5=b1e41d9390832deb953866abc0e971f
DOI: 10.1109/ICCA49400.2020.

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
43) Moe, M.M., Oo, K.K.

# 43. Comparative results of dependent and independent variables focused on regression analysis using test-driven development

```
(2020) WCSE 2020: 2020 10th International Workshop on Computer Science and Engineering, pp.
538-546.
```
43) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85092367223&doi=10.18178%2fwcse.2020.02.006&partnerID=40&md5=d35117127fd9c238931704040b
DOI: 10.18178/wcse.2020.02.

```
Document Type: Conference Paper
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
44) Papis, B.K., Grochowski, K., Subzda, K., Sijko, K.

# 44. Experimental evaluation of test-driven development with interns working on a real industrial project

```
(2020) IEEE Transactions on Software Engineering,.
```
44) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85091950145&doi=10.1109%2fTSE.2020.3027522&partnerID=40&md5=6a5f752c286c0fc38083b34efc2f213d
DOI: 10.1109/TSE.2020.

```
Document Type: Article
Publication Stage: Article in Press
Access Type: Open Access
Source: Scopus
```

```
Terms and conditions Privacy policy
```
45) Tsoupidi, R.M., Castañeda Lozano, R., Baudry, B.

# 45. Constraint-Based Software Diversification for Efficient Mitigation of Code-Reuse Attacks

```
(2020) Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence
and Lecture Notes in Bioinformatics), 12333 LNCS, pp. 791-808.
```
45) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85091315219&doi=10.1007%2f978-3-030-58475-7_46&partnerID=40&md5=849cf47259b0cb06a67fc18159fc8c
DOI: 10.1007/978-3-030-58475-7_

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
46) Di Sorbo, A., Grano, G., Aaron Visaggio, C., Panichella, S.

# 46. Investigating the criticality of user-reported issues through their relations with app rating

```
(2020) Journal of Software: Evolution and Process,.
```
46) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85090940323&doi=10.1002%2fsmr.2316&partnerID=40&md5=0bf4ff9f154b64585ae04f8c39bed39f
DOI: 10.1002/smr.

```
Document Type: Article
Publication Stage: Article in Press
Source: Scopus
```
47) Saranti, A., Taraghi, B., Ebner, M., Holzinger, A.

# 47. Property-Based Testing for Parameter Learning of Probabilistic Graphical Models

```
(2020) Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence
and Lecture Notes in Bioinformatics), 12279 LNCS, pp. 499-515.
```
47) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85090175338&doi=10.1007%2f978-3-030-57321-8_28&partnerID=40&md5=edaca321f6af97291078bc782e3f0bc
DOI: 10.1007/978-3-030-57321-8_

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
48) Nazir, S., Fatima, N., Chuprat, S.

# 48. Situational modern code review framework to support individual sustainability of software engineers

```
(2020) International Journal of Advanced Computer Science and Applications, 11 (6), pp. 366-375.
```
48) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85087819082&doi=10.14569%2fIJACSA.2020.0110648&partnerID=40&md5=274eb34b30264d21fc08efbde69fdf
DOI: 10.14569/IJACSA.2020.

```
Document Type: Article
Publication Stage: Final
```

```
Terms and conditions Privacy policy
```
```
Access Type: Open Access
Source: Scopus
```
49) Badreddin, O.

# 49. ~~ N/ADistributed software health and quality metrics with blockchains~~

```
(2020) CASCON 2019 Proceedings - Conference of the Centre for Advanced Studies on
Collaborative Research - Proceedings of the 29th Annual International Conference on Computer
Science and Software Engineering, pp. 365-366.
```
49) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85087409391&partnerID=40&md5=3482c35f0f69b1deda963fe7a88075c
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus

50) Spasić, M., Janičić, M.V.

# 50. Verification supported refactoring of embedded sql

```
(2020) Software Quality Journal,. Cited 1 time.
```
50) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85086670462&doi=10.1007%2fs11219-020-09517-y&partnerID=40&md5=70cea1163ed9864029ca29461e9a
DOI: 10.1007/s11219-020-09517-y

```
Document Type: Article
Publication Stage: Article in Press
Source: Scopus
```
51) Rakshith, M.N., Shivaprasad, N.

# ~~51. N/A Build Optimization Using Jenkins~~

```
(2020) Lecture Notes on Data Engineering and Communications Technologies, 38, pp. 401-409.
Cited 1 time.
```
51) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85083464260&doi=10.1007%2f978-3-030-34080-3_45&partnerID=40&md5=996f7581aab7e18911e7b1be4018fe
DOI: 10.1007/978-3-030-34080-3_

```
Document Type: Book Chapter
Publication Stage: Final
Source: Scopus
```
52) Masmali, O., Badreddin, O.

# ~~52. Towards a model-based fuzzy software quality metrics~~

```
(2020) MODELSWARD 2020 - Proceedings of the 8th International Conference on Model-Driven
Engineering and Software Development, pp. 136-148. Cited 1 time.
```
52)


```
Terms and conditions Privacy policy
```
```
https://www.scopus.com/inward/record.uri?eid=2-s2.0-85082984319&partnerID=40&md5=645f7f40db94d212d73d3e488b1ed
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
53) Sun, Q., Wu, J., Liu, K.

# 53. Toward Understanding Students' Learning Performance in an Object-Oriented Programming Course:

# The Perspective of Program Quality

```
(2020) IEEE Access, 8, art. no. 8995543, pp. 37505-37517.
```
53) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85081679892&doi=10.1109%2fACCESS.2020.2973470&partnerID=40&md5=44f786f8d1df75597ee6ce47ebb
DOI: 10.1109/ACCESS.2020.

```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
54) Guo, C., Yang, H., Huang, D., Zhang, J., Dong, N., Xu, J., Zhu, J.

# Review Sharing via Deep Semi-Supervised Code Clone Detection

```
(2020) IEEE Access, 8, art. no. 8959206, pp. 24948-24965.
```
54) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85079620738&doi=10.1109%2fACCESS.2020.2966532&partnerID=40&md5=8d155b8423b87b8026a725bac7ca3e
DOI: 10.1109/ACCESS.2020.

```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
55) Fronza, I., Hellas, A., Ihantola, P., Mikkonen, T.

# 55. Code Reviews, Software Inspections, and Code Walkthroughs: Systematic Mapping Study of

# Research Topics

```
(2020) Lecture Notes in Business Information Processing, 371 LNBIP, pp. 121-133.
```
55) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85078437204&doi=10.1007%2f978-3-030-35510-4_8&partnerID=40&md5=7d5822500a9ca7c83cb2e805992b
DOI: 10.1007/978-3-030-35510-4_

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
56) Mumtaz, H., Latif, S., Beck, F., Weiskopf, D.

# 56. Exploranative Code Quality Documents


```
Terms and conditions Privacy policy
```
```
(2020) IEEE Transactions on Visualization and Computer Graphics, 26 (1), art. no. 8807349, pp.
1129-1139. Cited 2 times.
```
56) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85075600970&doi=10.1109%2fTVCG.2019.2934669&partnerID=40&md5=e64d529f72a1630ed41e88996832b
DOI: 10.1109/TVCG.2019.

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```
57) Ochodek, M., Hebig, R., Meding, W., Frost, G., Staron, M.

# 57. Recognizing lines of code violating company-specific coding guidelines using machine learning: A

# Method and Its Evaluation

```
(2020) Empirical Software Engineering, 25 (1), pp. 220-265.
```
57) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85075204546&doi=10.1007%2fs10664-019-09769-8&partnerID=40&md5=8cf3824cf1e4c7096ea29752f6a
DOI: 10.1007/s10664-019-09769-

```
Document Type: Article
Publication Stage: Final
Access Type: Open Access
Source: Scopus
```
58) Aman, H., Amasaki, S., Yokogawa, T., Kawahara, M.

# 58 ~~N/A A Survival Analysis-Based Prioritization of Code Checker Warning: A Case Study Using PMD~~

```
(2020) Studies in Computational Intelligence, 844, pp. 69-83.
```
58) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85070607267&doi=10.1007%2f978-3-030-24405-7_5&partnerID=40&md5=d706ab01c848630593e6c1a248832a
DOI: 10.1007/978-3-030-24405-7_

```
Document Type: Conference Paper
Publication Stage: Final
Source: Scopus
```
59) Shaheen, A., Qamar, U., Nazir, A., Bibi, R., Ansar, M., Zafar, I.

# 59. OOCQM: Object Oriented Code Quality Meter

```
(2020) Studies in Computational Intelligence, 848, pp. 149-163.
```
59) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85070552262&doi=10.1007%2f978-3-030-25225-0_11&partnerID=40&md5=9bb7d3cce08aa556eb1e06b5a96718ba
DOI: 10.1007/978-3-030-25225-0_

```
Document Type: Book Chapter
Publication Stage: Final
Source: Scopus
```

```
Terms and conditions Privacy policy
```
60) Ruiz-Rube, I., Person, T., Dodero, J.M., Mota, J.M., Sánchez-Jara, J.M.

# 60. Applying static code analysis for domain-specific languages

```
(2020) Software and Systems Modeling, 19 (1), pp. 95-110. Cited 1 time.
```
60) https://www.scopus.com/inward/record.uri?eid=2-s2.0-85064242192&doi=10.1007%2fs10270-019-00729-w&partnerID=40&md5=51c146d429a9b057e87177df
DOI: 10.1007/s10270-019-00729-w

```
Document Type: Article
Publication Stage: Final
Source: Scopus
```


# * Protocolo:

1. Seleccion de artículos de Scopus periodo 2019 y 2020 asociados a la búsqueda code AND code quality
2. Exportación de bib para poder utilizar (utilizad de Scopus)
3. Download de los articulos y vinculación vía Mendeley ('pendiente')
4. Con el bib exportado creación del listado de artículos 
5. Diseño del template a completar
6. En este caso particular se utilizo una herramienta colaborativa dodne en una primera iteración cada investigador realiza por separado la extracción e identifica los atributos de Q de código, prácticas metdos etc. 
7. En una segunta iteracón ise ajustan los tags
8. Se decidió  selección 5 papers con los id 5,10,15,20,25 para realizar una primera reónvisi.
9. Se utilizó una guia de colores y etiquetas (originamente utilizado por el análisis temático para establecer la codificación y posterior extracción y digitalización. TODO: Sacar foto)
10. Se imprimieron los paper (y se realizó en paper para despues poder ver lo factible de realizarlo en otras herramientas como Atlas TI )
11. Una vez identificado el analisis temático en las categorías existentes se calificó como Low o High el grado de relación con la tematica de Q código ( una alternativa podria ser una escala de likert)
12. Varías ventajas de la utilización de hackmd como entorno colaborativo en relación al versionado, time stamp e integración con git, para posible extensión y replicación