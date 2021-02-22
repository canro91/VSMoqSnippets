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

<img src="/assets/NewMock.gif" alt="mn to create a Mock" width="400" height="300">

### `Setup` and `Return`

<img src="/assets/Return.gif" alt="mr to Setup/Return" width="400" height="300">

### `Setup` and `Throws`

<img src="/assets/Throw.gif" alt="mt to Setup/Throws" width="400" height="300">

## Snippets 

| Trigger | Content |
|---|---|
| `mn→` | Create a new `Mock` |
| `mr→` | `Setup` and `Return` with a mock |
| `mra→` | `Setup` and `ReturnAsync` with a mock |
| `mt→` | `Setup` and `Throws` with a mock |
| `mta→` | `Setup` and `ThrowsAsync` with a mock |
| `mi→` | Create `It.Is` parameter inside a mock |
| `mia→` | Create `It.IsAny` parameter inside a mock |
