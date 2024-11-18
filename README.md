Twitter Sentiment Analysis and Rephase by John O'Dell

You will need 
    - pip PyCharm
    - pip AutoTokenizer
    - An OpenAi API https://openai.com/api/
    - Roberta Model https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest


Tweet - Our Tweet Takes into Consideration
    - Text
    - Emojis
It will null out
    - any @ or #
    - any hyper links

First input your tweet and run it through the model to get a "Sentiment Score", then a prompt is sent to OpenAi to rephrase the tweet in a more Positive maner for a higher positive sentiment score.

By adding the final printed statement to a the tweet[] index, the rephrased tweet can be ran again for a more positive more score.

The rephrasal can be changed by "Rephrase this more ______," with another keyword.

If pycharm isnt working try using the "conda" command instead on "pip"
