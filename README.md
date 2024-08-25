# Solar-Engineering
Este repositorio será utilizado para la implementación de software tipo open-access para problemas de Ingeniría Solar. Estos trabajos desarrollados estan alineados a los desarrollos requeridos a los actores principales en matería de energía en el país. 

# INDICE
## Tiempo Solar real. (ST_90°W Std)
Este programa resuelve la ecuation de tiempo(EOT) para luego definir en minutos el ajuste en tiempo real de la hora de culminación solar en cualquier lugar que se encuentre en el meridiano -90°W. El desarrollo esta orientado para centroamérica. 

La ecuación para tiempo solar en minutos es: 
$T_{so}=12-\frac{(L_o+L_{std)}}{15}-\frac{EOT}{60}$; $L_{std}=90°$  (Ecuación propuesta por Duffie & Beckman (2013))

**Ecuación de Tiempo** 
$EOT= 9.87*\sin{2B}-7.53*\cos{B}-1.50*\sin{B}$ ; donde $B=\frac{360}{364}(n-81)$ n respresenta el dìa consecutivo del año, donde los valores oscilan desde 1<n<365

Este codigo permite ver la hora de culiminación para los 365 dias del año.

