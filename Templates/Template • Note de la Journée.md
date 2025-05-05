# ✅ Missions du jour
---
##### Je dois :
- [ ] 

##### Je devrais :
- [ ] 

##### J'aimerais : 
- [ ] 
# 📕 Journal de bord
---
- 


# 📝 Notes crées aujourd'hui
---
```dataview
List FROM "" 
WHERE file.cday = date("<% moment(tp.file.title,'YYYY-MM-DD').format('YYYY-MM-DD') %>")  & file.name != this.file.name
SORT file.ctime desc
```