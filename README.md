# Eye-Diseases-CNN (Blindness Phase 1)(Deep learning)
<img width="798" alt="image" src="https://github.com/user-attachments/assets/68e3e2d3-5303-462f-826d-cc1124413473" />
<img width="1351" alt="image" src="https://github.com/user-attachments/assets/3d362d9d-d675-45ca-bae0-3815ebb12b21" />
<img width="1340" alt="image" src="https://github.com/user-attachments/assets/41656128-b284-4b4e-9389-37eb07724d13" />
<img width="1324" alt="image" src="https://github.com/user-attachments/assets/bc24b896-c8b9-42c0-87f4-43e1ba1d036f" />
<img width="1349" alt="image" src="https://github.com/user-attachments/assets/44bdcb09-70c2-4c53-a352-63470ff92209" />
<img width="1331" alt="image" src="https://github.com/user-attachments/assets/19793a88-364b-4df9-8ac3-92ccc3ef7db4" />
<img width="1363" alt="image" src="https://github.com/user-attachments/assets/ee5566fb-8601-4f8c-8d47-3ad30fdaa8fb" />
<img width="1341" alt="image" src="https://github.com/user-attachments/assets/16f8a4b2-636a-4617-8b04-a1754f063bb2" />
<img width="997" alt="image" src="https://github.com/user-attachments/assets/7fe7bec8-0d1c-4d29-aa25-d80503e5765f" />
<img width="1276" alt="image" src="https://github.com/user-attachments/assets/5b018e8f-7131-42c7-8fee-b0126f36953d" />
<img width="995" alt="image" src="https://github.com/user-attachments/assets/b479653d-f789-400a-979a-52cd55fb2f77" />
<img width="474" alt="image" src="https://github.com/user-attachments/assets/b05ada1e-c564-4279-91f3-9a23f17f5306" />
<img width="482" alt="image" src="https://github.com/user-attachments/assets/f7dfc124-9430-4076-b762-d110ab01e065" />
 AI-Developers  might be wondering about ways to further improve the solution. There are multiple options. First, employing a larger network architecture and increasing the number of training epochs on the pre-training stage has a high potential for a better performance. At the same time, this would require more computing power, which might not be optimal considering the possible use of the automated retina image classification in practice.

Second, image preprocessing can be further improved. During the refinement process, the largest performance gains were attributed to different preprocessing steps. This is a more efficient way to further improve the performance.

Finally, the best solutions of other competitors rely on ensembles of CNNs using different image sizes and/or architectures. Incorporating multiple heterogeneous models and blending their predictions could also improve the proposed solution. Ensembling predictions of models similar to the one discussed in this post is what helped me to place in the top 9% of the leaderboard.
