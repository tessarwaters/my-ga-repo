When I was brainstorming for my final General Assembly project I knew I wanted to challenge myself to implement new concepts as well as those I learned throughout the course. But first I needed an idea:

The idea stemmed from my personal interests. My background is in biology - particularly ecology/climate science. The biggest takeaway I have from my experience in scientific research is the absolute necessity for a greener economy. To mitigate climate change, governments, businesses, and individuals need to boost investments in clean energy to drastically reduce carbon emissions. For this reason, I decided to look into clean energy ETFs for my project.

ETFs (Exchange-traded fund) are "a collection of securities that can be bought and sold in shares on a stock exchange just like an individual stock" (TheStreet). Investing in ETFs focused on clean energy allows investors to flow money into the alternative energy sector at a low risk.

I decided to pull data from the top clean energy ETF: iShares Global Clean Energy ETF (NASDAQ:ICLN). This ETF "focuses on global companies that produce energy from solar, wind, and other renewable energy sources" (The Motley Fool). After learning about Time Series at GA, I was interested in exploring how the results of the fund may be influenced by exogenous factors such as media coverage on climate change/renewable energy.

That's when I decided to turn to the New York Times. The NYT has an excellent article archive API that lists every article published per day since 1851. Using the NYT allowed me to explore topic modeling and eventually determine the best way to extract all the articles published that relate to climate change.

Since the iShares Global Clean Energy ETF is only a little over a decade old, I decided to extract ETF and NYT data from the last 10 years. Using shares volume and article counts per day my first goal was to answer the question:

Does a clean energy ETF's volume rise when there is more media coverage of issues surrounding climate change?

My second goal was to then create a Time Series model that could predict ETF volume with climate change article number included as an imposed variable.

Enjoy the journey of how I developed my model! (see Waters_Theresa_Capstone)
