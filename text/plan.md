
## Scope
### Description
- **Scope:** Type-tagging figma api exported file with PageFly type (NOT HTML type !)
- **Not in scope**: convert whole figma file to PageFly file
### Input
- **Input:** Figma API exported file
- **Sample input:** (fill in Figma file here)
### Output
- **Output:** Type-tagging figma api exported file with an extra field for each component: PageFly type
- **Sample output:** (fill in Figma file with extra filed "pf_type" here)
### Training data 
- **Training data:** Figma API exported file with PageFly type (exactly the needed output)
## Stages
### Data pre-processing : 
**Note**: this stage is the most time-consuming stage, but we don't know the exact data yet (we will have to wait for BB to provide the data)
### Research & PoC
- Process sample data: 3d
- NLP models: 5d
- LLM models: 5d
- Combine to PoC version: 3d
Total: 16d
## Transfer and Educate:
Total: 10d (this is the time that will be slowed down when working with fresher)
## First release
- Fine tuning models: 5d
- Build pipeline: 2d
- Code: 5d
- Debug: 3d
Total: 15d
## Transfer & Second release: 
- Second release: 10d
- Transfer : 7d (this is the time that will be slowed down when working with fresher)
Total: 17d

## Est. Total Effort
- **Total:** 58d (~3 working months)
- **Notes:** this estimation does not contain the data pre-processing time, which is the most time-consuming stage.