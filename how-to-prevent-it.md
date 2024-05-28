# How to prevent it?

## Keeping information up to date

This API documentation smell can be prevented by first outlining who your audience will be. If your audience is mainly developers (as it usually is), you should keep in mind the circumstances that your audience will be in, when they read your documentation.

If they are developers, and they are looking at your documentation, they must be trying to figure something out about your API. If you put yourself in their shoes, you would like answers to your problems, fairly quickly, and without much fuss.

With this in mind, you should keep your API documentation as concise as possible, while making sure that you **do not omit any crucial details that would hinder the usage or understanding of your API.**

Such details include:

* Endpoints, and how they can be used;
* Response objects;
* Any other quirks your API might have, that are not easily understandable should be specified in documentation.

## Keep it Simple

While writing your documentation, there are some points you have to follow to keep your documentation simple and efficient for the end user:

* **Provide clear and concise explanations:** Ensure your documentation is easy to understand!
  * Use simple language and avoid technical jargon whenever possible.&#x20;
  * Provide clear explanations for each API endpoint, parameter, and response.&#x20;
* **Include code examples:** You should provide some examples!&#x20;
  * To queue developers in on how to make Requests or what to expect from Responses.
* **Document error handling:** Explain the errors that can occur when using your API.
  * Provide error codes, descriptions, and potential solutions to common errors.
* **Keep documentation up to date:** Keep your documentation up to date, but iterate, don't just add on top!
  * You should change just what is necessary for a revision. Do not bloat your API documentation with methods that have deprecated, you should only keep relevant information.

## Using software to do it for you

You might also consider using software tools to do your documentation for you. Tools like [Swagger (OpenAPI)](https://swagger.io/) or [redocly](https://redocly.com/).

These tools automatically create API documentation by parsing special files or proprietary structures to build HTML pages that cover all the features defined by your API.&#x20;

These tools usually provide a base documentation that you can build up on, taking into account the principles above.

## References

{% embed url="https://nordicapis.com/helpful-api-documentation-best-practices/" %}

{% embed url="https://www.zoho.com/learn/focalpoint/api-documentation-guide.html" %}

{% embed url="https://www.postman.com/templates/e9c28f47-1253-44af-a2f3-20dce4da1f18/API-documentation/" %}
