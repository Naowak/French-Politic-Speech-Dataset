# French-Politic-Speech-Dataset
All political speechs made in France since the beginning of the 5th Republic (1958) to the end of the first mandat made by Macron (2022). Those speechs are referenced by www.vie-publique.fr.  

More than 140.000 speechs are stored in this dataset.  

The json contains one key "speechs" which is an array containing all speechs. Every speech is in the form :
{
    'title': str, 
    'speakers': list of object in the form : {'name': str, 'function': str},  
    'context': str, 
    'keywords': list of str, 
    'thematics': list of str, 
    'datetime': str, 
    'readtime': str, 
    'kind': str, 
    'text': str
}  

Scraped by Yannis Bendi-Ouis.
Website: https://www.naowak.fr/