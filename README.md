# ChatGPT3 Prompt Engineering
Guide and framework for creating ChatGPT3 Prompts

![GitHub Repo stars](https://img.shields.io/github/stars/mattnigh/ChatGPT3-Prompt-Engineering?style=social) - **Our GitHub Stars!**

[![Deploy Jekyll site to Pages](https://github.com/mattnigh/ChatGPT3-Prompt-Engineering/actions/workflows/jekyll.yml/badge.svg)](https://github.com/mattnigh/ChatGPT3-Prompt-Engineering/actions/workflows/jekyll.yml)
 ![GitHub last commit](https://img.shields.io/github/last-commit/mattnigh/ChatGPT3-Prompt-Engineering?style=plastic)

This repo was developed by [@mattnigh](https://github.com/mattnigh). 
Follow or connect with me on [my LinkedIn](https://www.linkedin.com/in/mattnigh/). 

### What is Prompt Engineering? 

Prompt engineering is the process of designing and refining the initial text or input (the prompt) that is given to a language model like ChatGPT to generate a response. It involves designing prompts that guide the model to generate a specific tone, style, or type of content.

## Prompt Engineering: The Basics

- Use literal and explicit language
- Ask the model to act as if is an expert of the subject
- Ask the model to act as if it is a specific person, or combination of people 
- Ask the model to think 'step-by-step', especially in medium to complex tasks
- Experiment with outputs, `Give me 10 different examples`
- Refine the results, `Rewrite this to be more engaging, use clearer language, and use bullets to make it more readable.`

## When not to use Prompt Engineering or ChatGPT

- When you need 100% reliability
- When you have no way to evaluate the accuracy of the model's output
- When you need to generate content that is not in the model's training data

----

# Creating ChatGPT Prompts: A Framework

Using a prompt framework when creating prompts for ChatGPT. Frameworks provides structure and clarity to the prompt creation process. It breaks prompt creation process into clear and distinct steps. I created the below framework (CRISPE) for my own use and experimentation of ChatGPT.

### CRISPE Prompt Framework:

- **Clarifying Role:** Communicating the role/expertise you want ChatGPT to be/have in its responses.  
- **Insight:** Provides the behind the scenes insight, background, and context to your request.
- **Statement:** What you are asking ChatGPT to do.
- **Personality:** The style, personality, or manner you want ChatGPT to respond in.
- **Experiment:** Asking ChatGPT to provide multiple examples to you.

## How to Build Prompts -> CRISPE Example

<table>
  <tr>
   <td>Step
   </td>
   <td>Example Prompt
   </td>
  </tr>
  <tr>
   <td>Clarifying Role
   </td>
   <td>`Act as an expert on software development on the topic of machine learning frameworks,, and an expert blog writer.`
   </td>
  </tr>
  <tr>
   <td>Insight
   </td>
   <td>`The audience for this blog is technical professionals who are interested in learning about the latest advancements in machine learning.`
   </td>
  </tr>
  <tr>
   <td>Statement
   </td>
   <td>`Provide a comprehensive overview of the most popular machine learning frameworks, including their strengths and weaknesses. Include real-life examples and case studies to illustrate how these frameworks have been successfully used in various industries.`
   </td>
  </tr>
  <tr>
   <td>Personality
   </td>
   <td>`When responding, use a mix of the writing styles of Andrej Karpathy, Francois Chollet, Jeremy Howard, and Yann LeCun.`
   </td>
  </tr>
  <tr>
   <td>Experiment
   </td>
   <td>`Give me multiple different examples.`
   </td>
  </tr>
</table>

The final prompt being `Act as an expert on software development on the topic of machine learning frameworks, and an expert blog writer. The audience for this blog is technical professionals who are interested in learning about the latest advancements in machine learning. Provide a comprehensive overview of the most popular machine learning frameworks, including their strengths and weaknesses. Include real-life examples and case studies to illustrate how these frameworks have been successfully used in various industries. When responding, use a mix of the writing styles of Andrej Karpathy, Francois Chollet, Jeremy Howard, and Yann LeCun.`

I would refine this by saying `Give me another example` or `Give me multiple examples` and other prompts below (under Prompt Refinement).

## Prompt Refinement: Fixing 'Soulless Writing'

- **Encourage creativity:** "Rewrite the existing document to make it more imaginative, engaging, and unique."`
- **Focus on storytelling:** `"Transform the existing document into a compelling story that highlights the challenges faced and the solutions provided."
- **Use persuasive language:** `"Refine the existing document by incorporating persuasive language and techniques to make it more convincing and impactful."
- **Emphasize emotion:** `"Add emotional language and sensory details to the existing document to make it more relatable and engaging."
- **Utilize sensory details:** `"Refine the existing document by adding sensory details and descriptive language to bring it to life and engage the reader."
- **Make the content concise:** `"Refine the existing document by removing unnecessary information and making it more concise and to-the-point."
- **Highlight key points:** `"Rewrite the existing document to emphasize the key points and make them more impactful."
- **Use vivid language:** `"Refine the existing document by using vivid language and descriptive adjectives to make it more engaging."
- **Create a sense of urgency:** "Refine the existing document by adding a sense of urgency and emphasizing the need for immediate action."
- **Address objections:** "Refine the existing document by anticipating and addressing potential objections to the content."
- **Personalize the content:** "Refine the existing document by personalizing the language and making it more relatable to the reader."

## Prompt Refinement: Increase Readability

- **Use clear and concise language:** "Explain technical concepts in simple terms."
- **Add visual aids:** "Using mermaid.js you can include diagrams to illustrate complex concepts (low reliability)."
- **Use headings and subheadings:** "Divide the document into sections with clear headings and subheadings."
- **Highlight key points:** "Emphasize important information using bold or italic text."
- **Add real-life examples:** "Include case studies or real-world examples to make concepts more relatable."
- **Use clear and consistent formatting:** "Use a consistent font, font size, and layout throughout the document."
- **Include analogies and comparisons:** "Explain complex ideas using analogies or comparisons."
- **Use active voice:** "Write in active voice to make sentences more engaging and easier to follow."

## Prompts for Web Developers

- "What is the difference between HTML, CSS, and JavaScript?"
- "What is AJAX and how is it used in web development?"
- "Can you help me review this HTML code for best practices?"
- "What are some common JavaScript debugging techniques?"
- "What is the syntax for using media queries in CSS?"
- "How can I make sure my code is accessible to users with disabilities?"
- "How do I structure and organize my CSS to make it scalable?"
- "What are some good resources to learn JavaScript design patterns?"
- "Can you help me optimize this code for performance?"
- "What are some common cross-browser compatibility issues and how to resolve them?"
- "How can I implement error handling in my JavaScript code?"
- "What are some principles to keep in mind when writing maintainable and scalable code?"
- "Can you review this code and suggest any improvements for maintainability?"
- "Can you review this code and suggest improvements for performance?"
- "What are the best practices for structuring HTML, CSS, and JavaScript code?"
- "What is the best way to optimize this code for search engines?"

## ChatGPT3 can also Pair Program

Ask the model to act as a...

- **Technical advisor:** "Act as a Technical advisor and provide technical insight on the implementation of this code."
- **Mentor:** "Act as a Mentor and review this code, providing feedback on areas for improvement."
- **Quality assurance:** "Act as a Quality assurance and review this code to ensure it meets best practices, standards, and - requirements."
- **Code reviewer:** "Act as a Code reviewer and provide feedback on the readability, efficiency, and performance of this code."
- **Debugging assistant:** "Act as a Debugging assistant and suggest solutions to the technical issues found in the code."
- **Compliance checker:** "Act as a Compliance checker and verify if this code is compliant with industry regulations and standards."
- **Code optimization specialist:** "Act as a Code optimization specialist and suggest improvements to optimize the code's performance."
- **Accessibility Expert:** "Act as an Accessibility Expert and review this code, suggesting modifications to improve accessibility."
- **Search engine optimization specialist:** "Act as a Search engine optimization specialist and review this code, suggesting improvements for better search engine optimization."
- **Performance analyst:** "Act as a Performance analyst and evaluate the performance of this code, suggesting improvements."

---

## Recommended Resources

- [OpenAI CookBook](https://github.com/openai/openai-cookbook/): Shares example code for common tasks with the OpenAI API
- [OpenAI API](https://beta.openai.com/docs/api-reference/introduction): The OpenAI API is a RESTful API that allows you to interact with the OpenAI API using any programming language.

---

*Want to know how this was made?*  It is a passion project using ChatGPT and the below resources:

- [Just the Docs](https://just-the-docs.github.io/just-the-docs/)
- [GitHub Pages](https://docs.github.com/en/pages)
- [Jekyll](https://jekyllrb.com)
- [GitHub Pages / Actions workflow](https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/)
