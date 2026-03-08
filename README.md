# Systematic-trading-researchSystematic Trading Strategy Research

This repository contains research on rule-based FX trading strategies using Python.

The goal of this project is to explore systematic strategies capable of generating stable, risk-adjusted returns across currency pairs.

Research Workflow

The strategy testing framework includes:

historical data collection

indicator calculation

rule-based strategy design

parameter sweeps

automated backtesting

trade-level performance analysis

Current Strategy

MACD + EMA Momentum Model

Strategy logic:

Entry

MACD crossover

price above EMA trend filter

Exit

opposite signal or momentum reversal

Key Findings

best parameters identified through parameter testing

win rate approximately 56%

strongest performance on GBP and JPY pairs

Tools

Python
Pandas
Jupyter Notebook
