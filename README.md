# claude-pdf-comparison
Method to use Claude API to compare pdf files to criteria in another pdf file

The script has built-in processes for a particular purpose. Customizations should include at a minimum in pdf-comparison-async.py:

- Your API key will need to be added at the command line.
- Revise the AI model that you want to use (line 103)
- Revise the prompt (lines 105-148)
- Revise extractions from files and outputs desired
- Input paths to your file directories or removing and using command line to identify (lines 329-330)

Code and prompt revisions were supported by the use of Claude Sonnet 4 chat and Claude 3.5 Haiku in Anthropic Console Workbench.
