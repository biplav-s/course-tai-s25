<em> **See also** : 
readings in [AI and NLP](https://github.com/biplav-s/course-tai-s25/blob/main/reading-list/Readme-AI-NLP.md) and [AI Trust](https://github.com/biplav-s/course-tai-s25/blob/main/reading-list/Readme-Trust.md) </em>

---

1. Introducing word representation 
> 1. Noah A. Smith, [Contextual Word Representations: Putting Words into Computers](https://cacm.acm.org/magazines/2020/6/245162-contextual-word-representations/fulltext), Communications of the ACM, June 2020, Vol. 63 No. 6, Pages 66-74
10.1145/3347145 


2. Language models
> 1. Hang Li, [Language Models: Past, Present, and Future](https://cacm.acm.org/magazines/2022/7/262080-language-models/fulltext), Communications of the ACM, July 2022, Vol. 65 No. 7, Pages 56-63
10.1145/3490443
> 2. [A Primer in BERTology: What We Know About How BERT Works](https://aclanthology.org/2020.tacl-1.54) (Rogers et al., TACL 2020)
> 3. Blogs explaining LLM concepts
> > a. Training LLMs and related concepts - [The Novice's LLM Training Guide](https://rentry.org/llm-training).
> > 
> > b. Estimating computing cost of LLM training - [Transformer Math 101](https://blog.eleuther.ai/transformer-math/), in EleutherAI Blog, Apr 2023.
> > 
> > c. Understanding Transformers - [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
> > 
> 4. Large Language Model (LLM) size, performance and resource needs 
> > a. Trade-offs - [In AI, is bigger always better?](https://www.nature.com/articles/d41586-023-00641-w), March 2023.

> > b. "22 times lesser energy thar regular LLM"  - [SpikeGPT: researcher releases code for largest-ever spiking neural network for language generation](https://news.ucsc.edu/2023/03/eshraghian-spikegpt.html), March 2023

> > c. How  to choose LLMs - [The Practical Guides for Large Language Models](https://github.com/Mooler0410/LLMsPracticalGuide), April 2023


3. Language, language models and human understanding
> 1. [AI And The Limits Of Language](https://www.noemamag.com/ai-and-the-limits-of-language/),  Jacob Browning and Yann LeCun, Aug 2022. _Argues that not all human knowledge is in text, and so, any AI trained on it will struggle_.
> 2. Weidinger, Laura, et al., [Taxonomy of Risks posed by Language Models](https://dl.acm.org/doi/10.1145/3531146.3533088), 2022 ACM Conference on Fairness, Accountability, and Transparency.
> 3. [Mission: Impossible Language Models](https://aclanthology.org/2024.acl-long.787/), Julie Kallini, Isabel Papadimitriou, et al, ACL 2024. _Creates impossible languages and sees how GPT-2 performs on them. Implication for grammards and language learning._


4. LLMs and Various Technical Aspects
> a. Hallucination
> > 1. [GPTs and Hallucination- Why do large language models hallucinate?](https://cacm.acm.org/practice/gpts-and-hallucination/),  Jim Waldo and Soline Boussard, Dec 2024. _Explains the concept of truth in philosophy, how we express in languages, LLMs, and why their output will always have made-up content (hallucination)_.
> > 2. [The Troubling Emergence of Hallucination in Large Language Models - An Extensive Definition, Quantification, and Prescriptive Remediations](https://aclanthology.org/2023.emnlp-main.155/), EMNLP 2023. _Describes hallucination types_.

> b. Synthetic data and impact on LLMs
> > 1. [AI models collapse when trained on recursively generated data](https://www.nature.com/articles/s41586-024-07566-y), Nature, 2024. _Explains model collapse when GenAI's data is used for further training_.


> c. LLMs and reasoning
> > 1. [Can Large Language Models Reason and Plan?](https://arxiv.org/html/2403.04121v1), S. Kambhampati 2024. _Explains LLMs properties with respect to reasoning and planning_.
> > 2. 

> d. Prompting resources
> > 1. [A guide with description about prompting techniques](https://www.promptingguide.ai/introduction)
> > 2. [The Prompt Report: A Systematic Survey of Prompting Techniques](https://arxiv.org/abs/2406.06608), June 2024 (revised Feb 2025). _A comprehensive survey of prompting approaches across LLM types_.
> > 3. [Promptify](https://github.com/promptslab/Promptify) - a Python library to automate creating prompts and getting structured results
> > 4. [AISuite](https://github.com/andrewyng/aisuite) - a Python library providing interface to multiple LLMs for prompting and getting responses
   
---

5. [ChatGPT](https://openai.com/blog/chatgpt/), from OpenAI - LLM for dialogs
>  a. About the technology
>  > 1. [The Brilliance and Weirdness of ChatGPT](https://www.nytimes.com/2022/12/05/technology/chatgpt-ai-twitter.html) [NY Times, Dec 2022]
 > > 2. [ChatGPT is 'not particularly innovative,' and 'nothing revolutionary', says Meta's chief AI scientist](https://www.zdnet.com/article/chatgpt-is-not-particularly-innovative-and-nothing-revolutionary-says-metas-chief-ai-scientist/) [Yann LeCun, Jan 2023]
 > > 3. [ChatGPT is not all you need. A State of the Art Review of large Generative AI models](https://arxiv.org/abs/2301.04655) [Jan 2023]
 > > 4. [Working with ChatGPT-like LLM-based-AIs Reliably: Don’t Look at Only the Technology Pillar For All The Answers](https://www.linkedin.com/pulse/working-chatgpt-like-llm-based-ais-reliably-dont-look-srivastava/) [Biplav Srivastava, Jan 2023]. _Argues that beyond technology, user education, regulation and standards are need to mature any technology, and now AI_
 > > 5. [Will ChatGPT supplant us as writers, thinkers?](https://news.harvard.edu/gazette/story/2023/02/will-chatgpt-replace-human-writers-pinker-weighs-in/) [Steven Pinker, Feb 2023]
 > > 6. [Beauty, lies & ChatGPT: Welcome to the post-truth world](https://thehill.com/opinion/technology/3861182-beauty-lies-chatgpt-welcome-to-the-post-truth-world/) [Subbaro Kambhampati, Feb 2023]. _Says that ChatGPT can help in framing search questions but cannot link to data source to prove results truthfulness._
 > > 7. Technical details
   
 > > > * ChatGPT: [What It Can and Cannot Do](https://www.youtube.com/watch?v=ORoTJZcLXek), video by Prof. Pascale Fung [March 2023]

 > > > * The specification of GPT, called [Model Spec](https://openai.com/index/introducing-the-model-spec/). Explains what the intent of OpenAI's models are. [May 8, 2024]

 > b. Impact: Passing tests and societal implications
 > > 1. Business - [ChatGPT passes MBA exam given by a Wharton professor](https://www.nbcnews.com/tech/tech-news/chatgpt-passes-mba-exam-wharton-professor-rcna67036) [Passing test with B grade at Wharton, Jan 2023]
 > > 2. Laws - [ChatGPT passes exams from law and business schools](https://www.cnn.com/2023/01/26/tech/chatgpt-passes-exams/index.html) [Jan 2023]
 > > 3.  [How Smart Are the Robots Getting?](https://www.nytimes.com/2023/01/20/technology/chatbots-turing-test.html) [Chatbots and Turing test, NY Time, Jan 2023]
 > > 4. Real Estate - [Real estate agents say they can’t imagine working without ChatGPT now](https://www.cnn.com/2023/01/28/tech/chatgpt-real-estate/index.html)  [Real-estate industry and ChatGPT, Jan 2023]
 > > 5. Previous chatbots and what's new with new chatbots - [How Siri, Alexa and Google Assistant Lost the A.I. Race](https://www.nytimes.com/2023/03/15/technology/siri-alexa-google-assistant-artificial-intelligence.html) [Comparison, March 2023]
 > > 6. Civil Services - [ChatGPT fails prestigious Indian civil service test](https://www.globalgovernmentforum.com/chatgpt-fails-prestigious-indian-civil-service-test-us-works-to-streamline-citizen-experience-policy-delivery-news-in-brief/) [March 2023]
 > > 7. Banks - [AI Chatbots Are Causing Bank Customers Headaches](https://www.cnet.com/personal-finance/ai-chatbots-are-causing-bank-customers-headaches/) [Consumers complaining about Bank Chatbots to Consumer Financial Protection Bureau in US, June 2023]
 > > 8. [Does ChatGPT have a liberal bias?](https://www.aisnakeoil.com/p/does-chatgpt-have-a-liberal-bias)[Exploring bias of text generated, Aug 2023]

 > c. Case Studies and Errors of ChatGPT/ language models
 > 1. [Large Language Models like ChatGPT say The Darnedest Things](https://garymarcus.substack.com/p/large-language-models-like-chatgpt) [A collection of mistakes by LLMs]
 > 2. [ChatGPT mistakes](https://github.com/giuven95/chatgpt-failures) [A GitHub of mistakes]
 > 3. [Case studies with LLMs](https://github.com/ai4society/LLM-CaseStudies) - [Finance](https://github.com/ai4society/LLM-CaseStudies/tree/main/Finance)  [Detailed examples in industries]

---

6. [Llama](https://www.llama.com/), from Meta - open weight (source) LLM. 
 > a. [Forbes article](https://finance.yahoo.com/news/mark-zuckerberg-went-meta-major-103000635.html) on strategy of open sourcing, Nov 2024
 > 
 > b. [Llama 3 blog](https://ai.meta.com/blog/meta-llama-3/) - overall description.
 > 
 > c. [Comparison of Llama3 with Llama2](https://www.apps4rent.com/blog/llama-3-vs-llama-2/), by Apps2Rent

---
7. [DeepSeek R1](https://www.deepseek.com/), from DeepSeek - open weight (source) LLM. 
 > a. A point-of-view [(POV)](https://drive.google.com/file/d/1ErR1xT7ftvmHiUyYrdUbjyd4qCK_FxKX/view?usp=sharing) from [AI for Society](https://ai4society.github.io/) (Feb 2, 2025). 

