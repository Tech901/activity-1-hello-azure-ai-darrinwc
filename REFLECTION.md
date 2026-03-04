# Reflection -- Hello, Azure AI

Answer these questions after completing the activity (2-3 sentences each). Connect your answers to specific things you observed while coding and experimenting.

## 1. Service Surprises

Which of the three Azure AI services (OpenAI, Content Safety, Language) surprised you the most? Connect this to something specific you observed during your experiments -- a response you didn't expect, a behavior that seemed too easy or too hard, or a result that made you rethink how the service works.

They were actually all a lot harder to use than I thought, it might just be that I was having problems with the Python stuff in the Codespaces.

## 2. Lazy Initialization

How would you explain the lazy initialization pattern to a colleague? Why is it used instead of creating clients at the top of the file?

Lazy initialization Delays an object being created until right before it is being used. This helps keep the code together and it also allows the application to run Without crashing on startup.

## 3. Content Safety in the Real World

A resident files this complaint: *"A man was assaulted at this intersection because the street light has been out for months."* This text describes real violence but is a legitimate safety concern. Should the system block it, flag it for human review, or pass it through? What factors would you weigh in making that decision?

I would flag it for human review. Personally I don't think that anything like that should be blocked. Having a human in the loop is important, especially for local services.
