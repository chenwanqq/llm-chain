# Announcement: LLM Chain Update 0.8.2

We are excited to announce the release of LLM Chain version 0.8.2! This update introduces some important improvements to our library, making it even more powerful and easy to use.

## What's new in 0.8.2

### New `extract_labeled_text` function

We've added a new function called `extract_labeled_text` in the parsing module. This function is designed to help you parse labeled text that is often generated by LLMs (Language Learning Machines). LLMs typically generate text like this:

```markdown
- *foo*: bar
- hello: world
```

### Improved find_yaml function
In this update, we have also improved the find_yaml function. It now returns the results in the order they appear in the document, making it more consistent and easier to work with.

## Get started with 0.8.2

To start using LLM Chain version 0.8.2, update your dependency in your Cargo.toml file:

```toml
llm_chain = "0.8.2"
```

We hope you enjoy these new features and improvements! As always, if you have any questions or feedback, please feel free to reach out to our team.