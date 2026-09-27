```shell
pandoc ".\La señalética y su importancia en el entorno educativo - v2.md" -o "La señalética y su importancia en el entorno educativo - v2.docx" --lua-filter="Z:\Users\MRodz\Documents\U\Trick-Tools\Literature_Redaction\Zotero\Plugins\pandoc-filters\md_to_docx_pandoc_zotero_filter.lua" --metadata=zotero_scannable_cite:false --metadata=zotero_client:zotero --metadata=zotero_author_in_text:true --metadata=zotero_csl_style:apa --metadata=zotero_sorted:true --citeproc --reference-doc "Z:\Users\MRodz\Documents\U\6th_Cycle\Data_Fundamentals (Itinerario)\APA7_Template_A4_tabla_Carta.docx" -f markdown+tex_math_dollars # note: zotero_author_in_text is crucial for managing citations inside markdown.
# e.g @djikstra1999 is an author-in-line citation. So if the attribute is set to false, then pandoc will not detect this citation unless it's formatted as: [@djikstra1999] (that is a parenthetical citation)
```

