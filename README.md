# AOCP Print Models

The Arabic-script OCR Catalyst Project trains models for transcribing and analyzing the layout of books printed in Arabic script. 

## Layout models:

These models detect lines of text and regions (main text block, page numbers, running titles, etc.)
You can find the types of regions a model is trained to recognize in the header of the .mlmodel file
(open it with a text editor to read the header).

Best layout model currently: 
* layout-20210711_AQ.mlmodel (region types: Catchword, Footnotes, Illustration, Main, Marginal_Material, Page_Number, Running_Title, Title)

Other layout models:
* layout-20210711.mlmodel (region types: Catchword, Footnotes, Illustration, Main, Marginal_Material, Page_Number, Running_Title, Title)
* layout-20221220.mlmodel (region types: Catchword, Footnotes, Illustration, Main, Marginal_Material, Page_Number, Running_Title, Title)

## Transcription models:

These models transcribe images of lines of text in Arabic script (any language) into machine-actionable text. 
Our primary focus was Arabic and Persian. You can also find models for Urdu and Ottoman Turkish. 
Generalized transcription models beginning with `apt` (for Arabic, Persian, and Turkish) were trained on Arabic, Persian, and Ottoman Turkish.

Best generalized transcription model currently: 
* apt-20221130.mlmodel

Best Urdu-specific transcription model currently: 
* urdu-20221130.mlmodel
