Este proyecto intenta averigual la entropia del alfabeto inglés y el español.
Se realiza el proceso teniendo en cuenta la frecuencia de apariciónsegun el
diccionario y segun el uso cotidiano (textos) de manera separada, pues la 
frecuencia de aparicion de cada letra varía en ambos casos.Para esto se tomaron
varios libros en formato .txt de ambos idiomas, a continuación las fuentes:
- Español: https://github.com/busiris2014/7506Condor1C2014/tree/master
- Inglés: https://www.gutenberg.org 

También se tomaron las listas de palabras (diccionario) de las siguientes fuentes:
- Español: https://github.com/lorenbrichter/Words/tree/master (este diccionario no contiene signos de acentuación)
- Inglés: https://github.com/lorenbrichter/Words/tree/master

En el caso del español tenemos signos de acentuación (á, é, í, ó, ú), estos
caracteres se simplificarán asignandolos a su vocal respectiva (á->a, é->e, í->i, ó->o, ú->u)
debido a que según la RAE: 
> "*...El abecedario del español queda así reducido a las veintisiete letras siguientes: a, b, c, d, e, f, g, h, i, j, k, l, m, n, ñ, o, p, q, r, s, t, u, v, w, x, y, z.*"

*fuente: https://www.rae.es/espanol-al-dia/exclusion-de-ch-y-ll-del-abecedario#:~:text=El%20abecedario%20del%20español%20queda,%2C%20x%2C%20y%2C%20z.*
