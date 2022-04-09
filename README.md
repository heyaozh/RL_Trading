# RL_Trading
Personal Project of Reinforcement Learning Trading






Dear Alex and Xinzhuo,

First of all, thank you very much for your time today and your compliment and advice on my project. 

As we discussed, I attached two papers I mentioned: market-making using reinforcement learning and generating realistic order flows using GAN. These are two candidate topics for my master’s thesis and I am working on them to decide one by the end of this month (our team is interested in the latter one very much).

Another paper attached might also be interesting for you, which shows how the agent or (general neural network based trading algo) can be reverse-engineered and attacked. This is a hot topic in the computer vision area, especially the self-driving car: what the computer sees can be attached by changing a single pixel.

There is some other research in my mind that you might be interested in, such as using a convolutional layer as a filter (like Kalman filter), using GAN and MCMC (Markov-Monte-Carlo-Chain) to do the forecasting, etc. I hope I could have the chance (data and computational power) to implement all those. I’ll share you next time if you like.

I will continue my work on the following points:
1.	Use all stocks available, consider data until yesterday, remove benchmark, and use the factors in the list before glb30.
2.	Use a long-short strategy, make it delta-neutral and sector-neutral. Here I was thinking to give the short side an opportunity cost (like borrowing cost) assuming a close-to-risk-free rate.
3.	Introduce an absolute portfolio value and number of stocks (not just weights anymore)
4.	Introduce transaction cost. I think the more volume traded, the more transaction cost should be (some implied costs can happen as well for large transactions), could you suggest a non-linear function that can approximately achieve this? (I’ll start with constant cost as a portion of the volume traded.)

As you suggested, I’ll do it for 24 sectors one by one and see how it works, but it takes time.

I suppose this can already be a topic for a master thesis…

Again, it was a great pleasure to meeting you, and I look forward to our next meeting after some time. 😊 Have a nice week and stay safe!

Cheers,
Yao
