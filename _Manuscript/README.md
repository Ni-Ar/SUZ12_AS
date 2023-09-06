Move to directory

```shell
cd ~/OneDrive\ -\ CRG\ -\ Centre\ de\ Regulacio\ Genomica/Suz12_AS_project/_Manuscript/SUZ12_AS_Manuscript_2
```

This did not work

```shell
pandoc Article.tex --citeproc --bibliography SUZ12_AS_References.bib --csl zHenriquesLab-StyleBioRxiv.cls -o Formatted_converted.docx
```



```shell
pandoc Article.tex --bibliography SUZ12_AS_References.bib -o Formatted_converted.docx
```

