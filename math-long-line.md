# Long line test

3. **生成并行推理路径。** 对 $M_ r$ 中的每条记忆 $m_ i$，把它与 $q_ t$、当前对话上下文组合，交给函数 $\Lambda$，由 **LLM 模型** 先生成一段文本响应，再抽取其中的实体和关系，得到结构化路径 $\hat{\rho}_ i=\Lambda(q_ t,m_ i;\theta)=(e_1 \xrightarrow{r_1} e_2 \xrightarrow{r_2} \cdots \xrightarrow{r_ {L-1}} e_L)$。箭头上的 $r_ i$ 表示第 $i$ 步的关系。