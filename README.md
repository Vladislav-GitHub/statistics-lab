# 📊 Statistics Lab

Интерактивная образовательная платформа для изучения статистики, вероятности, A/B тестирования и Monte-Carlo симуляций.

![React](https://img.shields.io/badge/React-18.3-61dafb)
![Vite](https://img.shields.io/badge/Vite-5.0-646cff)
![Tailwind](https://img.shields.io/badge/Tailwind-3.0-38bdf8)

## 🌐 Демо

**Сайт доступен по адресу:**  
👉 [https://vladislav-github.github.io/statistics-lab/](https://vladislav-github.github.io/statistics-lab/)

## 🎯 Возможности

### 1. Distribution Explorer (Real-time Sliders)
- Интерактивные слайдеры для параметров распределений
- Mean, Variance, Sample Size, Confidence Level
- PDF график обновляется в реальном времени
- Гистограмма выборочных данных
- Доверительные интервалы

### 2. Monte-Carlo Simulator
- **Sampling Distribution** - анимация выборочного распределения
- **Central Limit Theorem** - визуализация CLT
- **Bootstrap** - бутстреп распределение средних
- **Convergence** - сходимость выборочного среднего к генеральному

### 3. A/B Testing Simulator
- Интерактивное A/B тестирование
- Real-time p-value, confidence intervals
- Power analysis и effect size
- Uplift расчет
- Significance detection

### 4. Interactive Distributions
- 6 распределений: Normal, Poisson, Beta, Gamma, Student, Weibull
- Интерактивные параметры (α, β, λ, μ, σ)
- Real-time PDF графики

### 5. Hypothesis Tests
- t-test, Welch test, Mann-Whitney, ANOVA
- Расчет p-value и test statistic
- Кнопка Randomize для генерации данных

## 🛠️ Технологии

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Deploy**: GitHub Pages

## 🚀 Локальный запуск

```bash
# Клонировать репозиторий
git clone https://github.com/Vladislav-GitHub/statistics-lab.git

# Перейти в папку проекта
cd statistics-lab

# Установить зависимости
npm install

# Запустить dev сервер
npm run dev

# Открыть в браузере
# http://localhost:5173/statistics-lab/
