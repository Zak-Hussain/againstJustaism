## A rebuttal of two common deflationary stances against LLM cognition

This repository accompanies the paper:

Hussain, Z., Mata, R., & Wulff, D. U. (in press). A rebuttal of two common deflationary stances against LLM cognition. *Findings of the Association for Computational Linguistics: ACL 2025*, XX, XX.

It collects references to "Justaism" (pronounced "just-a-ism"), a term [coined](https://scottaaronson.blog/?p=7784) by Scott Aaronson to (pejoratively) refer to unsubstantiated deflationary claims made by skeptics that LLMs are "just...": "next-token predictors", "function approximators", or "stochastic parrots", and thus lack some
essential cognitive capacities that humans possess.

### Instances of Justaism

**Note:** The following will vary in their level of deflationism, question-beggingness, and general Justaic strength. To aid in 
conveying this diversity, we have included a Justaism strength rating ("strong", "moderate", "weak") in square brackets 
for each instance. These ratings are based not just on the quote itself, but also on the broader context in which it was made.

#### Academic Articles/Preprints:

"The widespread enthusiasm for LLMs should be tempered by an awareness that they are not actually simulating human intelligence [29,32,33]. LLMs simply predict the next phrase or sentence, given what they have been exposed to in the training data. Consequently, they tend to output an ‘average’ of what the internet or popular books tend to say"<br>
[Demszky et al., 2023, Nature Reviews Psychology](https://doi.org/10.1038/s44159-023-00241-5) [weak]

"As sequence predictors, these models draw on the underlying statistical distribution of previously generated text to stitch together vectorized symbol strings based on the probabilities of their co-occurrence4. They therefore lack the communicatively embodied and relational functionings that are a prerequisite of scientific meaning-making, in the barest sense."<br>
[Birhane et al., 2023, Nature Reviews Physics](https://doi.org/10.1038/s42254-023-00581-4) [moderate]

"LLMs are not trained to understand language as humans do. By ‘learning’ the statistical associations between words as they have been used by humans, GPT-3 develops an ability to successfully predict which word best completes a phrase or sentence."<br>
[Thirunavukarasu et al., 2023, Nature Medicine](https://doi.org/10.1038/s41591-023-02448-8) [weak]

"A truly intelligent and creative agent/system should be capable of selecting a word
based on first-order logical and deductive reasoning thus reducing the generation of nonsensical output to nearly zero, 
as opposed to the current mechanism LLMs employ which is based on probabilistic stochastic selection, adding weight
to our categorisation of LLMs as complex “auto-complete” tools. [...] "<br>
[O'Neil & Connor, 2023, arXiv](https://doi.org/10.48550/arXiv.2307.04821) [moderate]

"Our learned ability to process and find meaning in conversational text
means that we slip, and often forget that we are not dealing with a human, and
very quickly we anthropomorphise the bot. We may attribute personality traits
to it. We may attribute an intended meaning to the generated text. Anthropomorphism of this nature is not trivial and can have serious consensuses, indeed
previous research has highlighted people’s tendency to “overtrust” robotic systems with potentially disastrous outcomes [50]." <br>
[O'Neil & Connor, 2023, arXiv](https://doi.org/10.48550/arXiv.2307.04821) [weak]

“ChatGPT ‘writes’ by estimating each new word in a sequence by statistical ranking, given the probabilities of certain words and word-pairs in its training data.19 This process doesn’t seem to require attributing knowledge, belief, or intention to ChatGPT to explain any of the processing." <br>
[van Woudenberg et al., 2024, Philosophy and Technology](https://doi.org/10.1007/s13347-024-00715-1) [moderate]

"Algorithm driven technologies are far away from having mental states and understanding concepts or theories that are often considered to be constitutive for discursive practice and hence a conversation (Green Citation2020). Thus, it must be reminded that CAI is able to mimic a conversation, not to genuinely have it. Finally, to cite famous Searle’s response to the Touring test, “[computers/programs] have only a syntax but no semantics” (Searle Citation1980)."<br>
[Sedlakova & Traschel, 2023, The American Journal of Bioethics](https://doi.org/10.1080/15265161.2022.2048739) [moderate]

"However, large language models, and other AI models like ChatGPT, are doing considerably less than what human brains do, and it is not clear whether they do what they do in the same way we do. The most obvious difference between an LLM and a human mind involves the goals of the system. Humans have a variety of goals and behaviours, most of which are extra-linguistic [...]. Large language models simply aim to replicate human speech or writing. This means that their primary goal, insofar as they have one, is to produce human-like text." <br>
[Hicks et al., 2024, Ethics and Information Technology](https://doi.org/10.1007/s10676-024-09775-5) [weak]

"Despite their sophisticated algorithms and voluminous train- ing data (encompassing materials such as web pages, Wikipedia articles, social media posts, academic articles, books and instruc- tion data), they are mathematical models and lack an understand- ing of the world. These tools are designed to predict the likelihood of text, rather than to generate truth."<br>
[Lin, 2024, Nature Human Behavior](https://doi.org/10.1038/s41562-024-01847-2) [moderate]

"Take, for example, octopuses. Certainly octopuses are intelligent. But is anybody ‘in there’? How about bees? 
Or organoids — mini brain-like structures in a dish12? As dissimilarity with us increases, we should require more 
evidence to be convinced that ‘someone’ is ‘in there’ because our prior expectations become less reliable. 
In theory, this should mean an even higher bar for AI, but instead the opposite seems to be true. We are prone to 
anthropomorphizing AI40, especially now with large language models, because they seem ‘human’ through imitating human 
language patterns so fluently."<br> 
[LeDoux et al., 2023, Current Biology](https://doi.org/10.1016/j.cub.2023.06.067) [weak]

#### Wider Media Discourse:

"Some things get better as we make these neural network models, and some don’t. The reason that some don’t, in particular reliability and truthfulness, is because these systems don’t have those models of the world. They’re just looking, basically, at autocomplete. They’re just trying to autocomplete our sentences. And that’s not the depth that we need to actually get to what people call A.G.I., or artificial general intelligence."<br>
[Marcus, 2023, Interview with Ezra Klein](https://www.nytimes.com/2023/01/06/podcasts/transcript-ezra-klein-interviews-gary-marcus.html) [strong]

"An AI doesn’t contemplate your question. When you understand how they work, even at a superficial level, you realize it’s just a statistical algorithm. It’s a very cool and impressive statistical algorithm, but it doesn’t think or consider. Some people are surprised to learn that there’s no ‘mind’ there at all."<br>
[Woolridge, 2023, Interview with Elsevier Connect](https://www.elsevier.com/connect/with-the-rise-of-llms-what-should-we-really-be-concerned-about) [strong]

"First we should ask the question, have large language models achieved anything, anything in this domain [natural language understanding]. Answer: no, they've achieved zero. [...] GPT-3 has done nothing. With a supercomputer it can look at 45 terabytes of data and find some superficial regularities, which then, it can imitate. "<br>
[Chomsky, 2023, Interview with Machine Learning Street Talk](https://www.youtube.com/watch?v=axuGfh4UR9Q) [strong]

'It doesn't matter how much you scale AI you will never have a formula that can definitely describe, model, represent (whichever terminology
you wish to use) life. [...] We as humans, I think there is something very profound in our being, in our essence – call it consciousness if you will – we can't really define
it, we can't really grasp it, but it's part of us. I think that's how we have got here.' <br>
[Santacaterina, 2024, Interview with Machine Learning Street Talk](https://www.youtube.com/watch?v=USpbuZ22kOI) [strong]

"artificial deep neural networks are very different from the human brain, and it is anthropomorphism if one thinks that they might think or anything like that. It's a statistical machine"<br>
[Gigerenzer, 2024, Interview with Seekers Mindtalks](https://www.youtube.com/watch?v=BL1af5sJjdg)[strong]

"Machines don’t learn. Right? Machines copy, and then they basically match a user’s prompt with an analysis of patterns in what they’ve copied. And then they finish the pattern based on predictive algorithms or models. Right? That’s not what humans do. Humans have lived experiences. They have souls. They have genius." <br>
[Glazer, 2024,  Hard Fork Podcast](https://www.nytimes.com/2024/06/28/podcasts/hardfork-ai-music-lawsuits.html?showTranscript=1)[strong]

"All it [Claude] does is token predictions. Yes, it uses intermediate steps that you can interpret as internal reasoning, but it's still just token predictions. It hasn't developed an abstract 'maths core' or anything."<br>
[Hossenfelder, 2025, YouTube video title 'New Research Reveals How AI "Thinks" (It Doesn't)'](https://www.youtube.com/watch?v=-wzOetb-D3w)[moderate]

### References/responses to Justaism 

"Those on the 'LLMs do not understand' side of the debate argue that while the fluency of large language models is surprising, 
our surprise reflects our lack of intuition of what statistical correlations can produce at the scales of these models. 
Anyone who attributes understanding or consciousness to LLMs is a victim of the Eliza effect (24)—named after the 1960s 
chatbot created by Joseph Weizenbaum that, simple as it was, still fooled people into believing it understood them (25)."<br>
[Mitchell & Krakauer, 2023, PNAS](https://doi.org/10.1073/pnas.2215907120)

"In response to the survey item – 'Some generative model trained only on text, given enough data and computational resources, could understand natural
language in some non-trivial sense.' – 51% agreed and the remaining 49% disagreed (out of 480 active NLP researcher respondents)."<br>
[Michael et al., 2022, arXiv](https://doi.org/10.48550/arXiv.2208.12852)

"there is a small but growing belief that a next-token predicting model is merely an impressive improv artist that cannot truly model human thought. [...] This criticism has been floating around as an informal viewpoint (LeCun, 2024; Bubeck et al., 2023)."<br>
[Bachmann & Nagarajan, 2024, arXiv](https://doi.org/10.48550/arXiv.2403.06963) 

"I suspect that the general public, including many journalists reporting on machine learning, aren’t even aware of the distinction between training the model and using it to make inferences. One simply reads that ChatGPT, or any other comparable LLM, generates text by predicting the next word. This mis-communication is a MAJOR blunder." <br>
[Benzon, 2023, LessWrong](https://www.lesswrong.com/posts/sbaQv8zmRncpmLNKv/the-idea-that-chatgpt-is-simply-predicting-the-next-word-is)

"Related hot take: how do we know that humans aren’t mostly just stochastic parrots? Wasn’t this in essence the claim made by exemplar theories that have been popular in cognitive psychology in the recent past?"<br>
[Poldrack, 2024,  Twitter](https://twitter.com/russpoldrack/status/1789131984603926971)

"i am a stochastic parrot, and so r u"<br>
[Sam Altman, 2022, Twitter](https://x.com/sama/status/1599471830255177728?lang=en)

"A lot of people will tell you 'These things aren't like us, they're just predicting the next symbol, they're not reasoning like us', but actually in order to predict the next symbol it's going to have to do some reasoning"<br>
[Hinton, 2024, Interview with Sana](https://www.youtube.com/watch?v=n4IQOBka8bc&list=WL&index=2&t=3s)
