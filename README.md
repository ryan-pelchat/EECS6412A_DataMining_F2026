
Our Chosen topic is **"Detection of factual hallucinations in LLM-Generated Text".**

    - Study methods for automatically detecting factual claims in LLM-generated text that are incorrect or unsupported by available 
    evidence. Explore approaches based on self-consistency, model uncertainty, external evidence/retrieval, LLM-based verification, 
    and supervised detectors trained on LLM internal representations. Reproduce one or more recent hallucination-detection
    methods and investigate improvements in detection accuracy, efficiency, or generalization across different LLMs, tasks, 
    and domains, using public benchmarks such as RAGTruth, HaluEval, and FaithBench.




**Implementation(s) and evaluations of state-of-the-art or strong recent baseline methods**. 

If you implement the baseline from scrach, only one baseline is enough. If your baseline is hard to implement,  
you can get the code from baseline sources (or use an LLM to generate the code and make sure the code is correct),
but in this case you should choose multiple baselines to evaluate to see if you can duplicate the results.
A project midterm report describing your baseline(s) and the evaluation results, together with the code of the baseline(s), 
are due on **November 2**.
This report and the code will be worth 10% of your final grade for the course.



Useful resources:
- An article about Hallucination types (Detecting LLM Hallucinations: Strategies and Overview):
          https://medium.com/@techsachin/detecting-llm-hallucinations-strategies-and-overview-57eea69e6a07

- Paper we can replicate "AlignScore:Evaluating Factual consistency with a unified alignment function": was published in the ACL conference
      - https://arxiv.org/abs/2305.16739
      - Tried to test this out with a sample of 50 training and 50 test dataset: the github and everything works and was able to get initial results

- A survey paper on hallucinations we can use for citations an all: it is also cited in the article.
    - https://arxiv.org/abs/2311.05232. 

- A PAPER ON SELF-CHECK GPT (https://arxiv.org/abs/2303.08896): was published in ACL conference

