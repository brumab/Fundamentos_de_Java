# Copilot Instructions for This Java Project

## Project Overview
- This is a simple Java project structured for use with Visual Studio Code.
- Main source code is in `src/`, dependencies in `lib/`, and compiled classes in `bin/`.
- The project is intended for basic Java development and learning in VS Code.

## Key Directories
- `src/`: Place all Java source files here (e.g., `Exemplo.java`).
- `lib/`: Add any external JAR dependencies here if needed.
- `bin/`: Compiled `.class` files are output here automatically.

## Build & Run Workflow
- **Compile:** Use VS Code's built-in Java support or run `javac -d bin src/Exemplo.java` from the project root.
- **Run:** Use VS Code's Run/Debug features or run `java -cp bin Exemplo` from the project root.
- No custom build scripts or test frameworks are present by default.

## Conventions & Patterns
- Each Java class should be in its own `.java` file under `src/`.
- No package declarations are used by default; all classes are in the default package.
- No project-specific code generation, annotation processing, or advanced build tools (like Maven/Gradle) are configured.

## Integration & Dependencies
- To add external libraries, place JARs in `lib/` and update the classpath when compiling/running.
- No external services or APIs are integrated by default.

## Example Commands
- Compile: `javac -d bin src/Exemplo.java`
- Run: `java -cp bin Exemplo`
- Add a JAR: `javac -cp "lib/*;bin" -d bin src/Exemplo.java`

## Additional Notes
- For more details, see `README.md`.
- If you add new conventions or tools, update this file to help future AI agents and developers.
