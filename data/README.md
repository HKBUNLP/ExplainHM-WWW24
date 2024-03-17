## Multimodal Debate

multimodal_debate.zip

The format of the pickle file: {'id': {'harmful': "", 'harmless': ""}, ..., 'id': {'harmful': "", 'harmless': ""}}; where harmful means the explanation from the harmful argument and harmless means the explanation from the harmless argument.

## LLM Judge

llm_judge_result.zip

The format of the pickle file: {'id': '1 or 0', ..., 'id': '1 or 0'}; where 1 means harmful and 0 means harmless.

## Data Preprocess

To generate the multimodal debate for each meme, we employed LLaVA-1.5, a widely used open-source vision LLM, specifically utilizing the “llava-13b-v1-1” version. Drawing the practice of previous work like MaskPrompt, Pro-Cap, and Mr.Harm on FHM data preprocessing, the input text is augmented with image entities and demographic information in the FHM data preprocessing for a fair comparison.