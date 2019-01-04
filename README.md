# Tarea_Nro4
Ejercicios de for-loop


dv(19291687)

rm(Ruts)

t<-proc.time()
Ruts<-list()
for(i in 19291687:(19291687+5000)){
    rut<-print(paste(i,"-",dv(i)))
    Ruts <- c(Ruts,rut)
}
proc.time()-t
