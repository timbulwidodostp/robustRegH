# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Robust Fitting of Linear Models using Huber Psi Function Use robustRegH (robustreg) With (In) R Software
install.packages("robustreg")
library("robustreg")
robustRegH = read.csv("https://raw.githubusercontent.com/timbulwidodostp/robustRegH/main/robustRegH/robustRegH.csv",sep = ";")
# Estimation Robust Fitting of Linear Models using Huber Psi Function Use robustRegH (robustreg) With (In) R Software
robustRegH_1 <- robustRegH(Dependen ~ Independen_1 + Independen_2 + Independen_3, data = robustRegH)
print(robustRegH_1)
robustRegH_2 <- robustRegH(Dependen ~ Independen_1 + Independen_2 + Independen_3 ,data=robustRegH, m=FALSE)
print(robustRegH_2)
# Robust Fitting of Linear Models using Huber Psi Function Use robustRegH (robustreg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished