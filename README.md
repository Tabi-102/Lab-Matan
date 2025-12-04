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
lab-dynamics/
├── README.md # Описание проекта (этот файл)
├── notebooks/ # Jupyter notebooks для каждого уровня
│ ├── lab_easy.ipynb
│ ├── lab_normal.ipynb
│ └── lab_hard.ipynb
├── src/ # Повторно используемый код Python
│ ├── maps.py # Функции отображений, итераторы, устойчивость, Lyapunov
│ ├── plotting.py # Функции построения cobweb, bifurcation, time series
│ └── utils.py # Утилиты
├── results/
│ └── images/ # Сгенерированные графики
├── report.pdf # Основной отчет (PDF из notebook или LaTeX)
├── .gitignore # Игнорируемые файлы

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
