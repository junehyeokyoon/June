##  June Hyeok Yoon
**Ph.D. Student in Poultry Science (Broiler Nutrition)**  

University of Georgia  

📧 Email: [junehyeokyoon@ncsu.edu](mailto:junehyeokyoon@uga.edu)  
🔗 [Google Scholar](https://scholar.google.com/citations?user=FwQUdD4AAAAJ&hl=en&authuser=1) · 
[LinkedIn](https://www.linkedin.com/in/jeonghyeon-son-107a10246/)

---

## 🎓 Education
- **Ph.D. in Animal Science**  
  North Carolina State University, Raleigh, NC, Jan 2025–Present  

- **M.Sc. in Animal Science**  
  Konkuk University, Seoul, South Korea, Aug 2023  

- **B.Sc. in Animal Science and Technology**  
  Konkuk University, Seoul, South Korea, Aug 2021  

---
## 🔬 Research Interests
- Precision nutrition in swine  
- Nutrient digestibility, availability, and requirement modeling  
- Nutritional interventions and microbiome analysis for intestinal health  


---
## 📚 Publications
**Latest Publications:**
{% assign pubs = site.data.publications | where: "status", "published" | sort: "year" | reverse %}
{% assign pub_total = pubs | size %}
{% for pub in pubs limit:3 %}
- **{{ pub_total | minus: forloop.index0 }}.** {{ pub.authors | replace: 'Son J', '<strong>Son J</strong>' }}. {{ pub.year }}. {{ pub.title }}. *{{ pub.journal }}*{% if pub.volume %} {{ pub.volume }}{% endif %}{% if pub.pages %}:{{ pub.pages }}.{% endif %}{% if pub.link %} [🔗]({{ pub.link }}){% endif %}
{% endfor %}

[**View All Publications →**](/publication/)
