#Sentiment Analysis For Financial Markets
Unlock smarter investments with real-time sentiment analysis. Our website uses financial news to give clear buy/sell recommendations instantly!

##Problem & Motivation
Investors share a universal challenge: the fear of leaving money on the table. Timing the market when buying or selling stocks is notoriously difficult, largely because understanding market sentiment in real time is both complex and resource-intensive. This challenge compels analysts and investors to pour significant time, effort, and money into deciphering the ever-changing opinions and expectations of other market participants.

Despite these efforts, existing platforms like Robinhood, Bloomberg Terminal, and other tools often fall short. They either overwhelm users with excessive information, come with steep costs, or focus on long-term stock movements, which may not align with the needs of short-term decision-makers.

##The Solution
Our website offers a streamlined and highly efficient solution by harnessing the power of deep learning and natural language processing (NLP) techniques to analyze sentiment from real-time financial news, social media platforms, and earnings reports. Unlike conventional tools, it is specifically designed to predict short-term stock movements, providing clear and actionable insights into whether a stock is likely to move up or down in the near term.

Users can easily select their stocks of interest to receive personalized buy or sell recommendations based on the latest sentiment trends. Additionally, they can create and manage a portfolio to monitor multiple stocks worth considering simultaneously. This focused and intuitive approach simplifies the decision-making process, saving time and reducing the mental load for both individual and institutional investors.

What sets our website apart is its cost-effectiveness, user-friendly interface, and dedicated focus on short-term trading. Unlike existing platforms that may overwhelm users with excessive information, incur high subscription costs, or cater primarily to long-term strategies, our website prioritizes simplicity and actionable insights. It bridges the gap between cutting-edge analytics and practical investment needs, empowering users to make confident decisions and stay ahead in an increasingly competitive market.

###To test out:
curl -k -X POST -H "Content-Type: application/json" -d '{ "stock_symbol": "AAPL" }' https://3.15.173.177:5001/predict

stock_symbol can be any of the following: Boeing (BA), Merck (MRK), Intel (INTC), Microsoft (MSFT), AMD (AMD), NVIDIA (NVDA), Tesla (TSLA), Alphabet (GOOG), and Apple (AAPL).
