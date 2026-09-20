# Copilot Instructions

## Project overview
This project is a small web application for managing extracurricular activities at Mergington High School. It includes a Python FastAPI backend and a static frontend served from the `src/static` folder.

## General guidance
- Prefer simple, readable, and maintainable code.
- Keep changes scoped to the task requested.
- Follow the existing project structure and naming patterns.
- Preserve backward compatibility unless the task explicitly requires a breaking change.
- Do not add unnecessary dependencies or frameworks.

## Frontend
- The app frontend lives in `src/static` and uses plain HTML, CSS, and JavaScript.
- Keep markup semantic and accessible.
- Prefer small, targeted CSS changes that match the existing style.
- Maintain responsive behavior for the existing layout.

## Backend
- The backend is in `src/backend` and uses FastAPI.
- Keep API routes organized under the appropriate router files.
- Validate request data and handle errors clearly.
- Favor straightforward logic and explicit returns.

## Validation
- Run the relevant tests or checks for the changed behavior when possible.
- If there are no automated tests for a change, verify with the smallest meaningful command or manual validation.
- Do not claim completion without evidence from the validation step.

## Security
- Validate input sanitization practices.
- Search for risks that might expose user data.
- Prefer loading configuration and content from the database instead of hard coded content. If absolutely necessary, load it from environment variables or a non-committed config file.

## Code Quality
- Use consistent naming conventions.
- Try to reduce code duplication.
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.

## Commit and review expectations
- Keep code consistent with the repository conventions.
- Avoid unrelated refactors.
- Document intent clearly in code comments only when necessary.
