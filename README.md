# Web AI

A picked collection of AI tools and providers, with more advanced artificial
intelligence options.

Maintained by [Webship](https://www.drupal.org/project/webship). Webship and the
[Website Starter](https://www.drupal.org/project/website_starter) use the
[UI Suite UIkit](https://www.drupal.org/project/ui_suite_uikit) theme, with [UIkit](https://getuikit.com) and
[HTMX](https://htmx.org), on top of Drupal and [Display Builder](https://www.drupal.org/project/display_builder).

## What the default recipe installs

Installing Web AI applies `recipes/default`, which installs the
[AI](https://www.drupal.org/project/ai) module with the submodules an editorial
site uses (API explorer, assistant API, chatbot, CKEditor integration, content
suggestions and logging), plus
[AI Agents](https://www.drupal.org/project/ai_agents) and
[AI Image Alt Text](https://www.drupal.org/project/ai_image_alt_text).

It installs five providers:

- [Anthropic](https://www.drupal.org/project/ai_provider_anthropic), the default provider
- [OpenAI](https://www.drupal.org/project/ai_provider_openai)
- [Gemini](https://www.drupal.org/project/gemini_provider)
- [xAI](https://www.drupal.org/project/ai_provider_xai), for Grok
- [Huggingface](https://www.drupal.org/project/ai_provider_huggingface)

Anthropic is set as the default provider for chat, vision, tools, complex JSON
and structured responses.

## API keys

No API key is set by the recipe: keys are site owner data. Add yours at
Configuration > System > Keys, then select the key on the settings form of the
provider you use, at Configuration > AI > Provider settings.

## Also available, not installed

These are required by Composer so they are ready to install when a site wants
them, and are left uninstalled by the recipe:

- [Display Builder AI](https://www.drupal.org/project/display_builder_ai)
- [AI Penpot](https://www.drupal.org/project/ai_penpot)
- [AI Playwright](https://www.drupal.org/project/ai_playwright)
