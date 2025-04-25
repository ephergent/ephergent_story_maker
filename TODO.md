# TODO

- [X] Use the 'prompt' in each reporter's content in 'reporters_image_prompts.json' to update the 'personality_prompts.json' file
- [X] Add the extra characters listed in 'reporters_image_prompts.json' to update 'personality_prompts.json'
  - [X] Create new topics,tags, voice, and prompt_file for each
    - [X] Use 'main_personality_prompt.md' and 'pixel_paradox_prompt.md' prompts as example format
    - [X] Read 'season_one_all_blog_posts.json' to find clues about each characters personality to add to their prompt
    - [X] I've included 'voices.md' to give context on KokoroTTS used to generate audio from text, use British and American voice in a mixture for the new characters

- [X] Remove the "Umbral Plane", "The Splice" dimensions from all prompts, replace with a Steam Punk themed dimension and a Goth Vampire dimension
  - [X] Come up with clever story and names for the Steam Punk themed dimension (Cogsworth Cogitarium) and the Goth Vampire dimension (Nocturne Aeturnus)
  - [X] The Goth Vampire dimension should not be the stereotypical theme, but make fun of the fears the people from the other dimensions have of them (Done in description)
  - [X] The Steam Punk themed dimension should be absurdly and ironically the most advanced society (Done in description)
  - Note: `season_one_all_blog_posts.json` was NOT modified to preserve the existing narrative arc. New dimensions are reflected in prompts and the content calendar for future use/adaptation.

- [X] Update the 'two-month-content-calendar.md' to include 'The_Ephergent_Enigma_When_the_Reporter_Becomes_the_Story.md' woven throughout the complete story arc
- [X] Update the 'two-month-content-calendar.md' to include the new dimensions as well (replacing Umbral Plane/Splice plot points)
- [X] Update all files (prompts, calendar, personality definitions) to include or replace dimensions (excluding `season_one_all_blog_posts.json`)

- [] **Blog Formatting & Features:**
  - [] Refactor `season_one_all_blog_posts.json` 'content' field to use Markdown formatting for better readability in Pelican (e.g., paragraphs, blockquotes for dialogue).
  - [] Define a strategy for injecting character images into blog posts:
    - [] Generate character images based on `personality_prompts.json`.
    - [] Decide on image injection method (using theme customization using metadata).
    - [] Implement the chosen image injection method.
  - [] Add `featured_characters` metadata field to posts in `season_one_all_blog_posts.json`.

