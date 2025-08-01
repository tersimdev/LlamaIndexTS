# @llamaindex/anthropic

## 0.3.18

### Patch Changes

- Updated dependencies [a8ec08c]
  - @llamaindex/core@0.6.16

## 0.3.17

### Patch Changes

- ddc0eaf: anthropic: stream partial tool calls
- Updated dependencies [7ad3411]
- Updated dependencies [5da5b3c]
  - @llamaindex/core@0.6.15

## 0.3.16

### Patch Changes

- Updated dependencies [8eeac33]
  - @llamaindex/core@0.6.14

## 0.3.15

### Patch Changes

- Updated dependencies [d578889]
- Updated dependencies [0fcc92f]
- Updated dependencies [515a8b9]
  - @llamaindex/core@0.6.13

## 0.3.14

### Patch Changes

- Updated dependencies [7039e1a]
- Updated dependencies [7039e1a]
  - @llamaindex/core@0.6.12

## 0.3.13

### Patch Changes

- Updated dependencies [a89e187]
- Updated dependencies [62699b7]
- Updated dependencies [c5b2691]
- Updated dependencies [d8ac8d3]
  - @llamaindex/core@0.6.11

## 0.3.12

### Patch Changes

- Updated dependencies [1b5af14]
  - @llamaindex/core@0.6.10

## 0.3.11

### Patch Changes

- Updated dependencies [71598f8]
  - @llamaindex/core@0.6.9

## 0.3.10

### Patch Changes

- c927457: Use base64 for encoding files
- Updated dependencies [c927457]
  - @llamaindex/core@0.6.8

## 0.3.9

### Patch Changes

- 5cdab12: Add Claude Sonnet 4 and Clause Opus 4 models

## 0.3.8

### Patch Changes

- Updated dependencies [59601dd]
  - @llamaindex/core@0.6.7

## 0.3.7

### Patch Changes

- Updated dependencies [680b529]
- Updated dependencies [361a685]
  - @llamaindex/core@0.6.6

## 0.3.6

### Patch Changes

- 76c9a80: Make core package a peer dependency
- Updated dependencies [d671ed6]
  - @llamaindex/core@0.6.5

## 0.3.5

### Patch Changes

- 9b2e25a: Use Uint8Array instead of Buffer for file type messages (works with non-NodeJS)
- Updated dependencies [9b2e25a]
  - @llamaindex/core@0.6.4
  - @llamaindex/env@0.1.30

## 0.3.4

### Patch Changes

- 3ee8c83: feat: support file content type in message content
- Updated dependencies [3ee8c83]
  - @llamaindex/core@0.6.3

## 0.3.3

### Patch Changes

- 0dfa371: added `option.thinking` and `option.thinking_signature` to Anthropic's chat response

  added `option.thinking_signature` to Anthropic's chat stream response

  handle `ChatMessages` with `option.thinking` and `option.thinking_signature`

## 0.3.2

### Patch Changes

- Updated dependencies [9c63f3f]
  - @llamaindex/core@0.6.2

## 0.3.1

### Patch Changes

- Updated dependencies [1b6f368]
- Updated dependencies [eaf326e]
  - @llamaindex/core@0.6.1

## 0.3.0

### Minor Changes

- 91a18e7: Added support for structured output in the chat api of openai and ollama
  Added structured output parameter in the provider

### Patch Changes

- Updated dependencies [21bebfc]
- Updated dependencies [93bc0ff]
- Updated dependencies [91a18e7]
- Updated dependencies [5189b44]
  - @llamaindex/core@0.6.0

## 0.2.6

### Patch Changes

- aea550a: Add factory convenience factory for each LLM provider, e.g. you can use openai instead of 'new OpenAI'
- Updated dependencies [40ee761]
  - @llamaindex/core@0.5.8

## 0.2.5

### Patch Changes

- 8bf1ca1: Support chat stream with tools for Anthropic LLM
- Updated dependencies [4bac71d]
  - @llamaindex/core@0.5.7

## 0.2.4

### Patch Changes

- Updated dependencies [beb922b]
  - @llamaindex/env@0.1.29
  - @llamaindex/core@0.5.6

## 0.2.3

### Patch Changes

- Updated dependencies [5668970]
  - @llamaindex/core@0.5.5

## 0.2.2

### Patch Changes

- Updated dependencies [ad3c7f1]
  - @llamaindex/core@0.5.4

## 0.2.1

### Patch Changes

- Updated dependencies [cb021e7]
  - @llamaindex/core@0.5.3

## 0.2.0

### Minor Changes

- 3564244: Add support for claude 3.7 thinking (and set default temperature to 1)

### Patch Changes

- a9c6144: Stream thinking tokens
- 3564244: add support for claude 3.7
- Updated dependencies [d952e68]
  - @llamaindex/core@0.5.2

## 0.1.2

### Patch Changes

- be74207: fix: dont add empty text block to tool call

## 0.1.1

### Patch Changes

- Updated dependencies [cc50c9c]
  - @llamaindex/env@0.1.28
  - @llamaindex/core@0.5.1

## 0.1.0

### Minor Changes

- 6a4a737: Remove re-exports from llamaindex main package

### Patch Changes

- Updated dependencies [6a4a737]
- Updated dependencies [d924c63]
  - @llamaindex/core@0.5.0

