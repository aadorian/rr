[![hackmd-github-sync-badge](https://hackmd.io/re_vKvaTQnq7NhaQ-9sxQQ/badge)](https://hackmd.io/re_vKvaTQnq7NhaQ-9sxQQ)
**#Protocol RR **

Paper templete para CIBSE 
https://www.overleaf.com/7499996126hncrzznbwfxm

References Cartaxo: https://speakerdeck.com/brunocartaxo

Tool convertir Excel to Latex para tabla de RR 
https://www.tablesgenerator.com/

Template de Evidence B. https://docs.google.com/document/d/1-IH_sOd7Hrrs6Ri5GaBBoi95xgnhXncw15kYLnXf4iY/edit?usp=sharing

* Motivación - No se presenta en la literatura una definición de consenso respecto de que se entiende por calidad de código.
Objetivo :  Lograr una definición de QC y sus principales características / dimensiones a partir de una RR.

_PI : ¿Qué se entiende por Calidad de Código?

_PI: ¿Qué técnicas, métodos, prácticas, estándares y herramientas se utilizan en la industria para controlar la calidad del código?

Def. QC:   * {max min (ATRIB_Q Interna/Externa) (Costos)}
            sa restricciones contexto* 
> [TOC]
> 

---

`*PI:¿Qué se entiende actualmente por  Calidad de Código? *`
Keywords: Code Quality AND Software


---
` TITLE-ABS-KEY ( "code quality"  AND  software )  AND  ( LIMIT-TO ( PUBYEAR ,  2021 )  OR  LIMIT-TO ( PUBYEAR ,  2020 ) )` 


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
- CQ_PEOP/TOOL
`NULL`
- CQ_OTROS: 
`NULL`

---


-  Comentarios : - ``
---

- CQ_CITE_@ref: 
```
NULL
```

- Author / TimeStamp Start/ End
> [name= ]
> START_[time=]
> END_ [time=]



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

-  CQ_ARQ_ATRIB
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


---

-  COMMENTS : - `Case Study dentro del contexto de ESE (Empirical Software Eng.)` `menciona a GIT como tecnología y GITHub como repo central` y `PI asociada al tema RQ2. Does code quality affect pull request acceptance?... 'Pull request are a verypoerfull instrument', Aporte de este paper: Code qualite does not seem to be a keydriver for the acceptance of PR`

---

- CQ_CITE_@ref: 
```
NULL
```

- Author / TimeStamp Start/ End
> [name=Alejandro Adorjan]
> START_[time=Sun, Nov 8, 2020 3:55 PM]
> END_ [time=Sun, Nov 8, 2020 4:15 PM]






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