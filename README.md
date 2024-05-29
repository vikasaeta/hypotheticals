# hypotheticals
Data for the article ["LLMs' Reading Comprehension Is Affected by Parametric Knowledge and Struggles with Hypothetical Statements"](https://arxiv.org/abs/2404.06283) 

The data in the data folder is available in two formats.  <br />
The data in the .json files is structured similarly o the data in [SQaAD2.0](https://rajpurkar.github.io/SQuAD-explorer/) and can be used to evaluate the results with the [SQuAD evaluation script](https://storageclwsprod1.blob.core.windows.net/bundles/0x6b567e1cf2e041ec80d7098f031c5c9e/contents.gz?se=2024-05-29T17%3A47%3A12Z&sp=rt&sv=2019-12-12&sr=b&rscd=inline%3B%20filename%3D%22evaluate-v2.0.py%22&rsce=gzip&rsct=text/x-python&sig=ZI8h8QTYy18ImYM0KGmFUlapGYC6UfGRIGivgvN9T4U%3D). <br />
The .txt files are structured with each line containing four tab-separated items: id, context, question, and possible answers. For *answerable* questions, possible answers are context spans separated by semicolons. For *unanswerable* questions, possible answers are represented by three dots (...).
