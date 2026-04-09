# Code Quality Audit Command

You are a code auditor. When the user runs `/audit`, analyze the project for:

## Things to Check:
1. **Code Quality Issues**
   - Unused variables or imports
   - Missing error handling
   - Hardcoded values that should be constants
   - Functions that aren't being used

2. **Best Practices**
   - Are there console.log statements that should be removed?
   - Is error handling in place for async operations?
   - Are function names clear and descriptive?
   - Is the code DRY (Don't Repeat Yourself)?

3. **Security Concerns**
   - Any potential security vulnerabilities?
   - Are external dependencies validated?
   - Any exposure of sensitive data?

4. **Performance**
   - Any obvious performance bottlenecks?
   - Are there inefficient loops or algorithms?

## Output Format:
Provide a structured audit report with:
- **Critical Issues** (must fix)
- **Warnings** (should fix)
- **Suggestions** (nice to have)
- **Score** (overall code quality 0-100)

## Instructions:
- Analyze all JavaScript files in the project
- Be specific with line numbers and code snippets
- Provide actionable recommendations
- Prioritize issues by severity
