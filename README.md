# phone_parser

Collects urls
checks if 'ИНН' 'ОГРН' 'ИП' 'ООО' upper and lower case on the main page
parses russian phone numbers starting with 79 and makes whatsapp hyperlinks
creates csv table with columns URL - ИНН - ОРГН - ООО - ИП and 1 or more phone columns
before import to excel delete ' " [ ]
for import in Excel select devider ',' and encoding 65001
