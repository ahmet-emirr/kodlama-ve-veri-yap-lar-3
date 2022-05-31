# Proje-3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2,] dizisinin Binary-Search-Tree aşamalarını yazınız.
##### İkili arama ağacı, her düğümün solundaki koldan ulaşılabilecek bütün verilerin düğümün değerinden küçük, sağ kolundan ulaşılabilecek verilerin değerinin o düğün değeri

|     Açıklama   |  |  |  |
|--              |- |- |- |
|**root=7**      |  | 7|  |



**5 sayısı 7'den küçük olduğundan 7'nin soluna eklenir**
|   Açıklama  |     |  |  |
|--           |-    |- |- |
|             |     |  | 7|
|             |     | /|  |
|**5 ekledik**|**5**|  |  |


**1 sayısı 5'ten ve 7'den küçük olduğunda 7 ve 5'in soluna ekledik**
|     Açıklama  |     |  |  |  |  |
|             --|--   |--|- |- |- |
|               |     |  |  |  | 7|
|               |     |  |  | /|  |
|               |     |  | 5|  |  |
|               |     | /|  |  |  |
|**1 ekledik**  |**1**|  |  |  |  |

**8 sayısı 7'den büyük olduğundan 7'nin sağına ekledik**
| Açıklama      |  |  |  |  |  |  |     |
|--             |--|--|- |- |- |- |-    |
|               |  |  |  |  | 7|  |     |
|               |  |  |  | /|  |\ |     |
|**8 ekledik**  |  |  | 5|  |  |  |**8**|
|               |  | /|  |  |  |  |     |
|               | 1|  |  |  |  |  |     |


