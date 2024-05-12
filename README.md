# Usherai Summary  
Usherai is an easy-to-use Python module that simplifies OpenAI's artificial intelligence API for Python developers. Our module includes five simple AI-powered Python functions that can easily integrate AI into any of your Python projects (including text to speech). In order to use Usherai, you will need an OpenAI secret key that can be accessed after creating an OpenAI developer account at openai.com. Once you have access to your secret key, simply copy and paste the key into the Usherai class input and you're good to go! Created by Bertran Usher Jr.

Usher Tech is a software development consulting firm based in Las Vegas, Nevada that focuses on small-scale (affordable) software development, data processing, and AI automation integration.

## Overview

Usherai includes 5 functions that can be used to easily integrate A.I. into your Python project. Below are the functions, their descriptions, and sample usage.

### Functions 
**Overview**
IMPORTANT: Before using the ai text generator, you must first introduce your open ai api key as shown below!


```
import usher

ai = usher.ai_generator("your openai key")

text = ai.text("Funny Quote", 50)

usher.audio.say(text)

usher.audio.save(text, "testtextresponse.mp3")

```

print(text)

**usher.ai_generator.text(prompt, word_count)**

```
usher.ai_generator.text("Place promt here", word_count)

usher.ai_generator.text("Make a funny joke", 50)

- The code above will generate a funny joke in under fifty words.
```
**usher.ai_generator.command(prompt, word_count)**

```
usher.ai_generator.command("prompt", text_data, word_count)

usher.ai_generator.commad("Generate a fun fact about", "New York", "50")

-The code above will geenerate a fun fact about any topic placed into text_data. 
```

**usher.audio**

```
usher.audio.say(text_data)

usher.audio.save(text_data)

usher.audio.say("Hello")

usher.audio.save("Hello")

-The code above will generate an audio reply that says "hello". Audio.save will save the audio.

```
**usher.txt**
```
usher.txt.save(text_data)

usher.txt.save("Hello")

-the code above will save the text as a text (txt) file.

```
**Questions/Issues?**: Email bjusher820@gmail.com
