#2.1
library(openxlsx)

Opis <- read.xlsx("ROLN_3179.xlsx", sheet = 1)

#2.2
B <- Opis[ , 2]
s<- strsplit(B, " ")
u<- unlist(s)
slowa<- unique(u)
write.table(slowa, file = "slowa.txt.csv", row.names = FALSE, col.names =TRUE, fileEncoding = "UTF-8", )