To create your own AI chatbot on a website, I used Meow Apps plug in for wordpress. This plug in allowed me to install this directly on to a website for the public to use. WHenever you use the AI Chatbot it uses the OpenAI API to function via OpenAI's ChatGPT. To make my model custom I gave it a set of instructions about what the websitre is for. This way, the Chatbot serves as a FAQ bot. In theory you can make a GPT using AI for another purpose like as a digital service, but this GPT serves as a FAQ bot for now. You can implement multiple GPT's within the same website with MeowApps.

What I learnt was that the longer the instructions are, the more input tokens the GPT will cost. To make the GPT cost effective I tested it with the ChatGPT 3.5 Turbo model. With this, a single prompt resulted in a few hundred input tokens and roughly 100 output tokens on average.

A potential solution to this issue looking forward would be to finetune the model by training it on word documents that have all of your instructions on it. This way your instructions would be much less in size and therefore cost less input tokens. The longer the instructions on the AI engine, the more the input tokens the AI will use.

UPDATE: There is a feature called 'finetune model' under Meow Apps > AI Engine > Server Modules
