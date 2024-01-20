# Vision Prompt Templates
* You need to [configure OpenAI Key](https://text-gen.com/configure-api-key)
* [Prompt Engineering Guide](https://docs.google.com/document/d/11WlzjBT0xRpQhP9tFMtxzd0q6ANIdHPUBkMV-YB043U)

# Prompts 
| Prompt             | Usage                                               |
| ----------------   | --------------------------------------------------- |
| describe_Images    | Using OpenAI's GPT-4-Vision, describe Images        |



# Development

| Prompt             | Usage                                               |
| ----------------   | --------------------------------------------------- |
| askGPT4            | Using OpenAI's GPT-4-Vision, ask about image        |

## Initialization section
```handlebars
{{package "vision"}}
```


## Example usage
```js
const content = await run("vision/askGPT4", {prompt, base64Image});
```
