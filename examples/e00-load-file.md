<!-- Parent: parentpost -->
<!-- Space: MARK -->

# E000: Load File Content
<!-- Macro: {file:(.*)}
     Template: #inline
     filepath: ${1}
     inline: |
          {{ plaintext .filepath }}-->

This example will show mark tool loading a file from the file system and paste it's content to the body of the new post.

This action will require you to create a new macro.

## Example

{file:res-e00-plaintext.txt}

## Advanced Example

> Pasting as a code block

```
{file:res-e00-plaintext.txt}```
