# FinAgent
LLM Agents to compete between themselves in a basic market simulation.

In this repositery we define a playground for several AI agents to trade betwen each others and analyse the results associated. 
An extension can be made in which one person could play a trading game vs LLM Agents. 

**Rules** 

We define n assets and m llm agents.

The game is played in round, at each round each LLM agent knows its inventory and past prices streamed by other agents.
Using this information each agents stream prices they are willing to buy and sell each asset.
Once each agent is aware of other agents prices each agent propose a quantity for each assets they want to buy and sell from other agents.

After each round agents update their cash and inventory and another round is kicked off.

The goal of this project is to see if LLM agents framed as traders can take rationnal trading decisions and end up maximizing their profits.

<img width="1161" alt="image" src="https://github.com/reda-arab/FinAgent/assets/59368670/7915c446-c2c0-4b9b-bdc3-7a1313a6039d">

Setting Up FinAgent:

pip install -r requirements.txt

You should set your Mistral API Key 
