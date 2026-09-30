# Notebook

[Home](index.md)

## Table of Contents
- [Vocab](#vocab)

  - [Code Examples](#codeexamples)
    
  - [Notes](#notes)

  - [Code Blocks](#codeblock)

  - [Lists](#lists)
    
  - [Checklist](#checklists)

  - [Block Quotes](#blockquotes)

  - [Tables](#tables)
 
  - [Links & Images](#links&images)
 
  - [Collapsible sections](#collapsiblesections)
 
  - [Footnotes](#footnotes)
 
  - [Style Rules](#stylerules)
 
  - [Bottom line](#bottomline)

  - [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

## Vocab
<details>
  <summary>Algorithm</summary>
    Step-by-step instructions. 
  
    Example: The steps to making cookies and a method we use for long math problems are both examples of algorithms.
</details>

<details>
  <summary>Sequencing</summary>
    The order things happen in.

    Example: Brushing your teeth might consist of these steps: Put toothpaste on the toothbrush. Use the toothbrush to clean your teeth.
</details>

<details>
  <summary>Selection</summary>
   Selected parts of an algorithm for a specific choice

    Example: choosing clothes based off the event
</details>

<details>
  <summary>Iteration</summary>
   Parts of the code that repeat

    Example: Adding something multiple times
</details>

<details>
  <summary>Java</summary>
    programming language. Java and JavaScript are completely different languages.

</details>

<details>
  <summary>Object-oriented language</summary>
   Object-oriented programming is a way of writing code where you group related data and actions into reusable "objects," kind of like organizing tools into labeled boxes.
  
</details>

<details>
  <summary>Procedural language</summary>
   Procedural Languages focus on procedures (functions) that operate on data in a linear top-down sequence.
  
</details>

<details>
  <summary>Class</summary>
   A class in object-oriented programming is a template that combines data (attributes) and behavior (methods) to create individual objects that model real-world entities.
  
</details>

<details>
  <summary>Method</summary>
   A chunk of code that only runs when it's called.

    Example: static void myMethod() { // code to be executed }
</details>

<details>
  <summary>Console</summary>
   The area of a computer that notes from a program can be printed to. Kind of like a notebook.

    Example: On Skill Struck (python, javascript, and java) this is the area that your code is printed to
</details>

<details>
  <summary>Commenting</summary>
Information in you program that does not run, but simply meant to be informative.
  
    Example: //This is a comment in Java
</details>

<details>
  <summary>Internal Documentation</summary>
Internal documentation is the helpful comments and notes written inside your code to explain what it does, making it easier for you and others to understand and maintain later.  

</details>

<details>
  <summary>External Documentation</summary>
External documentation is the information about your code that's kept outside the actual source files, like user guides, API references, or manuals, to help others understand how to use or work with your program.  
  
</details>

<details>
  <summary>Variable</summary>
A variable is like a box that holds the information you want
  
    Example: //String weather = "sunny";
                     int age = 4;
</details>

<details>
  <summary>String</summary>
A string is a set of words or numbers that are surrounded by quotation marks. "Here is 1 string."
  
    Example: "I am a string."
</details>

</details>

<details>
  <summary>Integers</summary>
Whole numbers, which can be either positive or negative.
  
    Example: 12, -300
</details>

<details>
  <summary>Double</summary>
Used for decimal numbers.
  
    Example: 3.14, -.05
</details>

<details>
  <summary>Char</summary>
Used for a single character. Characters must be surrounded by single quotes.
  
    Example: 'A', '1', '$'
</details>

<details>
  <summary>Boolean</summary>
Represents true or false values.
  
    Example: true, false
</details>

<details>
  <summary>camelCase</summary>
CamelCase is a way of writing compound words or phrases where each word starts with a capital letter and there are no spaces
  
    Example: myVariableName or calculateTotalAmount
</details>

<details>
  <summary>Concatenation</summary>
Adding strings together to create longer strings. "Hello my name" + "is" + "Dominique"
  
    Example: print("This is " + "an example of " + "concatenation.")
             # Output: This is an example of concatenation.
</details>

## Code Examples
 
  ### Print Statements
  ```java
  public class Hello {
      public static void main(String[] args) {
          System.out.println("Hello World!");
      }
  }
  ```
  **System** accesses a Java class that's built into the language
  
  **out** is short for "output".
  
  **println** is short for "print line.

## day 0

### notes

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print


## Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

### Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

## Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

### Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals


## Checklists

When to use: Track progress on assignments or tasks.

### Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning


## Blockquotes

When to use: Call out notes, reminders, or teacher comments.

### Example:

> 💡 Remember: Loops repeat code until a condition is false.
 

## Tables

When to use: Compare values, track progress, or organize data neatly.

### Example:

| Task        | Status   | Notes          |
|--------------|------------|-----------------| 
| Homework 1  | Done #  | Submitted      |
| Homework 2  | Pending  | Needs review   |


## Links & Images

When to use: Add references, resources, or visuals.

### Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>


## Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

### Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>
 

## Footnotes

When to use: Add references or side notes without cluttering the page.

### Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.
 

## Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.
 

## Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.


## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  
