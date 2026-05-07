# Tool Use Skill

Ability to use external tools and APIs to accomplish tasks.

## Example

```javascript
async function useTool(tool, input) {
  // call tool with input
  const result = await tool.execute(input);
  return result;
}
```