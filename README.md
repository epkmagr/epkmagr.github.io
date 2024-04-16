# epkmagr.github.io
Östsvenska Veteran hemsidan

Håller på att uppdatera innerekorden för 2024
OK K/M 35-50

Byta namn på flera .htm filer till .html
for i in *.htm; do mv -- "$i" "${i%.htm}.html"; done

Byta till nytt år
cp -r 2023 2024

Byt ut år tal från  2022 till 2024 i html-filerna
rpl --dry-run '2022<' '2024<' *.html
rpl '2022<' '2024<' *.hmtl