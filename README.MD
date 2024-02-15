# Snippet and Case Converter Plugin for IntelliJ IDEA

## Overview
This IntelliJ IDEA plugin enhances your coding experience by providing quick access to a predefined set of code snippets and offering a feature to convert between snake_case and camelCase. It's designed to help you insert commonly used code snippets efficiently and customize them according to your needs.

## Features
- **Snippet Insertion**: Easily insert predefined code snippets into your editor with just a few clicks or a keyboard shortcut.
- **Case Conversion**: Convert selected text between snake_case and camelCase directly within the editor.
- **Custom Keyboard Shortcuts**: Keyboard shortcuts are available for quicker access to the plugin's features, enhancing your workflow.
- **Extendable**: The plugin is designed to be easily extendable, allowing you to add more snippets or features as needed.

## Installation
You can install this plugin from the IntelliJ IDEA Marketplace. Alternatively, clone the repository and build the plugin using IntelliJ IDEA's plugin development environment.

## Usage
### Snippet Insertion
Right-click in the editor and select "Snippet" to insert a predefined code snippet at the cursor's location. Keyboard shortcuts:
- For "Snippet": Use `control meta Y` on macOS or `control alt Y` on Windows/Linux.

### Case Conversion
Select the text you wish to convert, right-click, and choose "Case Converter" from the context menu. Keyboard shortcuts:
- For "Snippet": Use `control meta U` on macOS or `control alt U` on Windows/Linux. This will toggle the selected text between snake_case and camelCase.

## Snippet Categories and Usage

### General Utility
- `#hi`: Inserts a "Hello World" println statement.

### Configuration and Setup
- `@@sba`: Spring Boot Application main class and method.
- `@@cfg`: Basic Spring Configuration class template.
- `@@sec`: Spring Security configuration template.

### Controller and Service Layers
- `@@c`: RestController with a GET endpoint.
- `@@s`: Service class with an autowired repository.
- `@@m`: GET request method template.
- `@@p`: POST request method template.

### Data Access
- `@@dao`: JpaRepository interface for repository pattern.
- `@@rep`: Custom repository interface with query methods.

### Entity and Model
- `@@ent`: JPA Entity class template.

### Advanced Services
- `@@adv`: Service class with business logic.

### Testing
- `test@s`: SpringBootTest annotation with contextLoads test.
- `test@m`: Mockito-based service test class.
- `test@ctr`: WebMvcTest for controller testing.

### Gradle Dependencies
Snippets like `^junit`, `^mockito`, `^log`, etc., insert Gradle dependencies for various Spring Boot starters and testing libraries.

### Utility Snippets
- `util@log`: Logger declaration and logging statement.
- `util@time`: Method returning the current time as a formatted string.

## Contributing
Contributions are welcome! Whether it's adding new snippets, improving existing ones, or fixing bugs, your help is greatly appreciated. Please follow our [contribution guidelines](https://github.com/your-github-repo-url/CONTRIBUTING.md) to get started.

### Reporting Issues
Found a bug or have a feature request? Please open an issue on our [GitHub repository](https://github.com/your-github-repo-url/issues).

### Submitting Pull Requests
1. **Fork** the repository on GitHub.
2. **Clone** your fork to your machine.
3. **Create a new branch** for your changes.
4. **Implement** your changes and ensure they meet the project's standards.
5. **Commit** your changes with clear and meaningful commit messages.
6. **Push** your changes to GitHub and submit a **pull request** against the main repository.

### Guidelines
Follow the project's coding and documentation standards.
Include unit tests for any new features or bug fixes.
Document any changes in the README.md as necessary.

## Code of Conduct
All contributors are expected to adhere to our [Code of Conduct](https://github.com/your-github-repo-url/CODE_OF_CONDUCT.md).

## License
This project is open-source and available under the Apache License 2.0. See the LICENSE file for more details.

## Acknowledgments
Thanks to the JetBrains team for their comprehensive plugin development documentation.
This plugin is made possible by contributions from the community. Whether you're fixing a bug, proposing a new feature, or improving our documentation, we appreciate your help in making this plugin better for everyone.

For more detailed information on contributing to open-source projects under the Apache License 2.0, including what's permitted, required, and conditional, please refer to the official Apache License Version 2.0 documentation.

Thank you for using or contributing to the Snippet and Case Converter Plugin. Together, we can make it an invaluable tool for developers using IntelliJ IDEA.