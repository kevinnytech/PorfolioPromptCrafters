Suggested coding conventions and standards for the RoomZone codebase:

# Styleguide

This styleguide aims to set consistent coding conventions for improved readability and maintainability.

## Language

RoomZone is written in **JavaScript and JSX**. Prefer modern ES6 syntax when reasonable.

## Formatting

- Indent using 2 space tabs, no hard tabs.
- Lines limited to maximum of 80 characters.  
- Follow lint rules closely with limited disables.
- Use Prettier to auto-format where possible.

## Naming

- Use camelCase for variables, functions, components
- Use PascalCase for component file names
- Constants fully capitalized with underscores

## Components

- Functional components preferred
- Clearly comment all props interfaces
- Destructure props for concise access 
- Use Hooks for state management

## Functions 

- Perform single purpose 
- Use rest syntax over arguments 
- Default all parameters

## Asynchronous Logic

- Promise chains over nesting 
- Async/await syntax  
- Clearly handle errors

## Comments

- Summarize blocks of related code 
- Explain complex logic or derivations
- Include links to external references

