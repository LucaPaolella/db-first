Consegna:

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Una volta fatto, pushate lo screenshot della vostra progettazione.



Identificatore      Nome elemento                Tipo Dato       NULL        Default        Unique    Auto_Increment

1                   Ordine modelli	             INT             NotNull     no             yes       yes
2                   Marca	                     VARCHAR(20)     NotNull     no             no        no
3                   Modello	                     VARCHAR(20)     NotNull     no             no        no
4                   Anno	                     YEAR            Null        no             no        no
5                   Chilometraggio	             INT             NotNull     no             no        no
6                   Prezzo	                     DOUBLE(13,2)	 NotNull     yes(1000)      no        no
                                                