# Product Philosophy

| Field        | Value        |
| ------------ | ------------ |
| Status       | Draft        |
| Version      | 0.1          |
| Authors      | Adel         |
| Reviewers    | -            |
| Created      | 2026-07-11   |
| Last Updated | 2026-07-11   |

---

# Product Philosophy

## Introduction

Engram is built on a simple belief:

> People should spend their time learning, not organizing.

Modern learners continuously collect information from screenshots, books, PDFs, AI conversations, technical documentation, websites, videos, and personal notes. While capturing information has become effortless, organizing and maintaining it remains a manual, repetitive, and cognitively demanding task.

Engram exists to eliminate that burden.

Rather than asking users to organize their knowledge, Engram automatically understands information, identifies its meaning, connects it with existing knowledge, and continuously improves the user's personal knowledge base.

The user's responsibility is to learn.

Engram's responsibility is to remember.

---

# The Fundamental Problem

Most knowledge management systems organize files.

Some organize notes.

Others organize folders or tags.

None of these represent knowledge itself.

Knowledge is independent of the format in which it was captured.

The same idea may appear in a screenshot, a research paper, a book, a conversation with an AI assistant, or a handwritten note.

Although these sources are different, the underlying knowledge is the same.

Treating every file as an independent object fragments understanding and forces users to repeatedly organize the same information.

Engram treats every uploaded resource as evidence of knowledge rather than knowledge itself.

---

# Our Philosophy

Engram is knowledge-centric.

Files are temporary.

Knowledge is persistent.

Every uploaded resource contributes to a continuously evolving representation of what the user knows.

The system is not designed to store documents.

It is designed to build understanding.

---

# Core Principles

## 1. Knowledge Before Files

Files are containers.

Knowledge is the actual value.

Every engineering decision should prioritize preserving knowledge over preserving file hierarchy.

---

## 2. Zero Manual Organization

Users should never be required to manually create folders, collections, or tags before information becomes useful.

The system is responsible for organization.

The user is responsible for learning.

---

## 3. Every Source Has Value

Knowledge may originate from any learning resource, including:

* PDFs
* Screenshots
* Images
* Books
* AI conversations
* Technical documentation
* Videos
* Audio
* Personal notes
* Web pages

No source should receive special treatment simply because of its format.

---

## 4. Knowledge Evolves

Knowledge is never static.

As new sources are added, existing knowledge should become richer, more accurate, and better connected.

The system continuously refines its understanding instead of creating isolated duplicates.

---

## 5. Evidence Matters

Every piece of knowledge should remain traceable to its original source.

Users must always be able to understand where information originated.

Knowledge without evidence should be treated with lower confidence.

---

## 6. AI Organizes, Users Decide

Artificial intelligence assists with understanding, organization, summarization, and retrieval.

It does not replace the user's judgment.

Users remain the owners of their knowledge.

---

## 7. Local First

Users should be able to build and use their knowledge base entirely on their own devices.

Cloud services should enhance the experience, not be a requirement.

---

# Domain Vocabulary

The following terms define the language used throughout the project.

## Source

The original learning resource uploaded by the user.

Examples include PDFs, screenshots, books, AI conversations, videos, notes, and web pages.

---

## Content

The extracted information obtained from a source.

Content may include text, images, tables, metadata, or other machine-readable information.

---

## Engram

An Engram is the smallest persistent unit of personal knowledge within the system.

It represents a single idea, fact, or concept extracted from one or more learning sources.

An Engram always maintains references to the evidence from which it was derived and evolves as additional information becomes available.

---

## Evidence

A source supporting the existence or validity of an Engram.

Multiple sources may support the same Engram.

---

## Knowledge Base

The complete collection of Engrams and their relationships belonging to a user.

---

# Mental Model

Engram does not organize files.

Engram organizes knowledge.

The transformation can be represented as:

```text
Learning Sources
        ↓
Content Extraction
        ↓
Knowledge Extraction
        ↓
Engram Creation / Update
        ↓
Knowledge Relationships
        ↓
Personal Knowledge Base
        ↓
AI Reasoning & Retrieval
```

The user interacts with learning resources.

The system continuously builds understanding behind the scenes.

---

# Design Consequences

This philosophy influences every part of the system.

Examples include:

* Search should retrieve knowledge before files.
* Duplicate information should enrich existing Engrams instead of creating new isolated entries.
* Multiple sources may contribute to a single Engram.
* AI responses should be generated from the knowledge base rather than individual documents.
* Every response should be explainable through its supporting evidence.

---

# Long-Term Direction

Engram is not intended to become another cloud storage platform or note-taking application.

Its long-term objective is to become a continuously evolving personal knowledge engine capable of understanding, organizing, connecting, and reasoning over everything a user learns throughout their lifetime.

---

# Philosophy Statement

> Learn naturally.
>
> Capture everything.
>
> Organize nothing.
>
> Understand continuously.
>
> Remember forever.
