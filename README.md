# French-Politic-Speech-Dataset
All political speechs made in France since the beginning of the 5th Republic (1958) to the end of the first mandat made by Macron (2022). Those speechs are referenced by www.vie-publique.fr.  

More than 140.000 speechs are stored in this dataset. (About 1.1 GB, including more than 900MB of pure text)

The json contains one key "speechs" which is an array containing all speechs. Every speech is in the form :  
```
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
```

## Download

Github LFS restricts the storage so the dataset as been moved to a google drive. The download link is the following:
https://drive.google.com/file/d/1byaobaQrP0cLk_pkpZwYN2sVKwgnS5qP/view?usp=sharing

Scraped by Yannis Bendi-Ouis.   
Website: https://www.naowak.fr/

## License
This project is licensed under the MIT License with an Acknowledgment Clause. See LICENSE for more information.
