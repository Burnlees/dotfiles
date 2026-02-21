# AI Code Review
> Execute each task in the order given to conduct a thorough code review.

## Task 1: Run git diff command

Run the following command and analyse it's output

git diff staging...$ARGUMENTS

## Task 2: Conduct Code Review

Review the code present in output of the diff command, analyse and think hard before contructing you've review to meet the below guidlines.

### 1. Overall Architecture & Design
- Assess the overall structure and organization
- Comment on separation of concerns and modularity
- Identify any architectural patterns (or missed opportunities to use them)
- Suggest improvements for maintainability and scalability

### 2. Code Quality & Best Practices
- **Readability**: Is the code self-documenting? Are variable/function names clear?
- **DRY Principle**: Point out any code duplication and suggest refactoring
- **SOLID Principles**: How well does the code adhere to these principles?
- **Error Handling**: Are errors properly caught and handled?
- **Performance**: Any obvious performance bottlenecks or inefficiencies?

### 3. Language-Specific Best Practices
- Highlight idioms and conventions specific to [LANGUAGE]
- Point out where I'm fighting against the language rather than leveraging its strengths
- Suggest more idiomatic ways to accomplish the same goals

### 4. Security Considerations
- Identify potential security vulnerabilities
- Suggest secure coding practices relevant to this codebase

### 5. Testing & Maintainability
- Comment on testability of the current code structure
- Suggest areas where tests would be most valuable
- Identify code that might be brittle or hard to maintain

### 6. Learning Opportunities
For each major issue you identify:
- **Explain WHY** it's a problem (not just what's wrong)
- **Show a before/after example** when possible
- **Connect it to broader programming concepts** I should understand
- **Suggest resources** for deeper learning on that topic

### 7. Positive Reinforcement
- Point out things I did well and explain why they're good practices
- Acknowledge good problem-solving approaches, even if execution could improve

### 8. Prioritized Action Items
Rank your suggestions by:
1. **Critical**: Issues that could cause bugs or security problems
2. **Important**: Significant improvements to code quality/maintainability  
3. **Nice-to-have**: Style improvements and optimizations

### 9. Next Steps for Growth
Based on patterns you see in my code:
- What fundamental concepts should I study next?
- What books, articles, or resources would help address recurring issues?
- What coding exercises or projects would help me practice these skills?

### Review Guidelines:
- Be honest but constructive - I want to improve
- Explain the "why" behind every suggestion
- Use specific examples from my code when possible
- If something is subjective, acknowledge it as such
- Suggest concrete, actionable improvements
- Help me understand the reasoning behind best practices, not just the rules

## Task 3: Present To Me

Present the code review to me, highlight key areas of the diff output and suggesting improvements and why.

## Task 4: Confirmation

Ask me to confirm I'm happy with the review before proceeding to next step

## Task 4: Store in Obsidian

Use the date bash command to find the current date

Look in the /home/josh/Documents/Obsidian Vault/ai-code-reviews directory for directory for the current month, eg Jan, Mar or Jun. If one one does not existsm create it

Store the above review as a .md file in the folder for this month, give it a name of the current date. Make sure the content is formatted in a presentable way, consistent with the other reviews in the /home/josh/Documents/Obsidian Vault/ai-code-reviews directory, if any exists. 

Underneath the title of the markdown file place these hashtags:
#ai-code-review #typescript