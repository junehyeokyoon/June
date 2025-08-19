## 🐔 June Hyeok Yoon
**Ph.D. Student in Broiler Nutrition**  

Department of Poultry Science, University of Georgia  

📧 Email: [junehyeokyoon@uga.edu](mailto:junehyeokyoon@uga.edu)  
🔗 [Google Scholar](https://scholar.google.com/citations?user=1JO24ZIAAAAJ&hl=ko&oi=ao) · 
[LinkedIn](https://www.linkedin.com/in/june-hyeok-yoon-305573238/)

---

## 🎓 Education
- **Ph.D. in Poultry Science**  
  University of Georgia, Athens, GA, Aug 2024–Present  

- **M.Sc. in Animal Science**  
  Kyungpook National University, Sangju, South Korea, Feb 2024  

- **B.Sc. in Animal Science and Technology (Minor in Chemistry)**  
  Konkuk University, Seoul, South Korea, Feb 2022  

---
## 🔬 Research Interests
- Precision nutrition in swine  
- Nutrient digestibility, availability, and requirement modeling  
- Nutritional interventions and microbiome analysis for intestinal health  

---
## 🏆 Award
- **Poultry Science Association] Certificate of Excellence for oral presentation**

---
## 📚 Publications
**Latest Publications:**
{% assign pubs = site.data.publications | where: "status", "published" | sort: "year" | reverse %}
{% assign pub_total = pubs | size %}
{% for pub in pubs limit:3 %}
- **{{ pub_total | minus: forloop.index0 }}.** {{ pub.authors | replace: 'Son J', '<strong>Son J</strong>' }}. {{ pub.year }}. {{ pub.title }}. *{{ pub.journal }}*{% if pub.volume %} {{ pub.volume }}{% endif %}{% if pub.pages %}:{{ pub.pages }}.{% endif %}{% if pub.link %} [🔗]({{ pub.link }}){% endif %}
{% endfor %}

[**View All Publications →**](/publication/)
