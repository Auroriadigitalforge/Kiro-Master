# Debug Mentor

An AI-powered debugging assistant that helps developers understand, fix, and prevent programming errors through educational explanations at multiple complexity levels.

## Overview

Debug Mentor is a Kiro-native tool designed to transform how developers approach debugging. Instead of just providing quick fixes, it focuses on education and skill development, helping developers grow their debugging capabilities over time.

### Key Features

- **Multi-Level Explanations**: Get error explanations tailored to your skill level (Beginner, Intermediate, Advanced)
- **Educational Focus**: Learn not just what to fix, but why errors happen and how to prevent them
- **Comprehensive Analysis**: Understand root causes, get actionable solutions, and receive prevention guidance
- **Kiro-Native**: Operates entirely within Kiro without external dependencies
- **Pattern Recognition**: Handles various error formats including stack traces, compiler output, and log entries

## How It Works

1. **Input Your Error**: Paste error messages, stack traces, or log entries into the system
2. **Choose Your Level**: Select explanation complexity based on your experience
3. **Get Comprehensive Help**: Receive detailed analysis including:
   - What the error means in clear terms
   - Why it happens and what triggers it
   - Step-by-step solutions with code examples
   - Prevention strategies to avoid similar issues
   - Educational insights to improve your debugging skills

## Explanation Levels

### 🟢 Beginner
- Simple language and everyday analogies
- No assumed technical knowledge
- Step-by-step guidance with encouragement
- Focus on practical problem-solving

### 🟡 Intermediate  
- Technical explanations with clear definitions
- Multiple solution approaches
- Connections to broader programming concepts
- Educational context and reasoning

### 🔴 Advanced
- Deep technical details and system behavior
- Performance implications and optimizations
- Language specifications and standards
- Implementation-level insights

## Architecture

Debug Mentor follows a layered architecture with four core components:

```
┌─────────────────────┐
│   User Interface    │
├─────────────────────┤
│   Controller Layer  │
├─────────────────────┤
│ Error Analysis      │ ← Parsing, Classification, Context
│ Engine              │
├─────────────────────┤
│ Explanation         │ ← Multi-level Content Generation
│ Generator           │
├─────────────────────┤
│ Knowledge Base      │ ← Error Patterns, Solutions, Prevention
└─────────────────────┘
```

### Core Components

- **Error Analysis Engine**: Parses and classifies error inputs using pattern matching
- **Explanation Generator**: Creates educational content adapted to different skill levels
- **Knowledge Base**: Stores error patterns, solution templates, and prevention guidelines
- **User Interface**: Provides intuitive interaction for seamless debugging assistance

## Supported Error Types

Debug Mentor can analyze various types of programming errors:

- **Compilation Errors**: Syntax errors, type mismatches, missing imports
- **Runtime Exceptions**: Null pointer exceptions, array bounds, type errors
- **Logic Errors**: Incorrect behavior, unexpected results, algorithm issues
- **Stack Traces**: Multi-level call stacks with file and line information
- **Log Entries**: Application logs with error indicators and context

## Educational Philosophy

Debug Mentor is built on the principle that effective debugging is a learnable skill. Rather than just fixing immediate problems, it:

- **Builds Understanding**: Explains the "why" behind errors and solutions
- **Develops Intuition**: Connects specific errors to broader programming patterns
- **Prevents Recurrence**: Teaches practices that avoid similar issues
- **Grows Skills**: Adapts explanations to challenge and educate at appropriate levels

## Technical Implementation

### Kiro-Native Design
- Operates entirely within Kiro's ecosystem
- Uses Kiro's built-in AI capabilities for natural language processing
- Leverages pattern matching and template-based explanation generation
- Maintains all data within Kiro's internal storage systems

### Error Processing Pipeline
1. **Input Validation**: Verify error content contains recognizable patterns
2. **Parsing**: Extract structured information from error text
3. **Classification**: Categorize error type and map to knowledge base
4. **Analysis**: Generate root cause analysis and contextual information
5. **Explanation**: Create level-appropriate educational content
6. **Solution Ranking**: Prioritize fixes based on context and user level
7. **Prevention**: Generate guidance to avoid similar future errors

## Getting Started

1. **Access Debug Mentor** through your Kiro interface
2. **Paste your error** message, stack trace, or log entry
3. **Select your experience level** for appropriate explanation complexity
4. **Review the analysis** including explanations, solutions, and prevention tips
5. **Switch levels** to see different perspectives on the same error
6. **Apply the solutions** and learn from the prevention guidance

## Contributing

Debug Mentor is designed to grow and improve through use. The knowledge base expands with new error patterns, and explanation quality improves through feedback and iteration.

## Requirements

- Kiro IDE environment
- No external dependencies or API keys required
- Works with any programming language that generates text-based error output

## License

This project operates within the Kiro ecosystem and follows Kiro's licensing terms.

---

**Debug Mentor**: Because understanding errors makes you a better developer.
