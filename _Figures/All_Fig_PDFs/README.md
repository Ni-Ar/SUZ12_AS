

**Note**: The scatter plots in figures 5, 6 and 7 are rasterized only at the actual point layer. This is done to have a smaller size pdf. All the other plots are embeded pdfs (vectorial images). The gel (PCR and WB) images are 400 dpi embedded tiff images or higher that are compressed down to 300 dpi (to match journal requirements) when exporting to pdf in Adobe Illustrator.

```shell
cd ~/OneDrive\ -\ CRG\ -\ Centre\ de\ Regulacio\ Genomica/Suz12_AS_project/_Figures
```

To merge all individual figures pdfs into one.

```sh
pdfunite Fig1/Fig1_v10.pdf Fig2/Fig2_v5.pdf Fig3/Fig3_v6.pdf Fig4/Fig4_v5.pdf Fig5/Fig5_v8.pdf Fig6/Fig6_v3.pdf Fig7/Fig7_v2.pdf Supplementary_Fig/Supplementary_Figure_S8.pdf All_Fig_PDFs/Figures_1-7_Supplementary_1-8.pdf
```

```sh
open All_Fig_PDFs/Figures_1-7_Supplementary_1-8.pdf
```

