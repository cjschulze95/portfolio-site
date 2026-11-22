# Christopher Schulze | Student Portfolio

## Accessibility

After the updates, WAVE reported 0 errors and 0 contrast errors on Home,
Projects / Work, and About / Contact.

- On Projects / Work, I linked the Class projects section to its visible heading so assistive technology can identify the section by name.
- On Projects / Work, I linked the Practice and progress section to its visible heading so assistive technology can identify the section by name.
- On About / Contact, I linked the About me section to its visible heading so assistive technology can identify the section by name.
- On About / Contact, I linked the Contact section to its visible heading so assistive technology can identify the form's section by name.

## Color contrast

All three pages share the same stylesheet and dark palette. I checked these
text and background combinations with the WebAIM Contrast Checker. All six
passed WCAG AA for normal text.

| Text color | Page background `#0F172A` | Card and header background `#1E293B` |
| --- | --- | --- |
| Light text `#F1F5F9` | Pass | Pass |
| Paragraph text `#CBD5E1` | Pass | Pass (9.85:1) |
| Blue links `#38BDF8` | Pass | Pass (6.82:1) |

## Gestalt principles

- **Proximity:** I kept each project title and its details together inside one card so visitors can tell which details belong to each project.
- **Similarity:** I used the same border, rounded corners, and padding on project cards so visitors can recognize and scan them as a group.

## Accessible contact form

The form has linked labels for Name, Email, Subject, and Message. A fieldset
and legend group the contact details. A blank submission showed a visible
error beside each field. Valid entries cleared the errors and displayed a
confirmation. The form validates entries locally.
