# ANADE branches dataset
The datasets consists of branches of the ANADE (Agence Nationale d'Appui et de Développement de l'Entreprenariat)


## Source
[ANADE](https://promoteur.ansej.dz/).
(https://promoteur.ansej.dz/Annexes/Trouver_Annexe)
 

## Data format

| Key          | Description | 
| ------------ | -----------------------|
| id| Identification number |
| code| Wilaya code of where the branch is located |
| wilaya |Wilaya name                |
| ville |City where the branch is located  |
| adresse |Address of the branch |
| tel | Telephone number(s)                 |
| fax | Fax number(s) |
| email     |Branch email                 |
| lon | Longitude                 | 
| lat |Latitude            |

## Dataset creation steps

1. Getting data from  [ANADE site](https://promoteur.ansej.dz/Annexes/Trouver_Annexe) using the [script]() .
2. Data validation and correction using QGIS

Dataset created on Mar 10 , 2021

## Comments
Branches of the following wilayas are missing : Tamenrasset,Bouira,Oum El Bouaghi and Tipaza
