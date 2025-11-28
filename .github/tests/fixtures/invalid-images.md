# Invalid Image Examples

These should fail stricter validation:

![]() - Empty alt and URL

![](url) - Missing alt text

![alt]() - Missing URL

![alt](   ) - Whitespace only URL

![Missing closing parenthesis](url

[Not an image](url) - Missing exclamation mark
