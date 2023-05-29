---
title: "ChatGPT Prompt Engineering for Developers"
summary: Rough notes for ChatGPT Prompt Engineering for Developers from deeplearning.ai
weight: 200
---

# General Guidelines

- Use delimiters to clearly indicate distinct parts of the input. This helps the model distinguish the input text and prompt easily. (This also helps against prompt injection)
- Ask for a structured output like JSON. The structured format forces the model to produce better output.
- Ask the model to check whether conditions are satisfied before outputting the result. If the conditions are not satisfied, the model should output a message indicating the conditions are not satisfied.
- Use Few Shot Prompting. Give an example or starting point in the input prompt to help the model generate the output.
- Ask the model to specify the steps it took to arrive at the output. The steps can be in the form of sub tasks.
- When checking for the validity of the output, ask the model to generate the output along with the steps by itself before checking it for validity.

# LLM Tasks

## Summarization

- Summarization by word (token) limit.
- Summarization by focussing on semantic details.

## Inference

- Sentiment analysis
- Extract Data
- Inferring Topics

## Transformation

- Translation
- Tone Transformation
- Format Conversion
- Spell/Grammar Check

## ⭐ Expanding

- Assigning model roles will help generate better output.
- Make use of the temperature parameter.

# LLM Parameters

## Temperatures

Controls the degree of randomness in the output. The higher the temperature, the more random the output.

A temperature of 0 gives a deterministic output.
