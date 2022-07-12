# Stock Screening with 《社畜的財務自由計畫》 by 遊牧民

Our target is to use data API to screen stock with the method in the book, sharp volume rise, following with a volume drop.
Laterly we may introduce some screening criteria with price / 3,5 EMA.

We break it down into 2 step :
- Day 1 we screen out all stocks that have a volume rise more than *500%*, forming a potential stock list
- Day 2 we screen only the potential stock list, and look for stock that have volume drop to *25% or less*.

