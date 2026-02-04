# 🏭 Manufacturing Performance Analytics

---

## 📌 Kontext
Tento projekt simuluje výrobní prostředí ve středně velkém výrobním podniku.  
Data reprezentují výrobní linky, směny, prostoje, poruchy, kvalitu výroby a výkon jednotlivých pracovišť.

Projekt je zaměřen na analytické vyhodnocení efektivity výroby a identifikaci provozních problémů.

---

## 🎯 Cíl projektu
- analyzovat výkonnost výrobních linek
- identifikovat bottlenecky
- vyhodnotit prostoje a jejich příčiny
- vytvořit KPI reporting
- navrhnout datový model pro reporting

---

## 🧠 Business otázky
- Které linky mají nejnižší efektivitu?
- Jaké jsou hlavní příčiny prostojů?
- Kde vznikají bottlenecky?
- Jaký je rozdíl mezi směnami?
- Jaká je skutečná produktivita oproti plánům?

---

## 🗂 Datové zdroje
Simulovaná a anonymizovaná výrobní data:
- výroba
- směny
- operátoři
- poruchy
- plánování
- kvalita

Formát: CSV

---

## 🧱 Datový model

### Faktové tabulky:
- production_fact
- downtime_fact
- quality_fact

### Dimenzní tabulky:
- time_dim
- line_dim
- operator_dim
- shift_dim
- machine_dim

---

## 🔄 Datový tok

