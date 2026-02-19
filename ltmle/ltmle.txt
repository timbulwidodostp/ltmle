# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Longitudinal Targeted Maximum Likelihood Estimation (LTMLE) Use ltmle With (In) R Software
install.packages("ltmle")
library("ltmle")
# Estimate Longitudinal Targeted Maximum Likelihood Estimation (LTMLE) Use ltmle With (In) R Software
ltmle = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ltmle/main/ltmle/ltmle.csv", sep = ";")
ltmle <- ltmle(ltmle, Anodes = "A", Ynodes = "Y", abar = 1)
summary(ltmle)
# Longitudinal Targeted Maximum Likelihood Estimation (LTMLE) Use ltmle With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished