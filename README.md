# Analyse des Formats de Facture 

L'objectif principal de cette étude est d'analyser les structures et les caractéristiques des différents formats, notamment en examinant le positionnement des éléments clés tels que la date, le numéro de facture,le montant TTC, et l'identification du réparateur, dans le but d'améliorer  la détection et lecture conforme des critères d'une facture par le Robot Facture. 

L'étude porte sur 115 factures intégrées dans Robot Factures via BCA Connect. Parmi celles-ci, nous avons identifié 81 réparateurs distincts, chacun émettant ses propres factures selon 23 formats différents. 

 
# Taux de précision du Robot Facture
Un aspect crucial de notre étude était l'identification des formats de factures conduisants soit à une absence de lecture soit à une lecture non-conforme. Ces non-conformités/ absences ont été étudiées en fonction des quatre critères précidemment cités.

## Visualisations des 23 formats 

<iframe src='https://flo.uri.sh/visualisation/16740266/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/16740266/?utm_source=embed&utm_campaign=visualisation/16740266' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>



# Visualisation des occurences des 23 formats



<iframe title="[ Occurence des formats ]" aria-label="Pie Chart" id="datawrapper-chart-9A35f" src="https://datawrapper.dwcdn.net/9A35f/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="564" data-external="1"></iframe>




# Visualisation détaillée  des non-conformités


<iframe title="[ Format et non conformités  ]" aria-label="Split Bars" id="datawrapper-chart-W73Vg" src="https://datawrapper.dwcdn.net/W73Vg/2/" scrolling="no" frameborder="0" style="border: none;" width="600" height="665" data-external="1"></iframe>



# Visualisation Pareto

![Numero](https://github.com/thizirisaighi/Entreprise/blob/main/DateNum%C3%A9ro.png)
![TTC](https://github.com/thizirisaighi/Entreprise/blob/main/MontantAction.png)


# Identification réparateur 

Les occurrences sur le critère identification réparateur n'ont pas été relevées du fait de leur faible volumétrie et de l'action d'identification formelle à partir de la base réparateur. 
En outre, la lecture d'un numéro secondaire inscrit sur dans la base réparateur ou la lecture avec des espaces entre chiffres d'un numéro de téléphone conforme n'ont pas permis une identification du réparateur. 

# Conclusion : 
Les occurrences d'absence ou de lecture non conforme devraient permettre d'améliorer le taux de précision de Robot Facture. 