## 0.0.33

### Patch Changes

- 1c908fd: Revert previous release (not working with CJS)
- Updated dependencies [1c908fd]
  - @llamaindex/core@0.4.23
  - @llamaindex/env@0.1.27

## 0.0.32

### Patch Changes

- cb608b5: fix: bundle output incorrect
- Updated dependencies [cb608b5]
  - @llamaindex/core@0.4.22
  - @llamaindex/env@0.1.26

## 0.0.31

### Patch Changes

- 067a489: fix: missing condition to stringify tool input

## 0.0.30

### Patch Changes

- Updated dependencies [9456616]
- Updated dependencies [1931bbc]
  - @llamaindex/core@0.4.21

## 0.0.29

### Patch Changes

- d211b7a: added support for tool calls with results in message history for athropic agent
- Updated dependencies [d211b7a]
  - @llamaindex/core@0.4.20

## 0.0.28

### Patch Changes

- Updated dependencies [a9b5b99]
  - @llamaindex/core@0.4.19

## 0.0.27

### Patch Changes

- Updated dependencies [b504303]
- Updated dependencies [e0f6cc3]
  - @llamaindex/env@0.1.25
  - @llamaindex/core@0.4.18

## 0.0.26

### Patch Changes

- Updated dependencies [3d1808b]
  - @llamaindex/core@0.4.17

## 0.0.25

### Patch Changes

- 8be4589: chore: bump version
- Updated dependencies [8be4589]
  - @llamaindex/core@0.4.16
  - @llamaindex/env@0.1.24

## 0.0.24

### Patch Changes

- Updated dependencies [d2b2722]
  - @llamaindex/env@0.1.23
  - @llamaindex/core@0.4.15

## 0.0.23

### Patch Changes

- Updated dependencies [969365c]
  - @llamaindex/env@0.1.22
  - @llamaindex/core@0.4.14

## 0.0.22

### Patch Changes

- 90d265c: chore: bump version
- Updated dependencies [90d265c]
  - @llamaindex/core@0.4.13
  - @llamaindex/env@0.1.21

## 0.0.21

### Patch Changes

- Updated dependencies [ef4f63d]
  - @llamaindex/core@0.4.12

## 0.0.20

### Patch Changes

- Updated dependencies [6d22fa2]
  - @llamaindex/core@0.4.11

## 0.0.19

### Patch Changes

- a7b0ac3: feat(anthropic): support prompt caching
- Updated dependencies [a7b0ac3]
- Updated dependencies [c69605f]
  - @llamaindex/core@0.4.10

## 0.0.18

### Patch Changes

- Updated dependencies [7ae6eaa]
  - @llamaindex/core@0.4.9

## 0.0.17

### Patch Changes

- Updated dependencies [f865c98]
  - @llamaindex/core@0.4.8

## 0.0.16

### Patch Changes

- Updated dependencies [d89ebe0]
- Updated dependencies [fd8c882]
  - @llamaindex/core@0.4.7

## 0.0.15

### Patch Changes

- Updated dependencies [4fc001c]
  - @llamaindex/env@0.1.20
  - @llamaindex/core@0.4.6

## 0.0.14

### Patch Changes

- Updated dependencies [ad85bd0]
  - @llamaindex/core@0.4.5
  - @llamaindex/env@0.1.19

## 0.0.13

### Patch Changes

- Updated dependencies [a8d3fa6]
  - @llamaindex/env@0.1.18
  - @llamaindex/core@0.4.4

## 0.0.12

### Patch Changes

- Updated dependencies [95a5cc6]
  - @llamaindex/core@0.4.3

## 0.0.11

### Patch Changes

- Updated dependencies [14cc9eb]
  - @llamaindex/env@0.1.17
  - @llamaindex/core@0.4.2

## 0.0.10

### Patch Changes

- Updated dependencies [9c73f0a]
  - @llamaindex/core@0.4.1

## 0.0.9

### Patch Changes

- Updated dependencies [359fd33]
- Updated dependencies [efb7e1b]
- Updated dependencies [98ba1e7]
- Updated dependencies [620c63c]
  - @llamaindex/core@0.4.0

## 0.0.8

### Patch Changes

- Updated dependencies [60b185f]
  - @llamaindex/core@0.3.7

## 0.0.7

### Patch Changes

- Updated dependencies [691c5bc]
  - @llamaindex/core@0.3.6

## 0.0.6

### Patch Changes

- Updated dependencies [fa60fc6]
  - @llamaindex/env@0.1.16
  - @llamaindex/core@0.3.5

## 0.0.5

### Patch Changes

- Updated dependencies [e2a0876]
  - @llamaindex/core@0.3.4

## 0.0.4

### Patch Changes

- Updated dependencies [0493f67]
  - @llamaindex/core@0.3.3

## 0.0.3

### Patch Changes

- Updated dependencies [4ba2cfe]
  - @llamaindex/env@0.1.15
  - @llamaindex/core@0.3.2

## 0.0.2

### Patch Changes

- a75af83: refactor: move some llm and embedding to single package
- Updated dependencies [ae49ff4]
- Updated dependencies [a75af83]
  - @llamaindex/env@0.1.14
  - @llamaindex/core@0.3.1
