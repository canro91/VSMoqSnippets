# Visual Studio Snippets for Moq

This repo contains [Moq](https://github.com/moq/moq4) snippets for Visual Studio

## Installation

To import this snippet into Visual Studio, follow these steps

1. Download `MoqCodeSnippets.snippet`
2. Head to "Tools" > "Code Snippets Manager"
3. Click "Import" in the lower left corner
4. Find the snippet file you downloaded on step 1. and click "Open"
5. Choose "My Code Snippets" as the location for the snippets
6. Click "Finish" and "Ok"

## Usage

### Create a `Mock`

![mn to create a Mock](/assets/NewMock.gif)

### `Setup` and `Return`

![mr to Setup/Return](/assets/Return.gif)

### `Setup` and `Throws`

![mt to Setup/Throws](/assets/Throw.gif)

## Snippets 

| Trigger | Content |
|---|---|
| `mn→` | Create a new `Mock` |
| `mr→` | `Setup` and `Return` with a mock |
| `mra→` | `Setup` and `ReturnAsync` with a mock |
| `mt→` | `Setup` and `Throws` with a mock |
| `mta→` | `Setup` and `ThrowsAsync` with a mock |
| `mi→` | Create a parameter inside a mock |
| `mta→` | Create any parameter inside a mock |