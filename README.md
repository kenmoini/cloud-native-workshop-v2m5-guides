The CCN Roadshow(Dev Track) Module 5 Guide 2021
===

This module enables developers to integrate Red Hat Single Sign On with a set of Applications

This is super unofficial stuff, please don't use.

Agenda
===
* Getting Started with Red Hat Single Sign-On
* Deploying Red Hat Single Sign-On
* Adding Applications and Authentication
* Additional Modifications

Lab Instructions on OpenShift
===

Note that if you have installed the lab infra via APB, the lab instructions are already deployed.


_Migration_: the docs have been migrated from markdown to adoc. 
Using pandoc e.g: 
``` 
for i in *.md; do pandoc --standalone --to=asciidoc --output=$i.adoc $i; done;
```