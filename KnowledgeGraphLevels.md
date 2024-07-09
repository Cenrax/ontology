

### 1. **Code Structure Knowledge Graph AST** 
   - **Entities**: Modules, Classes, Methods, Functions, Variables.
   - **Relationships**: Contains, Inherits, Implements, Calls, Defines, Declares.
   - **Use Case**: Understanding the structural hierarchy and dependencies in the codebase.
#### Status
   - Already implemented using syntactical AST
   - Use LLM to create the knowledge graph

### 2. **Dependency Knowledge Graph**
   - **Entities**: Libraries, Modules, Packages, External APIs.
   - **Relationships**: Depends on, Imports, Requires, Uses.
   - **Use Case**: Analyzing and managing dependencies, impact analysis for updates, and vulnerability management.

### 3. **Collaboration Knowledge Graph**
   - **Entities**: Developers, Commits, Pull Requests, Code Reviews.
   - **Relationships**: Authored, Reviewed, Merged, Commented on, Assigned to.
   - **Use Case**: Understanding team collaboration, identifying key contributors, and analyzing code review patterns.
     #### Status
   - Needs to be implemented
   - Use github commit history and the code structure knowledge graph
     

### 4. **Bug and Issue Knowledge Graph**
   - **Entities**: Bugs, Issues, Commits, Files, Classes, Methods.
   - **Relationships**: Reported in, Fixed by, Affects, Related to, Regressed by.
   - **Use Case**: Tracking bugs and issues, understanding their impact on the codebase, and linking issues to specific code components.


### 5. **Testing Knowledge Graph**
   - **Entities**: Test Cases, Test Suites, Methods, Classes, Modules.
   - **Relationships**: Tests, Covers, Fails, Passes, Related to.
   - **Use Case**: Understanding test coverage, linking tests to specific code components, and identifying areas with poor test coverage.


### 6. **Performance Knowledge Graph**
   - **Entities**: Functions, Methods, Classes, Modules, Performance Metrics.
   - **Relationships**: Measured in, Affects, Depends on.
   - **Use Case**: Analyzing performance bottlenecks, linking performance metrics to code components, and optimizing code performance.

### 7. **Design Pattern Knowledge Graph**
   - **Entities**: Domain Concepts, Classes, Methods, Variables.
   - **Relationships**: Represents, Refers to, Associated with.
   - **Use Case**: Understanding the domain-specific semantics within the code, enhancing code readability and the areas where the code is missing the design pattern

   - Companies can build their own design pattern also


