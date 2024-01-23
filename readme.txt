# Repo purpose
This wordpress plugin demonstrates Gutenberg issue https://github.com/WordPress/gutenberg/issues/50229

# Steps to reproduce:
1. Add the block to a post or page. Notice that the min height and text color show as expected.
2. Update the post without pressing the change color button
3. View the updated post. Notice that the printed value for the color is #ff0000 but neither the text color nor the default height styling is applied.
4. Go back to the editor, press the change color button and save the post
5. View the post again. Notice that now styling is applied in line with the printed variable.
