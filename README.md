# citationApp
citationApp is a project of a web application leveraging [Citation.js](https://citation.js.org/) for reference management in writing process.

Users can use this tool to build, update, export their own refernce dataset without making actual reference list. The so-called reference dataset processed by this application is an [onject](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object), including in-text citation as key and DOI of the corresponding citation as value. After the manuscript (in-text citation) has been modified. The refernce dataset can be automatically updated by reloading the manuscript text. So, users can continue adding DOI to new refrence or get the new reference dateset.

## Usage
- copy and paste the your manuscript > load your texts > add DOI to your reference > render APA citations

## Application
- [APA Citation Manager](https://billbillbilly.github.io/paper_reference/citation_app/)
- [Project folder](https://github.com/billbillbilly/billbillbilly.github.io/tree/main/paper_reference/citation_app)

## Limits
Since application is based on Citation.js, it currently can only take the DOI to get the APA citation. Any reference without DOI information is not supported at this point.
