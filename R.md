# R Statistical Programming Language Hints

Probably will mostly be dumps from the RStudio history.

## Perhaps some hints on Venn Diagrams
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
pciAuditList
summaryList = list(mckessonOne,pciAuditList)
items - sort(unique(unlist(summaryList)))
items <- sort(unique(unlist(summaryList)))
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=2)
colnames(MAT) <- ("mckessonOne","pciAudit")
colnames(MAT) <- c("mckessonOne","pciAudit")
rowname(MAT) <- items
rownames(MAT) <- items
lapply(seq_along(summaryList),function(i) {})
lapply(seq_along(summaryList),function(i) {})
lapply(seq_along(summaryList),function(i) { MAT[items %in% summaryList[[i]],i] <<- table(summaryList[[i]])})
MAT
library(venneuler)
load("http://www.rforge.net/venneuler")
install.packages("venneuler")
library(venneuler)
v <- venneuler(MAT)
plot(v)
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
summaryList = list(mckessonOne,mckessonTwo,autostarOne,rmsOne,xifinOne,pciAuditList)
items <- sort(unique(unlist(summaryList)))
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=2)
colnames(MAT) <- c("mckessonOne","mckessonTwo,"autostarOne","rmsOne","xifinOne","pciAudit")
colnames(MAT) <- c("mckessonOne","mckessonTwo","autostarOne","rmsOne","xifinOne","pciAudit")
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=6)
colnames(MAT) <- c("mckessonOne","mckessonTwo","autostarOne","rmsOne","xifinOne","pciAudit")
rownames(MAT) <- items
lapply(seq_along(summaryList),function(i) { MAT[items %in% summaryList[[i]],i] <<- table(summaryList[[i]])})
v <- venneuler(MAT)
plot(v)
savehistory("/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/original_venn_diagram.Rhistory")
plot(v)
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
summaryList = list(mckessonOne,mckessonTwo,pciAuditList)
items <- sort(unique(unlist(summaryList)))
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=3)
colnames(MAT) <- c("mckessonOne","mckessonTwo","pciAudit")
rownames(MAT) <- items
lapply(seq_along(summaryList),function(i) { MAT[items %in% summaryList[[i]],i] <<- table(summaryList[[i]])})
v <- venneuler(MAT)
plot(v)
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
summaryList = list(mckessonOne,mckessonTwo,autostarOne,rmsOne,xifinOne,pciAuditList)
items <- sort(unique(unlist(summaryList)))
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=6)
rownames(MAT) <- items
colnames(MAT) <- c("mckessonOne","mckessonTwo","autostarOne","rmsOne","xifinOne","pciAudit")
lapply(seq_along(summaryList),function(i) { MAT[items %in% summaryList[[i]],i] <<- table(summaryList[[i]])})
v <- venneuler(MAT)
plot(v)
savehistory("/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/origianl_venn_fixed.Rhistory")
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
summaryList = list(mckessonOne,mckessonTwo,autostarOne,rmsOne,xifinOne,instaMedOne,pciAuditList)
items <- sort(unique(unlist(summaryList)))
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=6)
MAT <- matrix(rep(0,length(items) * length(summaryList)),ncol=7)
colnames(MAT) <- c("mckessonOne","mckessonTwo","autostarOne","rmsOne","xifinOne","instaMedOne",pciAudit")
""
colnames(MAT) <- c("mckessonOne","mckessonTwo","autostarOne","rmsOne","xifinOne","instaMedOne", "pciAudit")
rownames(MAT) <- items
lapply(seq_along(summaryList),function(i) { MAT[items %in% summaryList[[i]],i] <<- table(summaryList[[i]])})
v <- venneuler(MAT)
plot(v)
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
savehistory("/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/working_venn_fixed.Rhistory")
co <- intersect(pciAuditList,allOriginal)
co
co <- intersect(list(unlist(pciAuditList)),list(unlist(allOriginal)))
length(co)
print co
co
co <- intersect(pciAuditList,list(unlist(allOriginal)))
co
allOriginal
items <- list(sort(unlist(allOriginal)))
print items
items
co <- intersect(pciAuditList,items)
co
clear
source('/Volumes/d_other/Mayo_Rochester/Cyber_IT/docs/reports/2015-05-pci-found-systems/lists.R')
co <- intersect(pciAuditList,autostarOne)
co
items <- list(sort(unlist(allSoftware)))
items
co <- intersect(pciAuditList,items)
co
items
items <- sort(unlist(allSoftware))
item
items
co <- intersect(pciAuditList,items)
length(co)
install_packages("VennDiagram")
install.packages("VennDiagram")
draw.pairwise.venn(length(pciAuditList)+length(items),length(pciAuditList),length(intersect(pciAuditList,items)))
draw.pairwise.venn(length(pciAuditList),length(items),length(intersect(pciAuditList,items)))
items <- sort(unlist(allPatterns))
draw.pairwise.venn(length(pciAuditList),length(items),length(intersect(pciAuditList,items)),c("PCI Audit","All Patterns"))
savehistory("~/New_venn_process.Rhistory")
