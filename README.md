Ky projekt përpunon të dhëna CSV për regjistrime kursesh.
1. parse_csv lexon dhe filtron rreshtat e vlefshëm.
2. clean_rows pastron dhe normalizon fushat.
3. Funksionet filter_by_* dhe sum/avg analizojnë të dhënat.
4. Raportet për kurs/qytet formatohen me as_money.
Testuar me raste kufi: pagesë jo-numerike, emër bosh.
