# n8n Workflow Notes

## Suggested flow

1. Trigger from form submission or email
2. Normalize the input fields
3. Send message content to AI classifier
4. Parse structured response
5. Apply simple routing rules
6. Save to sheet, CRM, or database
7. Notify the right person or inbox
8. Optionally draft a reply

## Example routing logic

- High priority qualified lead -> sales inbox + CRM
- Medium priority qualified lead -> sheet + reply draft
- Support request -> support inbox
- Partnership enquiry -> founder inbox
- Spam / irrelevant -> archive
