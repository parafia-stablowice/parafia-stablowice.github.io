---
title: "{{ .Name }} - {{ ((time .Name).AddDate 0 0 6 ).Format "2006-01-02"}}"
date: {{ .Name }}
draft: true
type_name: "Intencje Mszy Świętych"
---

**niedziela** [{{ .Name }}]

* 8.30

  * 

* 10.00

  * 

* 11:30

  * 

* 13:00

  * 

* 18:00

  * 

**poniedziałek** [{{ ((time .Name).AddDate 0 0 1 ).Format "2006-01-02" }}]

* 8.00

  * 

* 18:00

  * 

**wtorek** [{{ ((time .Name).AddDate 0 0 2 ).Format "2006-01-02" }}]

* 8.00

  * 

* 18:00

  * 

**środa** [{{ ((time .Name).AddDate 0 0 3 ).Format "2006-01-02" }}]

* 8.00

  * 

* 18:00

  * 

**czwartek** [{{ ((time .Name).AddDate 0 0 4 ).Format "2006-01-02" }}]

* 8.00

  * 

* 18:00

  * 

**piątek** [{{ ((time .Name).AddDate 0 0 5 ).Format "2006-01-02" }}]

* 8.00

  * 

* 18:00

  * 

**sobota** [{{ ((time .Name).AddDate 0 0 6 ).Format "2006-01-02" }}]

* 8.00

  * 

* 18:00

  * 
