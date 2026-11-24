# PromptFoo
PromptFoo Language Translation

config-multiple-translations (Multiple Translations)
Evaluate translation quality across multiple languages using standard promptfoo evals and scenarios.

You can run this example with:

npx promptfoo@latest init --example config-multiple-translations
cd config-multiple-translations
Environment Variables
Set at least one API key:

OPENAI_API_KEY - Your OpenAI API key
ANTHROPIC_API_KEY - Your Anthropic API key
Usage
Array-based testing (default):

promptfoo eval
promptfoo view
Scenario-based testing:

promptfoo eval -c promptfooconfig-scenarios.yaml
promptfoo view
