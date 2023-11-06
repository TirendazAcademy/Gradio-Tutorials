# Welcome to Gradio Tutorials
In this repo, I walk you through how to build machine learning and deep learning apps. 

[Gradio](https://www.gradio.app/) is a Python library that allows you to quickly demonstrate your ML models with an interactive web interface. You can easily create apps like this: 

```
import gradio as gr
def greet(name):
    return "Hello " + name + "!"
demo = gr.Interface(fn=greet, inputs="text", outputs="text")
    demo.launch()
```

## YouTube Videos
- ![Building & Deploying an NER App with Gradio](https://youtu.be/2iRsk7HM6kg)
