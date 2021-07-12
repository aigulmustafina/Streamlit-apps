import yfinance as yf
import streamlit as st
import pandas as pd

st.write("""
# Simple Stock Price App
Shown are the stock closing price and volume of Google!

""")

tickerSymbol = 'GOOGL'
tickerData = yf.Ticker(tickerSymbol)
tickerDf = tickerData.history(perid = 'id', start = '2010-5-31', and = '2010-5-31')
st.line_chart(tickerDf.Close)
st.line_chart(tickerDf.Volume)
