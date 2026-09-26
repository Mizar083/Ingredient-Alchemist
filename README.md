<p align="center">
	<img src="./icons/logo-no-slogan.png" alt="Ingredient Alchemist" width="220" />
</p>

<h1 align="center">Ingredient Alchemist</h1>

<p align="center"><strong>Turn the ingredients you have into ideas worth cooking.</strong></p>

<p align="center">
	<a href="https://ingredientalchemist.com">Open Ingredient Alchemist</a>
</p>

## What is Ingredient Alchemist?

Ingredient Alchemist is an AI-powered cooking companion that turns ingredients you have, along with your preferences and cooking constraints, into recipe ideas. It is designed to help you decide what to cook; generated content is a starting point for your own judgment and creativity.

## Features

- Generate recipe ideas from available ingredients and cooking constraints.
- Choose dietary preferences and allergies to guide recipe generation.
- Get step-by-step cooking instructions and a nutrition information table for every recipe.
- Generate AI images for recipes and request suggestions for additional ingredients.
- Save recipes, search your recipe history, mark favorites, and share recipes with an account.
- Use the interface in English, German, Spanish, or French. Translation coverage may vary by area.

## Disclaimer: AI, Allergies, and Food Safety

AI-generated recipes, instructions, and nutrition estimates can be inaccurate or incomplete. Dietary and allergen preferences are inputs to generation, not a guarantee that a recipe is safe for you. Check every ingredient, label, quantity, preparation step, and cooking temperature yourself. Do not use the app as medical or professional nutrition advice.

## Screenshots / Demo

Try the live website at [ingredientalchemist.com](https://ingredientalchemist.com). Product screenshots will be added to this documentation when approved captures are available.

## How it works

The short version: choose ingredients and preferences, generate recipe ideas with AI, then save or share recipes if you use an account. See [How Ingredient Alchemist works](HOW_IT_WORKS.md) for a simple diagram and user-level explanation.

## Technology

| Area | Technology |
| --- | --- |
| Web application | Next.js 16, React 19, TypeScript |
| Languages | `next-intl`; English, German, Spanish, and French locale resources |
| Recipe generation and imagery | Genkit and Google Gemini |
| Accounts and saved data | Firebase Authentication, Cloud Firestore, and Firebase Storage |
| Hosting | Firebase App Hosting |

## Development

This public edition is a documentation and presentation hub; it does not include the runnable application source or deployment setup. The web application is developed separately, and its user-facing updates are reflected on the [live website](https://ingredientalchemist.com). Internal development workflows and service configuration are intentionally not published here.

## Project Status

Ingredient Alchemist is available as a live website. This public repository is its documentation and presentation hub. The README describes the user-facing product at a high level; features and availability may change as the application is updated. The product does not provide medical, professional nutrition, or food-safety advice.

## Privacy / Data

This summary is not a replacement for the [Privacy Policy](https://ingredientalchemist.com/privacy-policy), [Cookie Policy](https://ingredientalchemist.com/cookie-policy), or [Third-party services notice](https://ingredientalchemist.com/third-party). Those live pages describe current practices and are the reference for details such as retention and user rights.

| Information | How it is used |
| --- | --- |
| Account details | Firebase Authentication supports account creation and sign-in. |
| Preferences and saved recipes | For signed-in users, Firebase Firestore stores account preferences and saved recipe information, including favorites. |
| Recipe requests | Ingredients, dietary and allergen preferences, and cooking constraints are sent to Google Gemini to generate recipe content. Do not include sensitive personal information in a recipe request. |
| Recipe imagery | Recipe images are generated through Google Gemini and may be stored with Firebase Storage to support the recipe experience. |
| Cookies and technical information | The app and its service providers may use cookies or process technical information. See the live privacy, cookie, and third-party notices for details. |

Recipe content and preferences are associated with an account when saved. For information about retention, account controls, deletion, and third-party processing, refer to the live policies or contact [support](mailto:support@ingredientalchemist.com).

Current legal pages:

- [Privacy Policy](https://ingredientalchemist.com/privacy-policy)
- [Terms and Conditions](https://ingredientalchemist.com/terms-and-conditions)
- [Cookie Policy](https://ingredientalchemist.com/cookie-policy)
- [Third-party services](https://ingredientalchemist.com/third-party)
- [Disclaimer](https://ingredientalchemist.com/disclaimer)
- [Imprint](https://ingredientalchemist.com/imprint)

These links are provided for convenience and are not legal advice. Refer to the live pages for current policy wording.

## Contributing

Found a bug, have a question, or want to suggest an improvement? Read the [Contributing guide](CONTRIBUTING.md) before posting. Do not publish credentials, personal data, or exploitable security details in public issues or discussions.

## License

This documentation-only publication has no reuse license. No permission is granted to copy, modify, or redistribute its documentation or brand assets. The application source is not part of this public edition.