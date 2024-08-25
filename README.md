# Solar-Engineering
Este repositorio será utilizado para la implementación de software tipo open-access para problemas de Ingeniría Solar. Estos trabajos desarrollados estan alineados a los desarrollos requeridos a los actores principales en matería de energía en el país. 

# INDICE
## Tiempo Solar real. [ST_90°W Std](https://github.com/IICAT-FI-UNAH/Solar-Engineering/blob/main/ST_90%C2%B0W%20Std)
Este programa resuelve la ecuation de tiempo(EOT) para luego definir en minutos el ajuste en tiempo real de la hora de culminación solar en cualquier lugar que se encuentre en el meridiano -90°W. El desarrollo esta orientado para centroamérica. 

**La ecuación para tiempo solar** en minutos es: 
$T_{so}=12-\frac{(L_o+L_{std)}}{15}-\frac{EOT}{60}$; $L_{std}=90°$  (Ecuación propuesta por *Duffie & Beckman (2013)*)

**Ecuación de Tiempo**: 
$EOT= 9.87*\sin{2B}-7.53*\cos{B}-1.50*\sin{B}$ ; donde $B=\frac{360}{364}(n-81)$; siendo n el día consecutivo del año, donde los valores oscilan desde 1<n<365 (Ecuación propuesta por *Kalogirou(2014)* y *Goswami (2015)*.

*Referencias*
1.	Duffie, J. A., & Beckman, W. A. (2013). Solar Engineering of Thermal Processes (4th ed.). Wiley.
2.	Kalogirou, S. A. (2014). Environmental characteristics. In S. A. Kalogirou (Ed.), Solar Energy Engineering (2nd ed., pp. 51-123). Academic Press. https://doi.org/10.1016/B978-0-12-397270-5.00002-9
3.	Goswami, D.Y. (2015). Principles of Solar Engineering (3rd ed.). CRC Press. https://doi.org/10.1201/b18119  

\Este codigo permite ver la hora de culiminación para los 365 dias del año.

