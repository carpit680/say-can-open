# _say-can-open_

This is an implementation of [google-research/saycan](https://github.com/google-research/google-research/tree/master/saycan) to use the latest open-source OpenAI API-compatible LLM alternatives for the Embodied AI pipeline.

## Do As I Can, Not As I Say: Grounding Language in Robotic Affordances

Project website: https://say-can.github.io/ 
Paper: https://arxiv.org/abs/2204.01691

**Abstract** Large language models can encode a wealth of semantic knowledge about the world. Such knowledge could be extremely useful to robots aiming to act upon high-level, temporally extended instructions expressed in natural language. However, a significant weakness of language models is that they lack real-world experience, which makes it difficult to leverage them for decision-making within a given embodiment. For example, asking a language model to describe how to clean a spill might result in a reasonable narrative, but it may not be applicable to a particular agent, such as a robot, that needs to perform this task in a particular environment. We propose to provide real-world grounding through pretrained skills, which are used to constrain the model to propose natural language actions that are both feasible and contextually appropriate. The robot can act as the language model's "hands and eyes," while the language model supplies high-level semantic knowledge about the task. We show how low-level skills can be combined with large language models so that the language model provides high-level knowledge about the procedures for performing complex and temporally extended instructions, while value functions associated with these skills provide the grounding necessary to connect this knowledge to a particular physical environment. We evaluate our method on several real-world robotic tasks, where we show the need for real-world grounding and that this approach is capable of completing long-horizon, abstract, natural language instructions on a mobile manipulator. The project's website and the video can be found at https://say-can.github.io/.

## Instructions

This is a modified implementation of SayCan on a tabletop environment. Follow the setup instructions in the notebook for dependencies and VLLM(to run an OpenAI API-compatible LLM server) installation. It should run by running each cell in order.
