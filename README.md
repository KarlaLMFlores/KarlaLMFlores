import pandas as pd
tarifas=[

    ('Sur','Sur',4.89577,	0.01585,	5.03491),
    ('Sur','Centro',10.81326,0.07357,11.4289),
    ('Sur','Occidente'	,12.38628,	0.08909,	13.12899),
    ('Sur',	'Golfo',	7.96424,	0.04336,	8.3438),
    ('Sur' ,	'Norte',	12.3113,	0.08796,	13.04508),
    ('Sur',	'Istmo',	10.73376,	0.05929,	11.86292),
    ('Golfo', 'Centro',	9.2902,	0.05772,	9.78091),
    ('Golfo',	'Occidente',	10.86322,	0.07324,	11.481)
]

df = pd.DataFrame(tarifas, columns = ['Zona inyección', 'Zona extracción', 'Capacidad Base Firme', 'Uso Base firme', 'volumétrica'])
##print(df)
display(df)
