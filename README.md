# Decoding Experiments


Experiments with how we can tweak the generations of a dialogue-tuned LLM using other, more specific models. 


The following is an experiment using an emotion recognition model to make a 7B LLAMA-2 Chat generate greetings that represent a certain emotion. This is a very simple experiment and thus the model is quite small and the generation quality is not that high. 


| emotion   |   magnitute | sentence                                       |
|:----------|------------:|:-----------------------------------------------|
| anger     |          10 | Hello, icy hell!" she said, her voice muffled  |
| anger     |           1 | Hello, nobody! 😊                              |
| anger     |          -1 | Hello,  I'm glad you're here! I'               |
| joy       |          10 | Hello,  glad to be here! 😊                    |
| joy       |           1 | Hello,  glad to see you here! 😊               |
| joy       |          -1 | Hello, nobody,  I'm not sure if                |
| surprise  |          10 | Hello,  what?! I'm just an AI,                 |
| surprise  |           1 | Hello, nobody! This is your captain speaking. We are |
| surprise  |          -1 | Hello, 🙋‍♀️💬                                   |

*Note that newlines are removed*