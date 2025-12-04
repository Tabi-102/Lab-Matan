# Динамические системы – Лабораторная работа  
**Dynamical Systems – Laboratory Work (ITMO University)**

---

## 1. Введение

Цель лабораторной работы – **изучение дискретных динамических систем** через точечные отображения, включая:

- **Логистическое отображение (logistic map)**
- **Паутинные диаграммы (cobweb plot)** для визуализации последовательностей
- **Бифуркационные диаграммы (bifurcation diagram)**
- **Показатель Ляпунова (Lyapunov exponent)** для анализа хаоса
- **Численные эксперименты и визуализации**

> «Мы живем на острове, окруженном морем невежества. По мере роста острова нашего знания растет и берег нашего невежества.»

Лабораторная работа использует знания **Математического анализа 1**: пределы, последовательности, непрерывность, производные, неподвижные точки и их устойчивость.

---

## 2. Структура репозитория
```text
lab-matan/
├── README.md
├── notebooks/
│   ├── lab_easy.ipynb
│   ├── lab_normal.ipynb
│   └── lab_hard.ipynb
├── src/
│   ├── maps.py
│   ├── plotting.py
│   └── utils.py
├── results/
│   └── images/
├── report.pdf
├── .gitignore
└── requirements.txt
```

## 3. Установка

1. Клонируем репозиторий:
```bash
git clone https://github.com/Tabi-102/Lab-Matan.git
cd Lab-Matan
```
2. Создаем виртуальное окружение Python (рекомендуется):
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
3. Устанавливаем необходимые библиотеки:
```bash
pip install -r requirements.txt
```
