# Exploratory Data Analysis Pokemon 

An in-depth exploration of Pokemon stats, types, and legendary status using Python & Statistical Analysis.

### DataFrame.head(5) -
	#	Name	Type 1	Type 2	Total	HP	Attack	Defense	Sp. Atk	Sp. Def	Speed	Generation	Legendary
0	1	Bulbasaur	Grass	Poison	318	45	49	49	65	65	45	1	False
1	2	Ivysaur	Grass	Poison	405	60	62	63	80	80	60	1	False
2	3	Venusaur	Grass	Poison	525	80	82	83	100	100	80	1	False
3	3	VenusaurMega Venusaur	Grass	Poison	625	80	100	123	122	120	80	1	False
4	4	Charmander	Fire	NaN	309	39	52	43	60	50	65	1	False

## 📌 Project Overview
The goal of this project was to analyze the characteristics of 800+ Pokemon to identify patterns in combat stats and type distributions. This analysis helps understand the "meta-game" balance and identifies which features contribute most to a Pokemon's "Legendary" status.

## 📊 Key Insights
* **Type Dominance:** Water and Normal types are the most common, while Ice and Ghost types remain the rarest.
* **Average Total Power by Type: Dragon with high average strength but with high Standard Deviation**
* <img width="598" height="379" alt="Screenshot 2026-01-12 at 16 35 06" src="https://github.com/user-attachments/assets/34d8292c-acb1-4dbe-af2b-32678ac63a11" />

* **The Power Gap:** Legendary Pokemon have an average Total Base Stat significantly higher (~600) than non-legendary Pokemon (~400).
* **Correlation map of strengths: **
* <img width="622" height="497" alt="Screenshot 2026-01-12 at 16 37 03" src="https://github.com/user-attachments/assets/0b1132cd-a35a-4d79-806f-257237a10759" />


* **Stat Correlations:** There is a strong positive correlation between Defense and Special Defense, but a surprising lack of correlation between Speed and Weight.
* **Attack Distribution Water Vs fire :**
* <img width="622" height="401" alt="Screenshot 2026-01-12 at 16 38 22" src="https://github.com/user-attachments/assets/64aecc07-8c0e-45f7-bd5b-70e6538570be" />

* **Generational Shift:** Generation 1 has the highest variance in stats, while later generations show more balanced distributions.

## 🛠️ Tools & Technologies
* **Python** (Pandas, NumPy)
* **Statistical Analysis**
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Kaggle Notebooks

## 📂 Data Source
The data was sourced from the [Kaggle Pokemon Dataset](https://www.kaggle.com/datasets/abcsds/pokemon). It includes stats like HP, Attack, Defense, Speed, and Type for all Pokemon across 7 Generations.

## 🚀 How to View
1. Open .ipynob file directly here on GitHub to see the rendered code and charts.
2. Or, [View the Interactive Notebook on Kaggle](https://www.kaggle.com/code/vineetchopra/eda-pokemon-dataset).

