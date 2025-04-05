# Quantower C# Template Library

This repository contains ready-to-use **strategy** and **indicator** templates for the [Quantower](https://quantower.com/) trading platform, written in C#.

## 📁 Folder Structure

- `Strategies/` — Custom trading strategies (entry, exit, trailing logic)
- `Indicators/` — Custom indicators for charting and signals
- `strategy_index.md` — Summary of each file and its purpose

## 🔧 Base Templates

- [`StrategyTemplate.cs`](Strategies/StrategyTemplate.cs): Scaffold for writing new strategies
- [`IndicatorTemplate.cs`](Indicators/IndicatorTemplate.cs): Starting point for new indicators

## 📚 Strategy Examples

- [`RSI_CrossStrategy.cs`](Strategies/RSI_CrossStrategy.cs): Entry on RSI cross above/below key levels
- [`MACD_Breakout.cs`](Strategies/MACD_Breakout.cs): Entry on MACD histogram breakouts
- [`ATRTrailingStop.cs`](Strategies/ATRTrailingStop.cs): Trailing stop based on ATR values

## 📈 Indicator Examples

- [`SuperTrendIndicator.cs`](Indicators/SuperTrendIndicator.cs): Trend-following indicator with dynamic levels
- [`VWAPCustom.cs`](Indicators/VWAPCustom.cs): Custom volume-weighted average price

---

## 🧠 Usage with ChatGPT or GPT API

You can reference this repo in your prompts:

> "Use `StrategyTemplate.cs` from my GitHub repo as a base for a new EMA crossover strategy."

Or combine logic from multiple files:

> "Merge entry logic from `RSI_CrossStrategy.cs` with trailing stop logic from `ATRTrailingStop.cs`."

---

