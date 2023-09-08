# semantic-search
experiment and learn about vector embeddings and semantic search

Ideas
* explore how mathematica properties map to different semantics: dot product, cosine similarity, euclidian distance, single dimension distance, subtracted directions (old face - young face), arbitrary distance metrics, learnable distance metrics?
* how does content effect embedding on these metrics? Stating a fact as a question versus as an answer. describing something versus asking for something, filler words meant to indicate you are requesting a search for example "you know that song that... ", "I don't remember the name of the restaurant just that it had fried artichokes that were really crispy and swordfish and I think it was meditteranean...". Understanding ordering, ranking, counting: "I want a house that has stainless steel appliances, but that's less important than having a big kitchen with an island because I can always replace the appliances if I need to...".
* Understanding how to connect relevant information.... tree summarization of large corpuses of documentation or databases. Summarize this paragraph, summarize this page, summarize this chapter, summarize this book (root). At each node test for relevance and explore relevant children if relevant.
* Understand how a piece of code is embedded versus the comments/docs describing that code
* find directions of maximum change... eigen-directions.... but how can you seperate variation with semantic variation??? how to extract semantic eigen directions? Can you potentially combine LLMs systems that have an understanding of semantics to get a grasp on this? Dallee somehow was able to inject semantic understanding into images using llms. The llms must already have these directions maybe eigen directions will actually already be fine, i havn't tried that with natural language.


Resources:
* Maybe BS course on semantics: https://www.deeplearning.ai/short-courses/large-language-models-semantic-search/
* Scrape Zillow home listings: https://scrapfly.io/blog/how-to-scrape-zillow/
* ImageBind Representation: https://arxiv.org/abs/2305.05665 , https://imagebind.metademolab.com/
* Code Llama: https://about.fb.com/news/2023/08/code-llama-ai-for-coding/
* Boilerplate: https://drivendata.github.io/cookiecutter-data-science/
