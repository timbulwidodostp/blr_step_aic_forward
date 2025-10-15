# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Stepwise AIC forward selection Use blr_step_aic_forward (blorr) With (In) R Software
install.packages("blorr")
library("blorr")
blr_step_aic_forward = read.csv("https://raw.githubusercontent.com/timbulwidodostp/blr_step_aic_forward/main/blr_step_aic_forward/blr_step_aic_forward.csv",sep = ";")
# Estimation Stepwise AIC forward selection Use blr_step_aic_forward (blorr) With (In) R Software
blr_step_aic_forward <- glm(honcomp ~ female + read + science, data = blr_step_aic_forward, family = binomial(link = 'logit'))
blr_step_aic_forward_1 <- blr_step_aic_forward(blr_step_aic_forward)
blr_step_aic_forward_1
blr_step_aic_forward_2 <- blr_step_aic_forward(blr_step_aic_forward, details = TRUE)
blr_step_aic_forward_2
# Stepwise AIC forward selection Use blr_step_aic_forward (blorr) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished