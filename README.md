# Trebuchet UDD 
repositorio sobre la catapulta desarrollada para estudiantes udd

El desarrollo de este proyecto está inspirado en el trabajo de [Tom Stalton](https://www.youtube.com/@TomStantonEngineering).

![foto trebuchet](img/treb01.jpg)

>*Un **fundíbulo** (trebuchet) está formado por una viga o barra de madera sujeta a un armazón que la mantiene elevada del suelo. El punto de apoyo de la viga (usualmente un eje) está colocado en la parte superior del armazón. Del brazo corto de la barra se encuentra suspendido un contrapeso y del brazo largo una honda. La honda tiene un extremo atado a la viga y un extremo libre con un lazo donde se engancha la bolsa del proyectil.*
>[Wikipedia](https://es.wikipedia.org/wiki/Fundibulo)

---

### Herramientas
- Sierra ingletadora, serrucho, o similar
- Cortadora láser (en taller)
- Impresora 3d FDM (en taller)
- Taladro (en taller)
- Lima redonda para madera
- Broca madera o metal 8.5mm
- Broca madera o metal 10mm
- Llave Allen 6mm
- Llave Allen 8mm
- Llave Allen 3mm para el sk10
- Llave punta/corona 13mm
- Llave punta/corona 17mm


### Materiales

#### Simples

|ID| Material | Detalle | Cantidad |
|:---|:---|---:|---:|
|**palo_60**| Pino 3x2" cepillado | 60cms| 4 |
|**palo_80**| Pino 3x2" cepillado | 80cms| 2 |
|**palo_22**| Pino 3x2" cepillado | 22cms| 2 |
|**palo_54**| Pino 2x1" cepillado | 54cms| 1 |
|**palo_12**| Pino 2x1" cepillado | 12cms| 1 |
|**palo_30**| Pino 2x1" cepillado | 30cms| 2 |
|**torn_3**| Tornillo cincado cruz | 3"| 8 |
|**eje_40**| Barra acero 10mm | ~40cms | 1 |
|**sk_10**| Soporte aluminio | SK10 | 2 |
|**hilo_12**| Hilo 5/16 | 12cms | 3 |
|**tuer_516**| Tuerca hexagonal | 5/16" | 8 |
|**per_m8**| Perno Parker | M8 40mm | 9 |
|**tuer_m8**| Tuerca hexagonal | M8 | 9 |
|**gol_m8**| Golilla plana | M8 | 18 |
|**per_m10**| Perno Parker | M10 90mm | 24 |
|**tuer_m10**| Tuerca hexagonal | M10 | 24 |
|**gol_m10**| Golilla plana | M10 | 48 |

#### Fabricados

|ID| Material | Detalle | Cantidad |
|:---|:---|---:|---:|
|**mdf_inf**| MDF 3mm | [unionInferior-DXF](/archivos/CORREGIDOunionInferiorBaseCatapulta-MDF3mm-16xCatapulta-48Total.dxf) | 8 |
|**mdf_sup**| MDF 3mm | [unionSuperior-DXF](/archivos/CORREGIDOunionSuperiorBaseCatapulta-MDF3mm-8xCatapulta-24Total.dxf) | 4 |
|**mdf_bra**| MDF 3mm | [unionBrazo-DXF](/archivos/unionBrazoContrapeso-MDF3mm-4xCatapulta-12Total.dxf) | 4 |
|**mdf_con**| MDF 3mm | [contrapeso-DXF](/archivos/contrapesoCatapulta-MDF3mm-4xCatapulta-12Total.dxf) | 4 |
|**parche**| Cuerina | [parcheBrazo-DXF](/archivos/parcheCatapultaV2-1xCatapulta.dxf) | 4 |
|**pla_eje**| Pieza impresa PLA | [separadorEje-STL](/archivos/separadorEjeCentral-2xCatapulta-6Total.stl) | 2 |
|**pla_uni**| Pieza impresa PLA | [separadorUnion-STL](/archivos/separadorEjeContrapeso-1xCatapulta-3Total.stl) | 1 |
|**pla_con**| Pieza impresa PLA | [separadorContra-STL](/archivos/separadorMdfContrapeso-1xCatapulta-3Total.stl) | 1 |
|**pla_cab**| Pieza impresa PLA | [cabezalLanzador-STL](/archivos/cabezalLanzador-1xCatapulta-3Total.stl) | 1 |


----

### Fabricación y ensamble

Para manufacturar las partes de MDF y de PLA, se necesitan de maquinas de fabricación digital, tanto una cortadora láser como una impresora 3d FDM. Para la cortadora láser se usan los archivos con la extensión `.dxf` y se prepara el archivo con los parámetros adecuados para cortar el MDF. Y para imprimir las piezas de PLA se usan los archivos `.stl`, se necesita de filamento para la impresora y preparar el archivo en un *slicer* con un relleno de al menos un 20%, **pla_eje** está diseñado para ser impreso con su lado más ancho pegado a la cama.

Para las piezas **palo_[x]** se usa pino seco cepillado, se puede encontrar en barracas y ferreterías, y se necesitan de dos diferentes espesores, los de 2x1" (que cepillado queda en ~40x20mm), y los de 3x2" (que cepillados quedan de ~65x40mm), dependiendo del largo de las vigas se habrá que cubicar y calcular la cantidad a comprar, de acuerdo a las dimensiones y cantidad de los **palo_[x]**. Cada uno de ellos debe ser perforado en los lugares donde hay pernos, ejes o hilos. Para los orificios de pernos m10 se usa una broca de 10mm y se repasa con una lima, y para los orificios m8 se usa una broca de 8.5mm.

Antes de ensamblar las diferentes partes del trebuchet se debe saber cómo se pone un perno. Para este proyecto se usan pernos parker, los cuales necesitan de una llave hexagonal (perno m8 hexágono de 6mm, y perno m10 hexágono de 8mm), se recomienda del tipo allen para ayudar al torque, y para sus respectivas tuercas se necesitan 2 llaves punta/corona (tuerca m8 llave de 13mm y tuerca m10 llave de 17mm). Eso en cuanto a herramientas, ahora en cuanto a material por cada sujeción se necesita de un perno, dos golillas y una tuerca (1x **per_m8**, 1x **tuer_m8**, 2x **gol_m8** en el caso de los orificios m8; y 1x **per_m10**, 1x **tuer_m10**, 2x **gol_m10** en el caso de los orificios m10). Para colocar un perno primero se le pone una golilla, luego se atraviesan la perforaciones de los materiales a ensamblar, tras ello se pone la otra golilla y se pone la tuerca dando un par de vueltas de forma manual. Después hay que asegurar la unión usando la llave allen y la punta/corona correspondiente; esto se puede hacer inmediatemente después de poner cada perno, pero se recomienda poner varios pernos primero y luego apretarlos, esto facilita calces y da mayor movilidad mientras se van poniendo las piezas. 

TODO armado brazo y contrapeso

TODO armado base

TODO armado final

### Uso de la catapulta

---
![trebuchet](https://web.archive.org/web/20090728004740/http://us.geocities.com/krashous/imagenes/Animaciones/trebuchet2.gif)


>documentado por [AndresMartinM](https://github.com/AndresMartinM) 2025