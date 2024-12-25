# llm_chess

## TODOs

### Set up dataset
- [ ] Download the lichess puzzle dataset
- [ ] Extract the first 10k rows and add them to github

### Set up inference
- [ ] Configure Gemma in JAX
- [ ] Create an evaluation for the LLM
- [ ] Hillclimb the eval with prompt tuning alone

### SFT
- [ ] Fine tune the model on the puzzle dataset (first 10k rows are holdout)

### Results
- [ ] Run the eval on the fine tuned models
- [ ] ... Profit?

## Setup
- Install [pipx](https://github.com/pypa/pipx)
- Use pipx to install [Poetry](https://python-poetry.org/docs/)
