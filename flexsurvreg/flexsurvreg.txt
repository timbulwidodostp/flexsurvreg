# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Flexible parametric regression for time-to-event data Use flexsurvreg With (In) R Software
# Flexible Parametric Survival and Multi-State Models Use flexsurvreg With (In) R Software
install.packages("flexsurv")
install.packages("mvtnorm")
library("flexsurv")
library("mvtnorm")
flexsurvreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/flexsurvreg/main/flexsurvreg/flexsurvreg.csv",sep = ";")
# Estimation Flexible parametric regression for time-to-event data Use flexsurvreg With (In) R Software
# Compare generalized gamma fit with Weibull
flexsurvreg_gengamma <- flexsurvreg(formula = Surv(futime, fustat) ~ 1, data = flexsurvreg, dist="gengamma")
flexsurvreg_gengamma
flexsurvreg_weibull <- flexsurvreg(formula = Surv(futime, fustat) ~ 1, data = flexsurvreg, dist="weibull")
flexsurvreg_gengamma
# Flexible parametric regression for time-to-event data Use flexsurvreg With (In) R Software
# Flexible Parametric Survival and Multi-State Models Use flexsurvreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished





