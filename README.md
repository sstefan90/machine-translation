# Machine Translation - English -> Italian
This Project contains a truncated Pytorch implementation of the architecture in the Attention Is All You Need paper. The number of encoder and decoder stacks has been reduced from 6, the number presented in the original paper, to 3. Likewise, there are only 3 multihead attention heads present in this implementation, as opposed to the 8 in the paper. The model was truncated in order to train it on a local desktop in a reasonable amount of time. 
The model was trained on transcripts from the Italian parliament and US Congress.

## Model Architecture

<img width="357" alt="Screen Shot 2023-03-26 at 11 10 25 PM" src="https://user-images.githubusercontent.com/22806151/227855235-77ad232f-4527-459e-bfe2-a6cd6b86d93d.png">


### References
Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser and Illia Polosukhin. Attention is All You Need arXiv preprint arXiv:1706.03762, 2017.
Cheers, Sasha Rush, Austin Huang, Suraj Subramanian, Jonathan Sum, Khalid Almubarak, Stella Biderman. The Annotated Transformer. Harvard nlp.
