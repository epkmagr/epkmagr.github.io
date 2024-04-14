# epkmagr.github.io
Östsvenska Veteran hemsidan


Byta namn på flera .htm filer till .html
for i in *.htm; do mv -- "$i" "${i%.htm}.html"; done

Test att generera doc till html i terminalen:
https://github.com/tobya/DocTo/blob/docto/pages/all/ConvertDocToFileHTML.md