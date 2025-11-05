# Dhanvi Patel
**Email:** dhp003@ucsd.edu  

**Section & Mentor:** A11 – Prof. Arya Mazumdar  

---

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting takeaway for me from this quarter has been understanding the inner workings of a LLM and seeing how the math behind it connects to its true performance on rela life scenarios. The general theme of our project which connects the concept of gradient descent to in context learnings of say a linear self attention layer has been interesting! I picked this domain hoping to learn how the technology that is truly changing the world actually learns and I think I am making significant progress in doing so. The papers that we have read have reframed how transformers can internally simulate optimization by updating hidden representations rather than weights. Seeing how sequence-based tasks reveal implicit gradient steps inside attention layers made me appreciate how model dynamics can resemble explicit optimization.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For the upcoming quarter 2, I would like to focus a bit more on how architectural changes in model training steps affect the pace of in context learning behaviour of the model. What I mean by this is integrating more concepts like - curvature correction into the transformer’s internal optimization process and understanding ideas like second order approximations. 
Another idea could be to explore how the scaling of the LSA layer vertically or horizontally would change its gradient descent like updates in context. For instance identify the contributing components that drive GD like optimization. 
We can also explore and compare how and if the model performs as effectively on different tasks. Like does it learn certain tasks faster than others? 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
As of now, the majority of our project setup focuses on reproducing the original regression experiments using pre defined tasks and hyperparameters. I would like to modify this training pipeline to tweak the setup parameters like comparing multi head and single head attention layers etc. I would also automate evaluation on held-out tasks to assess generalization more rigorously, rather than relying on qualitative visualizations alone

**What other techniques would you be interested in using in your project?**  
Some techniques and skills I would like to incorporate into my project and become better are ones that can quantify and improve the model’s in context learning behavior which plays a crucial role in communicating the findings of our project. For example, running controlled ablations on components like attention normalization or positional encoding could show which parts of the transformer are essential for gradient-style updates. I’m also interested in using loss-surface and optimization-path visualizations to compare how the model’s implicit updates differ from true gradient descent. 
