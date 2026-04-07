# Leveraging Textual Semantic Guidance for Few-Shot Class-Incremental Learning

Official implementation of the paper: ''**Leveraging Textual Semantic Guidance for Few-Shot Class-Incremental Learning**''

*Submitted to ACM Transactions on Multimedia Computing, Communications and Applications (TOMM).*

## 📢 Code Release Plan
The code will be publicly released immediately upon the formal acceptance of the manuscript.

## 📝 Abstract
Few-shot Class-incremental Learning (FSCIL) aims to continually learn new knowledge about few-shot novel classes while retaining the previously learned knowledge of old classes. With the rapid development of vision-language models (e.g., CLIP) known for strong transferability, several studies have explored applying CLIP to FSCIL. However, they generally retain the original architecture, with visual and textual encoders operating independently, which limits the impact of textual semantics on the discriminative capability of the visual branch and somewhat restrict the model’s performance in FSCIL. In this paper, we argue that integrating class-level semantics from the CLIP textual branch into the visual branch can provide a more robust representational foundation for FSCIL. To this end, we propose LEAD, a CLIP-based FSCIL method that explicitly leverages textual semantic guidance to enhance the discriminability and generalizability of the visual branch, improving adaptability to few-shot novel classes while mitigating interference on old ones. Specifically, the Conditional Semantic Constructor (CSC) adaptively converts textual semantic cues into class-relevant guidance, and the Semantic-Enhanced Attention (SEA) module explicitly incorporates semantic guidance into the visual encoder to strengthen semantic awareness. A text-guided prototype generation strategy incrementally expands the text-guided prototype space, enhancing the distinction between different classes while promoting model stability in the incremental sessions. Extensive experiments on three benchmark datasets validate the effectiveness of LEAD and its competitive performance against existing FSCIL methods.
