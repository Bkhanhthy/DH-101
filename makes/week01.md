# Week 1 – Reverse Engineering

## 1. What Is Being Made?
DALLE 3 makes new images from text. You type what you want (“a rainy street in Tokyo, neon
signs, film photo”), and it generates an image that tries to match the details in your prompt.

## 2. What Is the Project Made From? (Data)
At a high level, it’s made from lots of image-text pairs (images with captions) and using data to
make informed actions. The model learns how to translate image to language. It’s looking for
specific details and patterns, with research on large amounts of data to make an imaginary
photo from description given by user.

## 3. Tools, Algorithms, or Systems
The project uses a neural network (GAN) that generates new images based on patterns it
learned. The process feels automated, but humans designed the system and chose what data
to include.
The core system is DALL·E 3, OpenAI’s text-to-image model. But it doesn’t work alone. It’s
tightly integrated with ChatGPT, which acts like a middle layer between the user and the image
generator.
AI is used at multiple stages such as to understand your prompt (ChatGPT rewrites or expands
it behind the scenes); generate the image; and also safety filter (other AI systems scan prompts
and images to block unsafe content)
The process is automated in turning text into images and improving prompts. However, human
is also included in the process since they still decide what to ask for and refine images through
conversation
## 4. Human Labor & Decisions
The training data was likely collected by large tech teams and data contractors, pulling from
massive image - text sources across the internet, licensed datasets, and internal collections.
Human help to give content, control, and improvise the project.
## 5. Design as Argument
It’s really to see that DALL E3 creates beautiful, polished images; fast results with minimal effort.
It makes AI look like a creative partner rather than a complex system. But it does not show
where the training images came from, who did the labor behind the scenes, or why certain
requests are blocked, and others aren’t. This make the design hide power, labor, and data
politics behind a clean and friendly interface.

## Reflection
Respond to this week’s reflection prompt in 200–300 words.

## Attribution & AI Use
- Tools used:
- AI prompts (summary):
- What AI generated:
- What you changed or decided:
