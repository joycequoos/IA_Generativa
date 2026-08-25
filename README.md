# Generative AI

[← Back](https://github.com/JosiTubaroski/DataScience/blob/main/README.md)

Never in human history has our intelligence been as challenged as it is now: for the first time, something has shown itself capable of learning and thinking in a way comparable to the human brain. Faced with this, many denied it, others panicked — but understanding how generative AI works is the first step to knowing how to position yourself in relation to it.

## What Artificial Intelligence Is

Artificial intelligence is a machine's ability to learn and perform tasks in a way similar to a human being. The process, in short, follows three steps: the AI receives data, learns from it, and then is able to carry out actions based on what it learned.

AI isn't exactly new — several tools have used artificial intelligence for quite some time:

- **Alexa** uses artificial intelligence for voice recognition.
- **Google Translate** evolved from literal, word-by-word translations to translations that use AI to get closer to natural human speech.
- **Netflix** uses AI to recommend movies and shows, learning what each user likes and dislikes — even the thumbnails change according to each person's profile.
- **Spotify** also uses AI, analyzing everything the user listens to in order to turn that into suggestions.

What's genuinely new is **generative AI**.

## Generative AI: What It Is and Why It's Trending

The difference between "traditional" artificial intelligence and generative AI lies in the ability to create: generative AI receives information and, from it, is able to generate something new — text, images, sound, or video — according to what was requested.

## AI Terminology

A few concepts help clarify the difference between AI and generative AI:

- **Machine Learning** is the ability to learn from data. For example: software that processes payments can learn to check for signs of fraud, whether a name is linked to the correct tax ID, or whether a zip code matches the given address — but it only performs what it was trained for, nothing beyond that. This type of check can also involve computer vision.
- **LLM (Large Language Model)** is a large language model, trained on huge amounts of interconnected data, generating an output by combining that data with the information it receives.

<img width="240" height="197" alt="LLM concept" src="https://github.com/user-attachments/assets/442f73dd-7178-4b65-a931-a3e0a1e0ccf2" />

How does the model know what's right and what's wrong? There's a training period, which can involve both automated processes and human evaluation — like the kind carried out by teams at companies such as OpenAI, one of the largest AI companies in the world.

<img width="430" height="310" alt="Model training process" src="https://github.com/user-attachments/assets/8078feeb-6d57-4825-8c3c-9b0e16c0b974" />

<img width="456" height="445" alt="Human evaluation in training" src="https://github.com/user-attachments/assets/f7797a3a-3d25-450d-88e8-4b408bfcd003" />

## Fundamentals of Generative AI

### Types of Generative AI

Generative AI isn't limited to ChatGPT or text-to-text conversion — there are several other model types, and understanding each one helps you know where to use them:

- **Text-to-text** — like ChatGPT, which generates text by trying to predict the most likely continuation based on what was typed.
- **Text-to-image** — the ability to turn text (a prompt) into an image. For example, when asked for "a scene of a man walking in New York at 6 PM with a suitcase in hand," a tool like DALL-E generates an image from that description, filling in unspecified details in whatever way it judges most fitting. The more information provided in the prompt — such as the person's appearance, the exact setting, surrounding elements — the closer the result gets to what was imagined.
- **Image-to-image**

  <img width="361" height="331" alt="Image-to-image example" src="https://github.com/user-attachments/assets/abd249c2-2c7a-4a37-a504-5813ce8d9770" />

- **Speech-to-text**
- **Text-to-audio**
- **Audio-to-text**
- **Text-to-video**

  <img width="363" height="347" alt="Text-to-video example" src="https://github.com/user-attachments/assets/5a9dad74-ce87-4478-87ac-f9265bb7c0d0" />

### Proprietary Models from Big Companies

Large tech companies often have their own models, developed specifically for their products. As good as a generic model like GPT may be, these internal models can far outperform it on specific tasks.

There's no perfect model: one model may be fast but less capable; another may be slower but more accurate and specialized in a particular subject. The choice of model depends on what you're trying to solve.

## Comparing Models

There are several models available on the market, each with its own specifications, costs, and capabilities.

<img width="391" height="273" alt="Comparison between AI models" src="https://github.com/user-attachments/assets/b702dbbd-a0a0-4492-9793-83822cc6d8df" />

<img width="387" height="220" alt="Comparison between AI models" src="https://github.com/user-attachments/assets/ad62a6ec-4949-47ee-aa2a-33d07304b25e" />

<img width="368" height="197" alt="Comparison between AI models" src="https://github.com/user-attachments/assets/7d96d722-fa3e-4eed-a5e6-8d0906102f14" />

<img width="200" height="166" alt="Comparison between AI models" src="https://github.com/user-attachments/assets/0b51c441-5794-40a0-b9f3-c2f6df9afc8c" />

<img width="325" height="215" alt="Comparison between AI models" src="https://github.com/user-attachments/assets/5f1ad19f-fa1c-4b21-8e1a-209c866ec574" />

## About Model Creation

<img width="445" height="120" alt="Stages of building an AI model" src="https://github.com/user-attachments/assets/e2688f81-9562-4cb1-a266-1fabae050b62" />

## The Role of Data in AI Training

<img width="468" height="554" alt="The role of data in training" src="https://github.com/user-attachments/assets/21c32cf1-9e34-4e21-b5f8-6efd86892fcd" />

When AI doesn't have enough data, it ends up "hallucinating" — that is, generating incorrect or made-up answers that appear truthful.

<img width="468" height="490" alt="AI hallucination due to lack of data" src="https://github.com/user-attachments/assets/4b7abd7e-e99a-4a65-a01a-f726ea9c0962" />

Poorly built datasets can cause several problems during training — artificial intelligence tends to be only as good as the dataset used to train it. That's why it's essential to be careful with the data used in training: inconsistent data makes AI less reliable.

Depending on the dataset, the model will generate more or less accurate answers — there's no point, for example, asking about cooking recipes to a model trained specifically to answer questions about geometry, geography, or geology. It's very hard to train a model that "knows everything about everything," since covering every area of knowledge consistently is extremely complex.

Also, the more data a model processes, the slower it tends to become — which requires ever-increasing computational power. The quality and quantity of data are, perhaps, the most decisive factor in the final quality of a generative AI, and they also define the limits of what it's capable of doing.

## Ethics and Limitations of Generative AI

As you can already see, generative AI has significant limitations.

<img width="439" height="355" alt="Limitations of generative AI" src="https://github.com/user-attachments/assets/a2489b91-c87c-43c9-9287-7aa1984ed808" />

<img width="422" height="70" alt="Limitations of generative AI" src="https://github.com/user-attachments/assets/21823b68-e420-44de-a668-39c6caed41f5" />

The data used to train the models comes from society itself — which is why AI commonly reproduces the biases and discrimination present in that data. For example, a model trained mostly on Western images tends to predominantly generate images in that same pattern, even when applied to other cultural contexts.

Another sensitive issue involves **privacy and copyright concerns**: who authorizes the use of the data used in training? There's still no clear regulation on this — many datasets are built from data freely collected on the internet, including books and movies.

<img width="441" height="120" alt="Privacy and copyright issues" src="https://github.com/user-attachments/assets/cbb588bf-9fbe-4dfa-b25a-dd4151d808fa" />

There are also impacts on the world of work: what percentage of a job's tasks are repetitive and capable of being automated by AI? Fields like marketing and content creation, design, HR, customer service, and education are already feeling this impact in different ways.

<img width="420" height="226" alt="AI impact on marketing and content" src="https://github.com/user-attachments/assets/28a0da08-440a-464f-8eb2-7c78f45e762e" />

<img width="299" height="202" alt="AI impact on HR" src="https://github.com/user-attachments/assets/8406c2b8-0c91-46b8-8768-f3f74f7b65ae" />

<img width="344" height="283" alt="AI impact on customer service" src="https://github.com/user-attachments/assets/0b37d5eb-6504-4979-a240-42a5f68bb022" />

<img width="329" height="244" alt="AI impact on education" src="https://github.com/user-attachments/assets/7e8b3de4-0218-4a85-b13f-6d262682dd8e" />

## Everyday Applications

### Productivity (Organization, Planning, and Writing)

Tools like **Notion AI** help with organizing daily task lists, decision-making, and general planning.

<img width="501" height="573" alt="Notion AI" src="https://github.com/user-attachments/assets/8e2ff936-fe6b-46a5-8fd0-162f44e2e3bc" />

### AI in Education

AI has the ability to adapt to each student's level, learning style, and pace — including those who learn better by listening or at a pace different from the standard classroom rhythm. Possible applications include:

- Explaining a topic in a simple way.
- Creating examples tailored to the student's context.
- Supporting teachers with grading exams and building lesson plans.
- Acting as a tutor with infinite patience, available at any time.

### How to Write Good Prompts

Asking good questions of AI is a core skill: the clearer and more objective the prompts (even if still fairly general), the better the responses tend to be.

<img width="312" height="318" alt="Best practices for writing prompts" src="https://github.com/user-attachments/assets/1cf7196e-4c79-4e32-9209-9417c65d2a0f" />

<img width="325" height="142" alt="Best practices for writing prompts" src="https://github.com/user-attachments/assets/58ded562-f18f-4600-94d5-e7877463ad5f" />
