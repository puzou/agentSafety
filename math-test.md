# Math rendering test

11. multiple inline: 对 $M_r$ 中的每条记忆 $m_i$，把它与 $q_t$ 组合，交给 $\Lambda$，得到 $e_1 \xrightarrow{r_1} e_2 \xrightarrow{r_2} \cdots \xrightarrow{r_{L-1}} e_L$。

12. exact note line: 3. **生成并行推理路径。** 对 $M_r$ 中的每条记忆 $m_i$，把它与 $q_t$、当前对话上下文组合，交给函数 $\Lambda$，由 **LLM 模型** 先生成一段文本响应，再抽取其中的实体和关系，得到结构化路径 $\hat{\rho}_i=\Lambda(q_t,m_i;\theta)=(e_1 \xrightarrow{r_1} e_2 \xrightarrow{r_2} \cdots \xrightarrow{r_{L-1}} e_L)$。

13. three inline: 对 $M_r$ 中的 $m_i$，得到 $e_1 \xrightarrow{r_1} e_2 \xrightarrow{r_2} \cdots \xrightarrow{r_{L-1}} e_L$。

14. long only: $e_1 \xrightarrow{r_1} e_2 \xrightarrow{r_2} \cdots \xrightarrow{r_{L-1}} e_L$